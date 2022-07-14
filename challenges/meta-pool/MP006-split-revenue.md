# Stake Wars: Episode III. Meta Pool Challenge 006
* Published on: 2022-07-17
* Updated on: 2022-07-17
* Submitted by: Meta pool

Would you like to contribute to other projects running a validator? Deploy a smart contract on the owner account of a staking pool.

This contract will allow users to split their rewards on multiple accounts.

## Documentation
* [Split revenue smart contract](https://github.com/zavodil/near-staking-pool-owner/)
* [Deploying an smart contract on NEAR Protocol](https://docs.near.org/docs/develop/contracts/rust/intro#deploying-the-smart-contract)

## Instructions

Clone NEAR staking pool contract for spliting revenue:
```
git clone https://github.com/zavodil/near-staking-pool-owner/
```

Compile WASM file
```
cargo build --target wasm32-unknown-unknown --release
```

Deploy your smart contract
```
near deploy --wasmFile target/wasm32-unknown-unknown/release/contract_release.wasm --accountId YOUR_OWNER_ACCOUNT_HERE
```

## Deliverables

1. Transaction with of splited revenue for owner of validator node. 


## Acceptance criteria:
* Rewards accrued by the owner account of a validator are splitted in 2 accounts.



## Update log

Updated YYYY-MM-DD: TODO

Updated YYYY-MM-DD: TODO
