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
