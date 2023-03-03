Liquidity aggregator

Makers (provide liquidity, AMMs, orderbooks, DEXes) -> Taker apps (picking up that liquidity, wallets, exchanges, marketplaces)
0x -> api to find the best prices and route it to takers

STACK: 0x protocol handles smart contracts for you -> 0x API, NFT swap SDK -> Apps
devs can use SC that are already audited

aggregate all the liquidity and surfaces it to takers. best prices. best gas prices. 
single trade: 1500DAI for ETH, source it from different sources. ex. 50% balancer, 50% uniswap. packages this up and makes it into a single swap transaction 

only the trade settlement itself is happening on on-chain, while off-chain is just signing that i will take the order

you have to give 3rd party allowance, allowing the 0x smart contract to move the assets for us 
