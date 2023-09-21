## Candy Machine Minting Site
This project is a Candy Machine minting site that allows users to mint NFTs by paying with an SPL token. It includes the creation of an SPL token, a user interface for the Candy Machine, and testing with dummy accounts.

## Prerequisites
Before you begin, ensure you have met the following requirements:

Node.js and npm installed
Solana development environment set up
Phantom Wallet (or any Solana wallet) for testing
Installation

cd your-candy-machine
Install project dependencies:

 npm install
Usage
Updating config.json

Open the config.json file in your project directory.

Update the "splTokenAddress" with the address of the SPL token you created.

 {
 "splTokenAddress": "your-spl-token-address"
 }
 
Creating the UI
Follow the steps in the tutorial "Quick Node: Set Up a Minting Site" to create a user interface for your Candy Machine.

Testing Minting
Run your web application locally or deploy it to a web server. Use dummy accounts or Phantom Wallet to simulate users minting NFTs.

User Testing
Share your web application with testers and ask them to go through the minting process. Ensure that SPL tokens are correctly deducted when minting NFTs. Gather feedback on the user experience and functionality.
