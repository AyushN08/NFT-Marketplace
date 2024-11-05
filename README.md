
# NFT Marketplace

This project is a decentralized NFT (Non-Fungible Token) marketplace built using **Next.js** for the frontend and **Hardhat** for smart contract development and deployment. The marketplace allows users to mint, buy, sell, and trade unique digital assets securely on the blockchain.

## Features

- **Decentralized Platform**: Fully decentralized using Ethereum blockchain.
- **Smart Contracts**: Developed and tested using Hardhat.
- **Minting NFTs**: Users can create and mint their own NFTs.
- **Marketplace Functionality**: Buy, sell, and trade NFTs.
- **Interactive UI**: Built with Next.js for a responsive and dynamic user experience.
- **Wallet Integration**: Connect your crypto wallet for transactions.
- **Test Environment**: Includes local blockchain simulation for testing.

## Technologies Used

- **Next.js**: React framework for server-side rendering and static web applications.
- **Hardhat**: Ethereum development environment for compiling, deploying, and testing smart contracts.
- **Ethers.js**: Library for interacting with the Ethereum blockchain.
- **IPFS**: Decentralized storage for NFT metadata and assets.
- **Tailwind CSS**: Utility-first CSS framework for designing a responsive UI.
  
## Installation

1. Clone the repository:
   git clone https://github.com/AyushN08/NFT-Marketplace.git
   cd nft-marketplace

2. Install dependencies:
   npm install

3. Start the local blockchain:
   npx hardhat node

4. Deploy contracts:
   npx hardhat run scripts/deploy.js --network localhost

5. Run the development server:
   npm run dev

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request.

## License

This project is licensed under the MIT License.
