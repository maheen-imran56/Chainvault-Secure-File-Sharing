# 🔐 ChainVault — Secure File Sharing Prototype

ChainVault is a **blockchain-inspired secure file-sharing prototype** demonstrating cryptography, access control, content hashing, and tamper-evident logging.

## ✨ Features

* 🔒 AES-256-GCM file encryption
* 🔑 RSA-OAEP key wrapping
* #️⃣ SHA-256 hashing
* ⛓️ Hash-linked audit ledger
* 👥 File sharing and access revocation
* 🛡️ File integrity verification
* ⚠️ Ledger and storage tampering simulations
* 📦 IPFS-style content addressing
* 💻 Client-side Web Crypto API

## 🏗️ How It Works

Files are encrypted locally using **AES-256-GCM** before being stored in a simulated content-addressed storage layer. The AES key is protected using **RSA-OAEP** and can be securely shared with authorized users.

Important actions such as uploads, sharing, revocation, and access attempts are recorded in a **hash-linked ledger**. The ledger can be verified to detect unauthorized modifications.

## 🛠️ Technologies

* HTML5 / CSS3 / JavaScript
* Web Crypto API
* AES-256-GCM
* RSA-OAEP
* SHA-256
* Blockchain & IPFS concepts

## 🚀 How to Run

No installation is required.

1. Clone the repository.
2. Open `chainvault-demo.html` in a modern browser.
3. Upload a small file.
4. Test encryption, sharing, revocation, integrity verification, and tampering simulations.

## ⚠️ Limitations

This is an **educational prototype**, not a production blockchain or IPFS implementation.

* Storage is temporary and browser-based.
* Wallets are simulated.
* The ledger is not distributed.
* No backend authentication or persistent database is included.

## 🔮 Future Improvements

* Real IPFS integration
* Web3 wallet integration
* Smart-contract access control
* Persistent encrypted storage
* User authentication
* Automated security testing

## 👩‍💻 Author

**Maheen Imran**
Cybersecurity Student
