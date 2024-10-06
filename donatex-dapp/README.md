# DonateX - Microsoft Hackathon (September 2024)

## Project Description

This project is a **decentralized crowdfunding platform** created during the **Microsoft Hackathon (September 2024)**. It allows users to create and contribute to fundraising campaigns using blockchain technology, ensuring transparency and security via smart contracts. The project aimed to familiarize the team with **Web3 development**, focusing on tools like **Truffle**, **Ganache**, **Solidity**, and **React**.

## Purpose

The main objective was to explore Web3 development, gaining practical experience with blockchain and decentralized technologies. By building this dApp, we were able to learn smart contract development, deployment, and integration with modern frontend tools. The project highlights a seamless interaction between Ethereum smart contracts and a React-based frontend.

## Technologies Used

- **Solidity**: For writing smart contracts to manage campaigns, contributions, and withdrawals.
- **Truffle**: Used for compiling, testing, and deploying the smart contracts.
- **Ganache**: Local blockchain environment for testing and simulating Ethereum transactions.
- **React (Context API)**: Frontend framework for building the UI and managing global state (e.g., wallet connection).
- **Apollo Client**: For data fetching via GraphQL, allowing interaction with blockchain data.
- **Web3.js / Ethers.js**: Libraries used to connect the frontend to Ethereum blockchain for sending transactions and retrieving data.
- **MetaMask**: For user authentication and wallet management.

## Features

- **Campaign Creation**: Users can create a campaign by specifying details like target goal and deadline.
- **Contributions**: Contributors can donate crypto to campaigns. All contributions are recorded on the blockchain.
- **Fund Withdrawal**: Campaign creators can withdraw funds if the fundraising goal is met.
- **Blockchain Transparency**: All interactions are managed via Ethereum smart contracts, ensuring decentralization and security.

## How to Run

1. **Smart Contract Deployment**:
   - Use Truffle to compile and deploy the contracts on a local network (Ganache) or a testnet.
   
2. **Frontend Setup**:
   - Navigate to the frontend directory and install dependencies:
     ```bash
     npm install
     ```
   - Start the React app:
     ```bash
     npm start
     ```

3. **Connect MetaMask**:
   - Open the app in your browser and connect MetaMask to interact with the platform.

## Conclusion

This project helped us explore **Web3 technologies**, combining blockchain with modern web development tools. By building this decentralized crowdfunding platform, we successfully demonstrated the potential of blockchain in creating transparent and secure fundraising systems.
