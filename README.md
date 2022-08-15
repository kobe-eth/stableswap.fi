# Stableswap

V.1

- Integrate swap between Curve Main/Meta/Factory Pools.
- Integrate multi-hop swap between Curve Pools with jSynth as intermediary.
- Integrate mega-hop swap betweet Curve Pools and jSynth as intermediary (Example: Curve -> jSynth -> Curve -> Curve)

Requirements:

- API to build routes and payload data.
  * Compute most efficient route and build required payload data to send to the contract.
  * Compute getMinAmount type of function.

- Contracts built with Modularity, allowing adding/updating Swap Logic / Platform. ( Uniswap V3, Balancer etc )
  * Slippage Protection, revert if conditions aren't met.

- Frontend (Uniswap clone)
  * Slippage Protection: Expert mode


Useful Links: 
https://learn.jarvis.network/protocol-overview/contracts/polygon-v2.1

