# Task Management System

A decentralized task management system built using Ethereum smart contracts (Solidity) and JavaScript. This system allows users to create, complete, and track tasks on the blockchain. The application leverages MetaMask for wallet integration and Ganache as the test network.

## System Requirements

- **MetaMask Wallet** (Browser Extension):  
  Install MetaMask and set up an Ethereum wallet to interact with the smart contract.

- **Ethereum Test Network (Ganache)**:  
  Ensure you have test ETH on your Ganache network to interact with the smart contract during development and testing.

- **Remix Ethereum IDE**:  
  Used for deploying and testing the Solidity smart contract.

## Setup and Installation

### Step 1: Contract Deployment

1. **Configure Ganache**:  
   Make sure your Ganache test network is set to the Istanbul region.

2. **Deploy the Smart Contract**:  
   - Open Remix Ethereum IDE and select the Istanbul EVM version for the compiler.
   - Deploy the contract on the Ganache test network.
   - After successful deployment, copy the contract address.

3. **Update Contract Details**:  
   - Paste the contract address into the `index.js` file of the project.  
   - If there are any changes to the smart contract, make sure to update the contract ABI in the `index.js` file as well.

### Step 2: Open the Application

1. **Run the Application Locally**:
   - Use Node.js to run the application with the following command:
     ```bash
     node <filename>.js
     ```

2. **Login with MetaMask**:
   - Once the application is running, you will need to log in using your MetaMask wallet extension.

### Step 3: Add a Task

1. **Connect Wallet**:
   - Click on the "Connect Wallet" button in the application to connect the MetaMask wallet.
   - Ensure that the "Source" account (admin account) is selected, as only this account can add tasks to the contract.

2. **Add a Task**:
   - After connecting the wallet, the "Source" account can add tasks to the smart contract.
   - After adding a task, the task list will display the most recent task at the top.

### Step 4: Completing a Task

1. **Ensure Correct Wallet Address**:
   - When using the "User Account", make sure the address reflects the correct wallet and balance.

2. **Complete a Task**:
   - As a user, you can mark tasks as complete. There will be two confirmation prompts to ensure proper transaction recording.

3. **Task Completion**:
   - After confirming the transaction, your wallet balance will reflect the changes.
   - The task list will update, and completed tasks will be displayed with a strikethrough.

## Tech Stack

- **Smart Contract**: Solidity
- **Blockchain Network**: Ethereum Test Network (Ganache)
- **Frontend**: JavaScript, HTML, and CSS
- **Wallet Integration**: MetaMask
- **IDE**: Remix Ethereum IDE for Solidity

## Members

- **Leone Nel Nucup**
- **Marcus Arthanan Bada**
- **Nicolai Isaiah Santos**
