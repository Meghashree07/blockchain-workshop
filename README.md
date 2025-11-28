# 🎰 RandomSpin Smart Contract

## 📍 Contract Address  
**0x3Ed4a9A2F877A38f482e31EA0C0F5fC8608eEDB9**  
🔗 https://coston2-explorer.flare.network/address/0x3Ed4a9A2F877A38f482e31EA0C0F5fC8608eEDB9

---

## 📘 Project Description  
RandomSpin is a simple and beginner-friendly Web3 project built on the Flare Network.  
The goal of this project is to demonstrate how users can interact with a deployed smart contract from a modern React + Wagmi + Viem frontend.

This smart contract generates a **pseudo-random number between 0–9** every time the `spin()` function is called. The UI enables any connected wallet to trigger a spin, view the most recent result, and observe real blockchain transactions in real time.

This project is ideal for:
- Web3 beginners  
- Students learning Solidity  
- Developers experimenting with Wagmi/Viem  
- Flare builders exploring contract interactions  

---

## 🎯 What This Project Does  
- Connects to a deployed smart contract on the Flare testnet  
- Calls the `spin()` function to generate a random number  
- Displays the last generated spin result on the UI  
- Shows live transaction status, confirmations, and errors  
- Demonstrates a clean, minimalistic smart contract interaction flow  

---

## ⭐ Features  
### 🔹 **Smart Contract Features**
- Simple random number generation  
- Public `lastSpin` state variable  
- Stateless `spin()` execution except for updating result  
- Great starter template for more complex games  

### 🔹 **Frontend Features**
- Full wallet gating (user must connect wallet)  
- Loading and pending state handling  
- Realtime transaction confirmation tracking  
- Error handling and status messages  
- Clean UI written in modern React + Tailwind  
- Minimal and beginner-friendly architecture  

### 🔹 **Technical Stack**
- **Smart Contract:** Solidity (Flare EVM)  
- **Frontend:** React + Next.js  
- **Web3:** Wagmi + Viem  
- **Network:** Flare Coston2 Testnet  

---

## 🛠️ How It Solves the Problem  
Blockchain beginners often struggle with:  
- Interacting with on-chain contracts  
- Understanding wallet state management  
- Handling loading, pending, and confirmation states  
- Reading data from contracts  
- Triggering on-chain actions from the UI  

This project solves those challenges by providing a **complete working example** with clean code.

### ✔ **Use Case 1: Learning Web3 Interactions**  
Developers can learn how to:
- Connect wallets  
- Read contract data  
- Write to smart contracts  
- Track confirmations in real-time  

### ✔ **Use Case 2: Starting Point for Mini-Games**  
RandomSpin can be extended into:
- Prize wheels  
- NFT spin mints  
- Loot box systems  
- Game reward systems  

### ✔ **Use Case 3: Understanding Viem + Wagmi Workflow**  
The project demonstrates:
- Contract ABI integration  
- Using hooks to read/write contracts  
- Using `useWaitForTransactionReceipt`  
- Managing UI state during blockchain operations  

---

## 🚀 Summary  
RandomSpin is a complete, minimal, and beginner-friendly Web3 project demonstrating how to call a deployed Flare contract, show UI states, and track blockchain transaction lifecycles.

Use it as a template, expand it into a game, or integrate it into your own Flare-based applications.

Happy Building! 🎉
