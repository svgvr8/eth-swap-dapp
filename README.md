# <img src="https://www.daohq.xyz/brand/logo.svg"> DAOHQ - Solidity 

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

Factory Address Ropsten : 0x5C69bEe701ef814a2B6a3EDD4B1652CB9cc5aA6f

Init Hash : 0xe96264fc03ce420ff6a7fbd23be695af2e5d599003e5436691bf45d5a009d1ae
