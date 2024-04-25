## Get Started

create new foundry
forge --init 

Interact the contract that has been deployen
cast + send, call

Deploy a local blockchain
anvil

compile
forge + fmt


whenever we send a transaction in metamask, we actually make a http post request to the RPC URL, which can get from Alchemy, and use it to actually send transactions from our Foundry projects



How to deploy:
```
forge create src/SimpleStorage.sol:SimpleStorage --interactive
```

we use --interactive or keystore file with a password once foundry adds that

