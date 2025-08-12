Ethereum NFT Marketplace
Author: Vidya Thakur

A decentralized application built on Ethereum that allows users to mint, list, buy, and sell NFTs securely using smart contracts. Designed for transparency, permanence, and decentralization.

Key Features
NFT Minting: Users create NFTs with name, description, and image stored on IPFS.

Decentralized Trading: Buyers purchase NFTs directly from sellers using Ether.

Listing & Offers: Sellers can set prices and manage active offers.

Ownership Proof: All transactions recorded on Ethereum blockchain.

Secure Withdrawals: Sellers claim earnings directly from smart contracts.

Technology Stack
Blockchain: Ethereum, Solidity

Front-end: React.js, Tailwind CSS

Blockchain Interaction: Web3.js, Metamask

Development Tools: Truffle, Ganache

Storage: IPFS

Backend: Node.js

Setup & Deployment
Clone Repo:

bash
Copy
Edit
git clone https://github.com/ra0321/NFT-Marketplace.git
Install Dependencies:

bash
Copy
Edit
npm install && npm install -g truffle
Compile Contracts: truffle compile

Run Local Blockchain: Using Ganache.

Start Front-end: npm start

Deploy on Testnet: Configure .env with PRIVATE_KEYS and INFURA_API_KEY, then

bash
Copy
Edit
truffle migrate --network ropsten
Architecture
Frontend (React.js) communicates with Ethereum Smart Contracts via Metamask & Web3.js.

NFT data stored on IPFS; hashes recorded on-chain for verification.

Smart Contracts manage NFT ownership, sales, and payments.

Resources
Ethereum.org

Truffle Suite

IPFS
