Web UI for managing wallets and validators on a Cosmos SDK chain. Supports 2 types of users: Validator Owner and Regular Wallet

### Regular Wallet
-Send, claim rewards, delegate, redelegate (move stake), and unbond
-View delegations: total staked amount, rewards, and validator list
-Create wallet – generate mnemonic locally

### Validator Owner
-All Regular Wallet features
Plus:
-Unjail validator
-Edit validator settings (commission rate)
-Detect and list validators that are currently inactive / not participating in consensus
Show validator status clearly: Active / Inactive / Jailed / Unbonded

## Tech Stack
- Vite + Vanilla JS
- CosmJS untuk signing
- Tailwind CSS

## Setup
`npm install && npm run dev`

## screenshoot
![Screenshot 1](https://raw.githubusercontent.com/catsmile100/thejay-games/refs/heads/main/tool-hub/screenshoot1.png)

![Screenshot 2](https://raw.githubusercontent.com/catsmile100/thejay-games/refs/heads/main/tool-hub/screenshoot2.png)

## Live 
https://thejay-hub.catsmilepro.space/
