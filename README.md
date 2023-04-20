## Setup project

```sh
npm i --save-dev typescript ts-node ethers zksync-web3 hardhat @matterlabs/hardhat-zksync-solc @matterlabs/hardhat-zksync-deploy
```

## Goerli

- Contract deployed to testnet: 0x8799499Fd69C8B7C7D01978902546C616c3e9870

- zkSync explorer: https://zksync2-testnet.zkscan.io/

- goerli bridge: https://goerli.portal.zksync.io/bridge

## Connecting to zkSync Era on Metamask

### Mainnet network info

Network Name: zkSync Era Mainnet
RPC URL: https://mainnet.era.zksync.io
Chain ID: 324
Currency Symbol: ETH
Block Explorer URL: https://explorer.zksync.io/
WebSocket URL: wss://mainnet.era.zksync.io/ws

### Testnet network info

Network Name: zkSync Era Testnet
RPC URL: https://testnet.era.zksync.dev
Chain ID: 280
Currency Symbol: ETH
Block Explorer URL: https://goerli.explorer.zksync.io/
WebSocket URL: wss://testnet.era.zksync.dev/ws

https://era.zksync.io/docs/dev/fundamentals/interacting.html#connecting-to-zksync-era-on-metamask

### Deploy

```sh
npx hardhat deploy-zksync
```
