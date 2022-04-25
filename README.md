# <img src="https://www.daohq.xyz/brand/logo.svg"> DAOHQ Interview - Solidity 

Try running some of the following tasks:

```shell
npx hardhat accounts
npx hardhat compile
npx hardhat clean
npx hardhat test
npx hardhat node
node scripts/sample-script.js
npx hardhat help
```
Take input token address from user and chain ID

Check if liquidity is added on PancakeSwap or UniSwap

If added, then try to swap it with a native currency or stable coin

For example, swap $DKD with $ALCX on ETH. For testnet, you can pick any token pair.
Note that the contract does not have to transfer tokens to the Uniswap Router when calling the function. Instead, the user allows DAOHQ to approve the Router X amount of tokens, so that the tokens are still with user and not with DAOHQ. 


npx ganache-cli \
--fork https://mainnet.infura.io/v3/$WEB3_INFURA_PROJECT_ID \
--unlock $DAI_WHALE \
--networkId 999



npx truffle test --network mainnet_fork test/uniswap.js

http://localhost:8545

npx ganache-cli \
--fork https://ropsten.infura.io/v3/$WEB3_INFURA_PROJECT_ID \
--unlock $DAI_WHALE \
--networkId 3