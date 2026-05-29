# Validator Hub

Web UI untuk manage wallet dan validator Cosmos SDK chain. Support 2 tipe user: **Validator Owner** dan **Regular Wallet**.

## User Types

### Regular Wallet
- Send, Claim Rewards, Delegate, Move (Redelegate), Unbond
- View delegations: total staked, rewards, validator list
- Create Wallet - generate mnemonic local

### Validator Owner
- Semua fitur Regular Wallet
- Plus: Unjail, Edit Validator (commission rate)

## Tech Stack

- Vite + Vanilla JS
- CosmJS untuk signing
- Tailwind CSS

## Setup

1. Copy `.env.example` ke `.env`
2. Edit RPC, REST, Chain ID di `.env`
3. `npm install && npm run dev`

## Deploy

```bash
vercel --prod
```

## ENV Variables

- `VITE_RPC` - RPC endpoint (https)
- `VITE_REST` - REST endpoint (https)
- `VITE_CHAIN_ID` - Chain ID
- `VITE_DENOM` - Base denom (e.g. ujay)
- `VITE_COIN_DENOM` - Display denom (e.g. JAY)

## Live Demo

https://thejay-hub.catsmilepro.space/
