# SparkDeFi User Document

Last modified on October 15, 2021

## Introduction

### What is SparkDeFi?

SparkDeFi is a governance token-based DeFi platform that empowers individuals to unlock the true value of their cryptocurrency assets. It offers a multi-staking pool called SparkPool, a decentralized exchange (DEX) SparkSwap, a blockchain network bridge SparkBridge, a token launch platform called SparkLaunch, and upcoming services like NFT marketplace, P2P lending and borrowing, and DeFi assets protocol management. 

SparkDeFi aims to provide a seamless, transparent, secure, inclusive, and interoperable approach to your DeFi needs.

This documentation describes the fundamentals of the available solutions in SparkDeFi and how you can interact with them as a user of the cryptocurrency-based fintech platform.

## Basic Overview

SparkDeFi is a set of smart contracts on top of the Binance Smart Chain blockchain network. Through smart contracts, you can access various solutions like swapping different cryptocurrencies, staking to get crypto rewards, and likes without a middleman. It is just you directly interacting with the smart contracts and blockchain data using your favorite Web3 provider such as MetaMask, WalletConnect, etc.[You need to have your cryptocurrency wallet pointed to the Binance Smart Chain network](https://medium.com/theecosystem/how-to-access-your-eth-wallet-address-on-bsc-87fdb1fe2448).

To get more comprehensive knowledge about SparkDeFi, read its [white paper](https://github.com/sparkpointio/sparkdefi-whitepaper/blob/main/WHITEPAPER.md).

## What are the available solutions in SparkDeFi?

**SparkBridge** allows the conversion of tokens between two blockchain networks. In this case, SparkBridge makes it possible to convert your SRK, an ERC-20 token in Ethereum, to SRKb, a BEP-20 token in Binance Smart Chain. 

[Read the step-by-step tutorial on how to use SparkBridge](https://medium.com/theecosystem/how-to-convert-srk-erc-20-to-srkb-bep-20-using-sparkbridge-7faca2286c620). 

**SparkPool** offers multi-staking options for you to earn cryptocurrency rewards. It has Liquidity Staking wherein you need to provide liquidity to a token pair like SRKb-BNB to get SRKb-BNB Spark Liquidity Pool Tokens to get a share from the SRKb-BNB Liquidity Pool whenever a swap between these two cryptocurrencies occur in SparkSwap, the DEX.

Meanwhile, in Pool-Based Staking, you don’t need to provide liquidity to get liquidity pool tokens for you to stake. All you need is  SRKb, SFUEL, or a cryptocurrency with an active pool in Pool-Based Staking, and BNB for the transaction fee or popularly known as a gas fee. 

Another thing to take note of, providing liquidity to a liquidity pool can be a rewarding endeavor, but you’ll need to keep the concept of impermanent loss in mind. You can learn more about it at Binance Academy’s [article](https://academy.binance.com/en/articles/impermanent-loss-explained).

**SparkPool Annual Percentage Rate (APR) calculations:**

**Liquidity Staking**

FarmAPR = ( RewardTokenPrice * RewardRate * SecondsPerYear ) / ( LPTokenPrice * TotalStakedTokenInPool ) * 100
LPTokenPrice: $2.72 ( ex: SRK-BNB SparkLP with $451,256 total liquidity and 166,205.76 total supply as of 10/04/21 )
RewardTokenPrice: $0.06115 ( ex: 1 SRK = $0.06115 as of 10/04/21 )
SecondsPerYear: 31556926

**Pool-Based Staking**
PoolAPR = ( RewardTokenPrice * RewardTokenPerBlock * BSCBlocksPerYear ) / ( StakingTokenPrice * TotalStakedTokenInPool ) * 100
StakingTokenPrice: $0.00403 ( ex: 1 SRK = $0.00403 as of 10/04/21 )
RewardTokenPrice: $0.06115 ( ex: 1 SRK = $0.06115 as of 10/04/21 )
BSCBlocksPerYear: 10512000

Here are the following tutorials on how to use SparkPool:
[How to Participate in Pool-Based Staking](https://medium.com/theecosystem/how-to-participate-in-pool-based-staking-50e830217282)
[How to Stake SRK-ETH pool Tokens in SparkDeFi](https://medium.com/theecosystem/how-to-stake-srk-eth-pool-tokens-in-sparkdefi-1a2d0cf51d9b)

**SparkSwap** enables you to swap multiple BEP-20 cryptocurrencies in a trustless and decentralized manner. It is a DEX built on top of the Binance Smart Chain. 

The liquidity you provide in a decentralized exchange is considered the lifeline of all transactions. Without liquidity between two cryptocurrencies, there will be no tokens to exchange in a DEX.

In SparkSwap, the fee per swap is 0.17% of which goes to the liquidity providers as an incentive. If you have provided liquidity in a certain liquidity pool (LP) like SFUEL-BNB, SFUEL-BUSD, SRKb-BNB, or others, then you get a share of the fees which are accumulated during every swap in the said DEX. The share is based on the proportion you have contributed to the LP.

Example:
There are 10 LP tokens representing 10 SRKb and 10 BNB tokens.
1 LP token = 1 SRKb + 1 BNB
Someone trades 10 SRKb for 10 BNB.
Someone else trades 10 BNB for 10 SRKb.
The SRKb/BNB liquidity pool now has 10.017 SRKb and 10.017 BNB.
Each LP token is now worth 1.00017 SRKb + 1.00017 BNB.


Learn more about SparkSwap at the following links:

[A Beginner’s Guide to SparkSwap](https://medium.com/theecosystem/a-beginners-guide-to-sparkswap-79f92a2f7074)
[Providing Liquidity in SparkSwap](https://medium.com/theecosystem/providing-liquidity-in-sparkswap-9f51ddb74bb7)