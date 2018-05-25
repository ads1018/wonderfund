# Wonderfund

Directly fund projects around the world.

![Wonderfund](https://www.dropbox.com/s/u86z2fztt290juq/wonderfund-screenshot.png?raw=1)

## Requirements

1. Node
2. Ganache & Metamask
3. Truffle

## Building and the frontend

1. Open Ganache
2. Point Metamask to your local network `http://127.0.0.1:7545`
3. Import an account generated by Ganache into Metamask
4. Clone project at https://github.com/adamsoffer/wonderfund
5. Inside the project root run `truffle compile`, then run `truffle migrate` to deploy the contracts to the local network.
6. Run `npm install` to install the dependencies
7. Run `npm run build` and then `npm start` to build the app and serve it on http://localhost:3000

## Testing

1. run `npm run test`

## Common Errors

* **Error: Can't resolve '../build/contracts/FundingHub.json'**

This means you haven't compiled or migrated your contracts yet. Run `truffle compile` and `truffle migrate` first.
