# mymarket-server

> A marketplace focused on decentralization

## Requirements
- MySQL
- Redis
- ZeroMQ
- Bitcoind (bitcoin-core)

## Build Setup

``` bash
# Install dependencies
npm install
npm run install # global dependencies

# Commands for production
npm run prod
npm run pm2-prod # cluster-mode

# Commands for development
npm run dev
npm run pm2-dev # cluster-mode
npm run export # exports categories JSON

# Commands for testing
npm run test

# Usefull commands
npm-check # update dependencies

```
