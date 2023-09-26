# Audio-Video-NFT-Marketplace-RSK

Welcome to the Audio-Video-Compatible-NFT Marketplace, a decentralized NFT trading platform built on the RSK (Rootstock) Blockchain. This marketplace allows users to mint, buy, sell, and view non-fungible tokens (NFTs) with ease. Below, you'll find essential information on how to set up and use this platform.

## Introduction
The Audio-Video-Compatible-NFT Marketplace is a decentralized platform that leverages the RSK blockchain to provide users with fast and cost-effective NFT transactions. It offers a user-friendly interface, secure transactions through RSK, and smart contracts designed specifically for NFTs on the RSK network.

## Functionality
The platform provides the following key functionalities:

- **Mint NFTs:** Users can mint new NFTs by uploading video or audio files and specifying a name and price. Minted NFTs are stored in the user's account.

- **List NFTs for Sale:** Users can list their minted NFTs for sale, making them available for purchase by other users.

- **Purchase NFTs:** Users can browse the marketplace and purchase NFTs listed by other users. Ownership of the purchased NFTs is transferred to the buyer.

- **View Owned NFTs:** Users can view and manage the NFTs they own, including the option to relist them for sale.

## Key Functions
The core functions of the marketplace's smart contract include:

- `MintProduct`: Minting a new NFT to the caller's address, accepting a file link, name, and price as parameters.

- `BuyProducts`: Allowing buyers to purchase multiple listed NFTs, transferring ownership to the buyer.

- `GetAllProducts`: Returning metadata of all minted NFTs on the contract, used to display listings.

- `Resale`: Allowing NFT owners to relist their NFTs for sale, accepting a new price as a parameter.

## Running the Project
To run the project on the RSK Testnet, follow these steps:

### Step 1: Setup the RSK Testnet in Metamask
1. Open Metamask and access "Settings."
2. Select "Networks" from the settings menu.
3. Click "Add a Network" to create a custom network.
4. Fill in the network details as follows:
   - Network Name: RSK Testnet
   - New RPC URL: https://public-node.testnet.rsk.co
   - Chain ID: 31
   - Currency Symbol: tRBTC
   - Block Explorer URL (Optional): https://explorer.testnet.rsk.co
5. Click "Save" to add the RSK Testnet to Metamask.

### Step 2: Obtain Test TRBTC Tokens from the RSK Testnet Faucet
1. Visit the RSK Testnet faucet at https://faucet.rsk.co/.
2. Enter your wallet address to receive test TRBTC tokens.
3. Complete any required captcha or verification steps, if prompted.
4. Click "Submit" to receive test TRBTC tokens in your wallet.

### Step 3: Access and Use the Project
- NFT Marketplace Hosting Link: [Project Hosting](https://nandinidusane.github.io/Audio-Video-NFT-Marketplace-RSK/)

### Author: Nandini Dusane
### Email: npdusane@gmail.com
### Linkedin: https://www.linkedin.com/in/nandinidusane/
