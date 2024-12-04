# **Freelance Service Management Smart Contract**  
_A Blockchain-Based Solution for Secure and Transparent Freelancing_  

## **Features**  
- **Deposit Funds**: Clients can securely deposit payment for services.  
- **Complete Work**: Freelancers can mark tasks as complete to release funds.  
- **Renew Contract**: Extend contracts for additional work.  
- **Feedback System**: Clients can provide ratings stored on the blockchain for transparency.  

## **Tech Stack**  
- **Smart Contract**: Written in Solidity and deployed on Ethereum.  
- **Testing Framework**: Truffle Suite (Truffle, Ganache, and Mocha).  
- **Frontend**: React.js for interacting with the contract.  
- **Wallet Integration**: MetaMask for Ethereum transactions.  

---

## **Installation**  

### **Prerequisites**  
Ensure the following tools are installed on your system:  
1. [Node.js](https://nodejs.org)  
2. [Truffle Suite](https://trufflesuite.com) (`npm install -g truffle`)  
3. [Ganache](https://trufflesuite.com/ganache/)  
4. [MetaMask](https://metamask.io/)  

---

### **Setup Steps**  
1. Clone this repository:  
   ```bash  
   git clone https://github.com/your-username/freelance-service-management.git  
   cd freelance-service-management

   
Install dependencies:
npm install  
Start Ganache and note the RPC server URL (e.g., http://127.0.0.1:7545) and network ID.

Compile the smart contracts:
truffle compile 

Deploy the contracts to Ganache:
truffle migrate --reset  
Run contract tests:


truffle test  
Navigate to the frontend directory and start the React development server:


cd freelance-service-management 
npm start  
Open the application in your browser and connect MetaMask to the Ganache network.
