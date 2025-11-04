# MemoryGamedApp
🎮 A blockchain-based memory game with on-chain score tracking using MetaMask and Sepolia testnet.

🧠 Memory Game dApp — Blockchain Score Tracker (Sepolia Testnet)
📋 Overview

This project is a decentralized application (dApp) that combines a fun Memory Card Game with on-chain score tracking using Ethereum’s Sepolia Test Network.
Players connect their MetaMask wallet, play the game, and record their scores directly on the blockchain using a Solidity smart contract.

🎯 Features

  🧩 Interactive memory game built with HTML, CSS, JavaScript

  🔗 Integrated with MetaMask using ethers.js

  💾 Records player scores on the blockchain

  🧠 Displays top 5 players and personal best scores

  🎮 Accepts any score, including zero

  💅 Smooth animations and clean responsive design

  ⚙️ Smart Contract Details

File: SmartContract.sol
Network: Sepolia Testnet
Contract Address: 0xa4008680ccf4DBB6990117616A8833CdD6c53b7c
Language: Solidity ^0.8.19

Function	Type	Description
recordScore(uint256 _score)	Write	Records a player’s score (any value allowed)
getMyBestScore()	Read	Returns the connected wallet’s best score
getTopScores()	Read	Returns top 5 players and their scores

🧰 Technologies Used
  Component	Technology
  Smart Contract	Solidity (Remix IDE)
  Blockchain Network	Ethereum Sepolia Testnet
  Wallet	MetaMask
  Frontend	HTML, CSS, JavaScript
  Library	ethers.js
  Development Tool	VS Code + Live Server
  Repository	GitHub

🚀 Setup Instructions
  1️⃣ Clone or Download
  git clone https://github.com/aaa3525/memory-game-dapp.git
  cd memory-game-dapp
  
  2️⃣ Open in VS Code
  
  Launch VS Code
  
  Open the folder
  
  3️⃣ Run with Live Server
  
  Install the Live Server extension in VS Code
  
  Right-click index.html → Open with Live Server
  
  The game opens in your browser (http://127.0.0.1:5500 or similar)
  
  4️⃣ Connect MetaMask
  
  Open MetaMask in your browser
  
  Switch to Sepolia Test Network
  
  Get free test ETH: https://sepoliafaucet.com/
  
  Click “Connect Wallet” in the game interface
  
  5️⃣ Play & Record Scores
  
  Click “New Game” to start playing
  
  Match all cards
  
  After the game ends, your score is displayed
  
  Click “Submit Score to Blockchain”
  
  Confirm the transaction in MetaMask
  
  Check your updated leaderboard and best score!

🧪 Troubleshooting
| Issue                    | Cause                                  | Solution                                        |
| ------------------------ | -------------------------------------- | ----------------------------------------------- |
| Transaction failed       | No gas or wrong network                | Get Sepolia ETH & switch to Sepolia in MetaMask |
| Wallet not connecting    | MetaMask not detected                  | Ensure MetaMask is installed & unlocked         |
| Leaderboard not updating | Contract not deployed or wrong address | Double-check contract address & ABI             |
| Live Server not working  | File not served via localhost          | Open via “Open with Live Server”                |


👩‍💻 Author

Name: Amnah Asrar
Course: Blockchain Development / Web3 Fundamentals
Instructor: Dr. Usama Arshad
Date: November 2025
Testnet Used: Sepolia
