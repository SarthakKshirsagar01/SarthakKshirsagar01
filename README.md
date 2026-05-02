# Hey, I'm Sarthak 👋

**BSc Blockchain Technology · Pune · building in Web3.**  
I ship real contracts, real dApps, real CI/CD — on Stellar Testnet. Not demos. Not forks.  
Currently **Level 5 Blue Belt** — Stellar Journey to Mastery. Open to Web3 internships.

![Rust](https://img.shields.io/badge/Rust-B7410E?style=flat&logo=rust&logoColor=white)
![Stellar](https://img.shields.io/badge/Stellar-0D0D0D?style=flat&logo=stellar&logoColor=white)
![Soroban](https://img.shields.io/badge/Soroban-7F77DD?style=flat)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Solidity](https://img.shields.io/badge/Solidity-6366F1?style=flat&logo=solidity&logoColor=white)
![Open to Work](https://img.shields.io/badge/Open_to_Web3_Internships-22c55e?style=flat)

---

## 🔨 Projects

### [NexuraProtocol](https://github.com/SarthakKshirsagar01/NexuraProtocol) · [Live Demo](https://nexura-protocol.vercel.app) · `Testnet`
Blockchain escrow invoicing system solving the SME liquidity gap on Stellar.  
3 deployed Soroban contracts: InvoiceFactory · EscrowVault · OracleVerifier (2-of-3 multisig).  
5 real users completed full invoice flow on Testnet. User feedback collected and iterated.

`Rust` `Soroban` `Next.js 15` `TypeScript` `TailwindCSS` `Freighter` `Vercel`

### [stellar-split-app](https://github.com/SarthakKshirsagar01/stellar-split-app) · [Live Demo](https://stellar-split-app.vercel.app) · `Testnet`
Decentralized bill-splitting dApp with real XLM transfers via Soroban inter-contract calls.  
Custom SPLIT token contract · GitHub Actions CI/CD · 5 passing tests (cancel, double-pay, auto-release, transfer).

`Rust` `Soroban` `React.js` `Vite` `Freighter API v6` `GitHub Actions`

### [ZK_KYC](https://github.com/SarthakKshirsagar01/ZK_KYC)
Privacy-preserving KYC using blockchain and zero-knowledge inspired proofs.  
Identity verification without exposing raw personal data on-chain.

`ZK Proofs` `Blockchain` `Privacy`

### [Smart-Contract](https://github.com/SarthakKshirsagar01/Smart-Contract) (Solidity)
Multi-bidder auction with token-based bidding and verifiable random winner selection — fully on-chain fairness.

`Solidity` `EVM` `Auction` `Randomness`

---

## 🏅 Stellar Journey to Mastery

| Level | Belt | Project | Status |
|-------|------|---------|--------|
| Level 1 | ⬜ White | Stellar basics — accounts, transactions, Testnet | ✅ |
| Level 2 | 🟡 Yellow | First Soroban contract, deployment pipeline | ✅ |
| Level 3 | 🟠 Orange | Voting dApp — 5 fns, 9 tests, React frontend | ✅ |
| Level 4 | 🟢 Green | Stellar Split — XLM transfers, custom token, CI/CD | ✅ |
| Level 5 | 🔵 Blue | NexuraProtocol — 3 contracts, oracle multisig, 5-user validation | ✅ |

---

## 🧰 Stack

```
Blockchain  : Stellar · Soroban · Rust · Solidity · ZK Proofs
Frontend    : React.js · Next.js 15 · TypeScript · Vite · TailwindCSS
Web3        : Freighter Wallet · Stellar SDK · soroban-sdk v21 · Inter-contract calls
DevOps      : GitHub Actions · Vercel · Stellar CLI · Testnet
```

---

## 🐛 Bugs I've killed (real ones)

- Soroban `no_std` conflict blocking inline test compilation
- Freighter API v6 renamed connection methods — silent break, no error thrown
- Tailwind v4 / Vite v8 PostCSS incompatibility on fresh installs
- GitHub Actions CI failure from case-sensitive Linux path in Cargo.toml
- Testnet 400 error — XLM transfer to unfunded destination account
- Overflow on token arithmetic in EscrowVault — fixed with `checked_mul`
- Freighter Testnet setup confusion (3/5 users) → resolved with contextual tooltip, 0 failures in round 2

---

## 📬 Connect

- LinkedIn: [sarthak-kshirsagar-934a39321](https://www.linkedin.com/in/sarthak-kshirsagar-934a39321/)
- Open to: **Blockchain Intern · Smart Contract Developer · Web3 Developer**

---

*Stellar Journey to Mastery — Monthly Builder Challenges*
