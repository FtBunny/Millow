# 🏠**Millow** Real Estate dApp Frontend  

A **React.js frontend** for a blockchain-based **real estate marketplace**.  
Users can **browse homes, view details, and interact with Ethereum smart contracts** (`RealEstate` and `Escrow`).  

---

## 🔎 Preview  

![App Screenshot](src/assets/screenshot.png)  

---

## 📦 Prerequisites  

Before you begin, make sure you have the following installed:  

- 📌 **Node.js** (v18+ recommended)  
- 📌 **npm**  
- 🔗 **MetaMask** (or any Ethereum wallet browser extension)  
- 🖥️ **Git** for cloning the repository  
- ⚡ For full interaction with the dApp:  
  - **Hardhat** (Ethereum dev environment)  
  - Deployed **`RealEstate`** and **`Escrow`** smart contracts  

---

## ⚙️ Setting Up  

 1. **Clone the Repository**

  ```
  git clone https://github.com/FtBunny/Millow.git
  cd Millow
  ```

2. **Install Dependencies**
  ```
  npm install
  ```

3. **Run Tests (Optional)**
  ```
  npx hardhat test
  ```

4. **Start Hardhat Node**
  ```
  npx hardhat node
  ```

5. **Deploy Contracts**  
  In a separate terminal:
  ```
  npx hardhat run ./scripts/deploy.js --network localhost
  ```

6. **Start Frontend**
  ```
  npm start
  ```
  The app will open at [http://localhost:3000](http://localhost:3000)

  > Make sure your MetaMask is connected to localhost 8545 (Hardhat network).

---

##  🔧 Configuration

- **Connect to the right network:**  
Open `config.json` in the project root and update the addresses for your `RealEstate` and `Escrow` contracts. 

- **MetaMask Account:**  
✅ Ensure MetaMask is connected to the same network as your contracts (e.g. Hardhat localhost, Goerli, or Ethereum mainnet).


---

## 🚀 Usage  

- 🏡 **Browse Homes** → All homes minted in `RealEstate` contract will appear on the homepage  
- 🔍 **Search Homes** → Filter properties using the search component  
- 📋 **View Details** → Click a property card to view its details in a popup  
- 🔑 **Interact with Smart Contracts** (if enabled):  
  - Buy a home via the `Escrow` contract  
  - Ensure you have enough test ETH (in testnet) or ETH (on mainnet)  

---

##  🤝 Contributing

1. Fork the repository.
2. Create a feature branch:
  ```
  git checkout -b feature/my-feature
  ```
3. Make changes and commit:
  ```
  git commit -m "Add my feature"
  ```
4. Push to your branch:
  ```
  git push origin feature/my-feature
  ```
5. Open a pull request.

---

## 📜 License  

MIT 
