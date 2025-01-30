how to run

1. Download and install NodeJS

2. Install truffle and ganache using node packager manager.

   npm install -g truffle

3. Install metamask browser extension

   Download and install metamask extension

4. Configure metamask on the browser with the following details

   New RPC URL: `http://127.0.0.1:8545` *(use `port: 7545` for ganache gui, update it in the file:`truffle-config.js` as well)

   Chain ID: `1337`

5. Import account(s) using private keys from ganache-cli to the metamask extension on the browser

6. Deploy smart contract to the (local) blockchain network (i.e ganache-cli)

   # on the 22bce147_196_voting system directory 
   truffle migrate
Use `truffle migrate --reset` for re-deployments

7. Launch the development server (frontend)

   cd client
   npm install
   npm start

