# Bitcoin Simulation with Proof-of-Work

This project is a simple **Bitcoin blockchain simulation** implemented in Python. It demonstrates core blockchain principles such as **Proof-of-Work (PoW) consensus mechanism** and **SHA-256 hashing** for block integrity.

## 🚀 Features
- **Blockchain structure** with linked blocks.
- **SHA-256 hashing** for cryptographic security.
- **Proof-of-Work (PoW)** to ensure computational difficulty.
- **Chain validation** to detect tampering.
- **Genesis Block** as the starting point of the blockchain.

## 🛠️ Installation
1. **Clone the repository:**
   ```sh
   git clone https://github.com/utkarsh1507/Blockchain_Simulation.git
   cd Blockchain_Simulation
   ```
2. **Install dependencies:**
   ```sh
   pip install -r requirements.txt
   ```

## 🏗️ Usage
Run the blockchain simulation:
```sh
python blockchain.py
```

### Example Output:
```sh
Index: 0, Transactions: Genesis Block, Hash: abc123..., PrevHash: 0
Index: 1, Transactions: Alice pays Bob 10 BTC, Hash: def456..., PrevHash: abc123...
Blockchain valid? True
Tampering detected! Blockchain invalid.
```

## 🔒 Proof-of-Work Mechanism
Each block must meet a computational requirement (hash starts with a certain number of zeros) before being added to the chain. This prevents spam and ensures network security.

## 🏗️ Docker Setup (Optional)
You can run this simulation inside a **Docker container**:
```sh
docker build -t bitcoin-simulation .
docker run bitcoin-simulation
```


---
Developed by [Utkarsh Srivastava](https://github.com/utkarsh1507) 🚀
