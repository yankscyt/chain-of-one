# Chain of One

**Blockchain-based Carbon Credit Tracking System**

---

## 🚀 Project Overview
**Chain of One** is a blockchain-powered system that tracks, trades, and redeems carbon credits. Companies or individuals who plant trees, adopt renewable energy, or reduce emissions can earn carbon credits. These credits are recorded on the blockchain to ensure transparency, prevent double-counting, and allow for fair, trustworthy exchanges.

The project leverages **Cardano blockchain** for secure, decentralized record-keeping while storing proofs (photos, geotags, timestamps) off-chain. Only the **hash** of the proof is written on-chain, ensuring efficiency and immutability.

---

## 🌍 Motivation & Problem Statement
- **Lack of trust**: Traditional carbon credit systems risk fraud and double-counting.  
- **Transparency gap**: Companies and individuals need a reliable way to verify credits.  
- **Sustainability goals**: Encourage more people to adopt eco-friendly practices.  
- **Blockchain advantage**: Decentralized, tamper-proof ledger builds trust.

---

## 🎯 Objectives
1. Design a credit issuance system tied to verifiable eco-actions.  
2. Store proofs off-chain while securing hashes on the blockchain.  
3. Enable transparent credit trading and redemption.  
4. Provide user-friendly interfaces (API + frontend).  
5. Encourage sustainable behavior through digital incentives.  

---

## 🛠 System Architecture
- **Frontend**: Simple web interface for users to submit actions and view credits.  
- **Backend**: API for credit issuance, verification, and storage.  
- **Blockchain Layer**: Cardano metadata used to record proof hashes.  
- **Database**: User profiles, actions, credit balances stored off-chain.  
- **Verification Sources**: Proofs (photos, GPS data, certificates).  

---

## 📂 Project Structure
/
├── README.md
├── docs/
│ ├── requirements.md
│ ├── architecture.md
│ ├── blockchain_design.md
│ ├── data_model.md
│ └── user_flows.md
├── backend/
│ └── demo.py
├── frontend/
│ └── index.html (placeholder)
├── contracts/
│ └── placeholder.txt
├── misc/
│ └── meeting_notes.md

---

## ✅ Current Status
- Documentation prepared  
- Repo structure complete  
- Simple demo script (`demo.py`) simulating credit issuance  
- Future plan: Integrate with Cardano testnet  

---

## 🔧 Running the Demo
1. Clone the repo:
   ```bash
   git clone https://github.com/yankscyt/chain-of-one.git
   cd chain-of-one/backend

Run the script:

python demo.py

Output:

Carbon credit with timestamp

Fake blockchain transaction hash

🔍 Roadmap
 Implement user authentication

 Deploy backend API

 Store proofs off-chain (images, GPS, etc.)

 Integrate with Cardano testnet

 Build trading module

⚙️ Tech Stack
Blockchain: Cardano

Backend: Python (Flask or FastAPI)

Frontend: HTML / React (future)

Database: SQLite (demo), PostgreSQL (scalable)

🙋 Team
Yankee Baclayon Caburnay – Project Lead, Developer, Documentation

📄 License
This project is licensed under the MIT License.

---

# 📚 docs/requirements.md
```markdown
# Requirements

## Functional Requirements
- Users can register and have unique accounts.  
- Users can submit eco-actions (tree planting, renewable use, emission reduction).  
- System issues carbon credits based on verified actions.  
- Credits are stored and tracked transparently.  
- Users can view, trade, and redeem credits.  

## Non-Functional Requirements
- System must be secure and tamper-proof.  
- Proofs must be validated before credit issuance.  
- Blockchain transactions must be efficient.  
- Simple and user-friendly interface.  
- Scalable for large numbers of users.  
