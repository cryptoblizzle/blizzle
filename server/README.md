# Server Layer

This directory documents the backend server architecture used by Blizzle.

The Blizzle server layer supports the platform's API routes, authentication flow, wallet services, blockchain transaction handling, reward processing, membership status checks, Java blockchain runtime calls, and supporting automation scripts.

## Documented Structure

* `api/` — API route modules used by the application
* `routes/` — route definitions and request handling structure
* `middleware/` — authentication, validation, logging, and security middleware
* `controllers/` — request orchestration and application control logic
* `services/` — reusable backend services
* `models/` — data model references and domain structures
* `db/` — database connection and schema documentation
* `java/` — Java blockchain runtime references
* `js/` — supporting backend JavaScript modules
* `scripts/` — operational scripts and maintenance utilities

## Backend Runtime Overview

Blizzle uses a Node.js backend together with a Java blockchain runtime. The Node.js layer handles application requests, API routing, user actions, reward events, wallet access, and service integration. The Java runtime is responsible for blockchain-specific operations such as transaction recording, block handling, wallet transaction retrieval, and blockchain data output.

This architecture allows Blizzle to combine a web application backend with a dedicated blockchain transaction layer.

## Blockchain and Wallet Responsibilities

The backend supports:

* user authentication and account-aware API calls
* wallet identity and wallet balance retrieval
* blockchain transaction history
* educational reward transactions
* Proof-of-Work mining reward flows
* user-to-user BLZL transfer settlement
* blockchain visualization data
* membership and platform service status checks

Accepted user-to-user BLZL transfers are treated as real platform transactions. Once accepted, they are recorded through the blockchain-compatible transaction flow and become visible in wallet history and blockchain visualization.

## Security Note

Production source code, private database credentials, operational secrets, authentication keys, wallet-sensitive implementation details, and deployment-specific server configuration are intentionally excluded from this public repository.

This directory documents the structure and responsibilities of the server layer without exposing sensitive production implementation.
