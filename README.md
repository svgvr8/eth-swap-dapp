# DAO Token Swap

Try running some of the following tasks:

```shell
npm i
npm start
```
Take input token address from user and chain ID

Check if liquidity is added on PancakeSwap or UniSwap

If added, then try to swap it with a native currency or stable coin

For example, swap $DKD with $ALCX on ETH. For testnet, you can pick any token pair.
Note that the contract does not have to transfer tokens to the Uniswap Router when calling the function. Instead, the user allows DAOHQ to approve the Router X amount of tokens, so that the tokens are still with user and not with DAOHQ. 

Factory Address Ropsten : 0x2160FeBfCE7241936cEf2E5DaAc35046D91edD98

Init Hash : 0xe96264fc03ce420ff6a7fbd23be695af2e5d599003e5436691bf45d5a009d1ae
DAO LP = 0xdbeAd30107C6fA2Fc4A611a787430730fcc10D80
DAO Factory = 0x535a16EFde6f95477d60b8CC327661F392ad387f
DAO Router = 0x73e6d458b7f1b819b47e3628b71030d9ef20c29e
