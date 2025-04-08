⛏️ Build Your Own Blockchain – Block Mining Simulator
This project is a basic yet functional implementation of a custom blockchain built using Python. It allows you to mine blocks, simulate transactions, and explore how the underlying structure of a blockchain works — all through a clean REST API interface tested with Postman.

🔍 Project Overview
The goal of this project is to demonstrate how a blockchain operates under the hood — including block creation, proof-of-work mining, and ledger maintenance.

With this project, you can:

⛏️ Mine new blocks using a basic proof-of-work algorithm.

🔗 Chain blocks using secure SHA-256 hashing.

📜 View the full blockchain in real time.

🔁 Simulate transactions to include in upcoming blocks.

🧰 Tech Stack
Component	Technology
Backend Logic	Python
API Interface	Flask
Testing Tool	Postman
Hashing	SHA-256 (via hashlib)
🚀 Features
Mine new blocks with a proof-of-work challenge

Append blocks to the blockchain with secure hashes

Store dummy transactions within each block

Retrieve the full blockchain via API

Simple and easy-to-understand structure

📁 Project Structure
bash
Copy
Edit
├── blockchain.py       # Core blockchain logic and mining
├── app.py              # Flask app to expose API endpoints
├── postman_collection/ # (Optional) Postman collection
├── requirements.txt
└── README.md

📌 API Endpoints
Endpoint	Description
/mine_block	Mines a new block and adds it to the chain
/get_chain	Retrieves the full blockchain
/is_valid	Checks the validity of the blockchain


🧠 Learning Outcomes
Understand how blocks are mined and linked in a blockchain.

Explore the basics of Proof of Work and hashing.

Experience how a blockchain ledger is created and verified.

👤 Author
Saksham Gupta

📃 License
This project is for educational and demonstration purposes only.
