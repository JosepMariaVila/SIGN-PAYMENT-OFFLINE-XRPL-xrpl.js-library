Sign a transaction offline from html input data and then submit it to the XRPL. 

It uses the xrpl.js library.

It uses a seed to derive the account address and sign transactions, 2 options are possible:

Option A: 29 characters seeds (suNq9PQrYKEifmLdFs9NPjdLeyMKm) which correspond to the secp256k1 algorithm.

Option B: 31 characters seeds (sKdNVBLAmVjgcDrEfDSzTSBqsagHMEd) which correspond to the ed25519 algorithm.

You need Node.js and VisualStudioCode to set up the project. Then you would sign completely offline through the HTML file.

Step by step guide to use the code:

1) Create an empty folder in your desktop and name it as you like

2) Download the 2 files I have in this project and put them in that folder:
   signsubmit.js
   signsubmit.html

3) Open that folder with VSC, or when you are in VSC open that folder

4) Open a terminal and type (it creates a basic package.json): npm init --yes

5) Then type in the terminal (it installs the library): npm install --save xrpl

6) Close VisualStudioCode
  
7) Open the folder and open the HTML file and disconnect the internet connection

8) Populate the html fields and SIGN the transaction offline

9) Then copy the tx blob and past it in the Tx_blob section bellow and SUBMIT the transaction online, watch the results

To try it online here: https://skunk-proper-smoothly.ngrok-free.app/tools/signofflinepayment/signsubmit
