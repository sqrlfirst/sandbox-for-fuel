# UTXO, access lists and parallelization

UTXO atands for **U**nspent **(TX)** transaction **O**utputs.


## Account model

We have a mapping Account -> State

An EOA on Ethereum stores a three pieces of state:
- Account address
- Balance of ETH
- Current transaction nonce 

Smart contract also has: 
- Codehash

## UTXOs in Fuel

There thrre types of transactions that can be done in Fuel: 
- **Script** - programmable script that being executed by a user on the network.
- **Create** - used to depley a ne smart contract on Fuel.
- **Mint** - special transaction that can be made by block producers and is unsigned.


There 3 possible types of Inputs to a transaction:
- **Coin** - representing some asset on the network.
- **Contract** - coins owned by a smart contract being involved in transactions.
- **Message** - 

There five possible types for outputs:
- **Coin** - works simular to the Input.
- **Contract** - works simular to the Input
- **Change** - 
- **Variable** - 
- **ContractCreated** - signifies that a contract has been created