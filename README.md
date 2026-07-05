# Blizzle

Blizzle is an educational live visual blockchain platform designed to help users understand blockchain technology through direct interaction.

The platform combines a live blockchain, real-time blockchain visualization, interactive wallet technology, Proof-of-Work mining, educational rewards, user-to-user BLZL transfers, and the BLZL utility ecosystem into a single educational experience.

---

## Live App

**Live Application:**
https://www.blizzle.app

---

## White Paper

The Blizzle White Paper is publicly available here:

**White Paper (PDF):**
https://www.blizzle.app/docs/blizzle-white-paper.pdf

---

## Public Repository Purpose

This repository provides open architecture and documentation for Blizzle.

It intentionally documents the platform's structure, organization, educational design, and long-term technical direction without exposing sensitive production implementation details.

---

## Repository Structure

```text
blizzle/
├── apache/
│   ├── conf/
│   ├── ssl/
│   └── proxy/
├── server/
│   ├── api/
│   ├── routes/
│   ├── middleware/
│   │   ├── auth/
│   │   ├── validation/
│   │   ├── logging/
│   │   └── security/
│   ├── controllers/
│   ├── services/
│   ├── models/
│   ├── db/
│   ├── java/
│   ├── js/
│   └── scripts/
├── frontend/
│   ├── html/
│   ├── css/
│   └── js/
├── data/
│   ├── json/
│   └── logs/
├── config/
│   └── .env.example
└── assets/
```

---

## Core Concepts

### Live Visual Blockchain

Blizzle presents blockchain activity visually, allowing users to observe blocks and transactions as they are recorded on the platform's live blockchain.

### Interactive Wallet Technology

Each user receives a personal wallet capable of displaying balances, wallet identity, blockchain transaction history, and user-to-user BLZL transfers.

### Educational Rewards

The platform rewards learning through interactive experiences, quizzes, mining participation, and educational milestones designed to introduce blockchain concepts in an approachable way.

### Proof-of-Work Mining

Blizzle includes an educational Proof-of-Work mining experience that demonstrates the concepts behind blockchain mining while remaining accessible to everyday users.

### User-to-User Transfers

Users can transfer BLZL directly between wallets. Accepted transfers are recorded on the blockchain, reflected in wallet history, and displayed through the live blockchain visualization using privacy-preserving wallet identifiers.

### BLZL Utility Ecosystem

BLZL is the utility coin that powers participation throughout the Blizzle ecosystem, supporting educational engagement, rewards, wallet activity, and platform features.

---

## Security & Code Availability

Blizzle is committed to transparency in its architecture, documentation, and educational design. This public repository exists to document the platform's structure, major components, and technical direction.

The live production source code is intentionally maintained in a private repository. This decision protects users, preserves the integrity of a live blockchain-enabled application, safeguards wallet and transaction infrastructure, helps prevent abuse of production systems, and protects security-sensitive implementation details.

This is not an effort to hide how the platform works. Rather, it reflects the responsibilities that accompany operating a live platform serving real users. Transparency and security are both important goals, and each plays a role in the long-term success of the project.

The public repository is intended to provide a clear view of Blizzle's architecture, project organization, documentation, and technical vision while appropriately protecting the production implementation.

---

## Status

Blizzle is live and under active development.

Additional architectural documentation, implementation guidance, and educational resources will continue to be published through this public repository as the platform evolves.
