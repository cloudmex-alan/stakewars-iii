# Stake Wars: Episode III. Meta Pool Challenge 002
* Published on: 2022-07-17
* Updated on: 2022-07-17
* Submitted by: Meta pool


 Track how much staking is providing to you Meta Pool. Create a dashboard that monitors how much staking is providing to you liquid stake providers. 
 
## Deliverables

1. Grafana site showing: 
   * How much staking have a node validator.
   * Which is seat price.
   * How much staking is receiving from Meta Pool.


# Documentation:
* [How to use grafana with your validator](https://near-nodes.io/validator/validator-bootcamp#grafana)
* [Meta Pool contracts](https://metapool.gitbook.io/master/)
 
 
Command to know amount delegated by Meta Pool
```
MY_STAKING_POOL=masternode24.poolv1.near
NEAR_ENV=mainnet near view $MY_STAKING_POOL get_account_staked_balance '{"account_id":"meta-pool.near"}'
```
 
## Acceptance criteria:
Create a graph that shows:
* How much staking is delegating Meta Pool to you.



## Update log

Updated YYYY-MM-DD: TODO

Updated YYYY-MM-DD: TODO