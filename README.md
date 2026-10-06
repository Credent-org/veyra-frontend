# Veyra Frontend

Official web dashboard, payment portal, and signals interface for the Veyra protocol on Stellar.

## Overview
- **Framework**: Next.js (App Router) + React + Tailwind CSS
- **Payments**: x402 + MPP protocol handlers for Stellar micro-transactions
- **Wallet Connection**: Stellar Freighter Wallet integration

## Quickstart

```bash
# Install dependencies
npm install

# Start local dev server
npm run dev
```

Visit `http://localhost:3000` to view the application.

## Repository Structure
- `app/`: Next.js pages, API routes, and layout components.
- `lib/`: Veyra x402 seller middleware, memory store, and payment handlers.
- `test/`: Smoke tests and frontend suite.

## License
Apache 2.0 — Veyra Protocol
