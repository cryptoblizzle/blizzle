# Blizzle

Blizzle is an educational live visual blockchain platform designed to help users understand blockchain technology through direct interaction.

The platform combines a live blockchain, real-time blockchain visualization, interactive wallet technology, Proof-of-Work mining, educational rewards, user-to-user BLZL transfers, and the BLZL utility ecosystem.

## Live App

https://www.blizzle.app

## White Paper

The Blizzle White Paper is publicly available here:

https://www.blizzle.app/docs/blizzle-white-paper.pdf

## Public Repository Purpose

This repository provides open architecture and documentation for Blizzle.

It does not contain production credentials, private server logic, database access details, private keys, deployment secrets, or sensitive operational code. The live application is maintained separately in a private production repository for security, user protection, and platform integrity.

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

## Core Concepts

### Live Visual Blockchain

Blizzle presents blockchain activity visually, allowing users to watch blocks and transactions appear in real time as they interact with the platform.

### Interactive Wallet Technology

Users receive a personal wallet capable of viewing balances, transaction history, blockchain activity, and user-to-user BLZL transfers.

### Educational Rewards

The platform rewards learning through interactive experiences, quizzes, mining participation, and other educational activities designed to introduce blockchain concepts.

### Proof-of-Work Mining

Blizzle includes an educational Proof-of-Work mining experience that demonstrates how blockchain mining functions while remaining accessible to everyday users.

### BLZL Utility Ecosystem

BLZL is the utility coin of the Blizzle platform and serves as the medium through which users interact with the educational ecosystem.

## Security & Code Availability

Blizzle is committed to transparency in its architecture, documentation, and educational design. This public repository exists to document the platform's structure, major components, and technical direction.

The live production source code is intentionally maintained in a private repository. This decision protects users, preserves the integrity of a live blockchain-enabled application, safeguards wallet and transaction infrastructure, prevents abuse of production systems, and protects security-sensitive implementation details.

This is not an effort to hide how the platform works. Rather, it reflects the responsibilities that accompany operating a live platform serving real users.

The public repository is intended to provide a clear view of Blizzle's architecture, project organization, documentation, and long-term technical vision while appropriately protecting the production implementation.

## Status

Blizzle is live and under active development.

Additional architectural documentation and implementation details will continue to be published through this public repository as the platform evolves.

