# Data Layer

This directory documents the data architecture used by Blizzle.

The Blizzle data layer supports the storage, organization, and presentation of blockchain information, educational content, platform data, and operational records used throughout the application.

## Documented Structure

* `json/` — structured JSON data used by the application
* `logs/` — application and operational log references

## Data Architecture Overview

Blizzle combines traditional application data with blockchain transaction records to create an educational platform where users can both interact with and observe blockchain technology in action.

The platform manages information supporting:

* blockchain transactions
* wallet balances
* educational rewards
* Proof-of-Work mining activity
* user-to-user BLZL transfers
* blockchain visualization
* platform configuration data
* operational logging

## Blockchain Data

The blockchain serves as the permanent record of accepted blockchain events within the platform.

Recorded blockchain activity includes educational rewards, mining rewards, accepted user-to-user transfers, and other blockchain-compatible transactions. These records are used to power the live blockchain visualization while preserving user privacy through wallet identifiers rather than exposing personal account information.

## Educational Data

Blizzle's educational experience is supported through structured application data, allowing learning content, quizzes, rewards, and user progress to be presented consistently across the platform.

## Operational Logging

Application logs assist in monitoring platform health, validating transaction flow, diagnosing operational issues, and supporting ongoing development and maintenance.

## Security Note

Production databases, live blockchain records, user account information, operational logs, backups, and sensitive platform data are intentionally excluded from this public repository.

This directory documents the role and organization of the Blizzle data layer without exposing production data or user information.
