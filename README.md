##SocialPost - Get Paid for Quality Social Media Posts

## Pre-reqs:

node.js
truffle
testrpc
metamask


Launch:

Tmux is your best bet. 

Window 1
$ npm install

Window 2
$ ./starttestrpc.sh

Window 3
$ truffle migrate --reset

Browser
Set Metamask to "Localhost 8545".
Import accounts defined in your testrpc Ethereum node.

Private keys to import:

Coinbase
* 0x351494a5ae8f9b70a2a2fd482146ab4578f61d4d796685c597ec6683635a940e

Account 1
* 0x4cd491f96e6623edb52719a8d4d1110a87d8d83e3fa86f8e14007cb3831c0a2b

Account 2
* 0x0ef40e0d6ada046010b6965d73603cabae1a119ca804f5d9e9a9ce866b0bea7d

You can name these accounts anything you want. First account is the coinbase account.

$ npm run dev
URL: http://localhost:3000

Change to Account 1 that you imported in Metamask

Submit a post that will be worthy of a tip from another user's account (You will be required to pay a small fee, but if you get tipped, you will recoup and earn ETH). If your article receives a tip, it will be visible permanently in the "View Tipped Articles" tab with the tipper's wallest address.


#based off github.com/Chainskills
