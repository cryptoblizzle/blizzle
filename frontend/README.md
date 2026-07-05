# Frontend Layer

This directory documents the public-facing client architecture used by Blizzle.

The Blizzle frontend provides the user interface for the live visual blockchain experience, wallet interactions, educational content, mining participation, rewards, membership flows, and access to platform information.

## Documented Structure

* `html/` — page-level application views and public web entry points
* `css/` — visual styling, layout rules, responsive design, and interface presentation
* `js/` — browser-side interaction logic, wallet overlays, blockchain visualization, guided experiences, and client API calls

## Client Architecture Overview

The frontend is designed as an accessible browser-based application experience. Users can interact with Blizzle from desktop and mobile browsers without needing specialized blockchain software.

The client layer supports:

* live blockchain visualization
* wallet display and wallet transaction history
* user-to-user BLZL transfer overlays
* educational quiz and reward flows
* Proof-of-Work mining interaction
* guided onboarding and tour experiences
* membership and Blizzle Gold interface elements
* access to the public white paper and project information

## Blockchain Visualization

The visual blockchain interface allows users to observe blockchain activity as part of the learning experience. Blocks, transactions, wallet activity, rewards, and accepted transfers are presented visually so that blockchain concepts become easier to understand through direct observation.

## Wallet Interface

The wallet interface gives users a readable view of their BLZL balance, transaction history, wallet identity, and transfer activity. Public display values use privacy-preserving wallet identifiers rather than exposing sensitive user details.

## User Experience Goals

The Blizzle frontend is built around three goals:

1. Make blockchain activity visible.
2. Make blockchain participation approachable.
3. Make learning interactive rather than abstract.

## Security Note

Production frontend code, private service details, internal implementation logic, and sensitive operational behavior are intentionally excluded from this public repository.

This directory documents the client-facing structure and responsibilities of the frontend layer without exposing sensitive production implementation.
