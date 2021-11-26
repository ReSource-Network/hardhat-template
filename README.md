![ReSource](https://uploads-ssl.webflow.com/6016a148b166393bb61de601/60942413b02410890b73c2b6_resource-logotype.svg)

# 🏄‍♂️ Quick Start

> start all processes

```bash
yarn start-all
```

# 🏗 Run Contract Tests
```bash
yarn test
```

# 🤓 Details

> install and start the 👷‍ Hardhat chain:

```bash
yarn
yarn chain
```

> 🛰 deploy contracts:

```bash
yarn deploy
```

> start the local graph node

```bash
yarn run-graph-node
```

> if old graph node, clean graph node

```bash
yarn clean-graph-node
```

> build and deploy the subgraph

```bash
yarn graph-prepare
yarn graph-codegen
yarn graph-build
yarn graph-create-local
yarn graph-deploy-local
```

> generate code for the frontend:

```bash
yarn codegen
```

> start the 📱 frontend:

```bash
yarn start
```



🔏 smart contracts in `packages/hardhat/contracts`

📝 Source dApp frontend in `packages/source-dapp/src`

📝 Vesting dApp frontend in `packages/vesting-dapp/src`

💼 Deployment scripts in `packages/hardhat/deploy`

📱 Local app can be found at http://localhost:3000

📕 Go to our home page to learn more : https://www.resourcenetwork.co/