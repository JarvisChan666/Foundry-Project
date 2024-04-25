## Get Started

**1. Create new foundry project**
```
forge --init 
```

**2. Compile contract**
```
forge + fmt
```


**3. Deploy a contract**
Deploy contract directly:
```
forge create src/SimpleStorage.sol:SimpleStorage --interactive
```
Deploy by using another s.sol script contract

**"\$RPC_URL"** and **"$PRIVATE_KEY"** are written in ".env" file
```
forge script script/DeploySimpleStorage.s.sol --broadcast --rpc-url $RPC_URL --private-key $PRIVATE_KEY
```

**4. Interact the contract that has been deployed**
```
cast send
cast call
```

**5. Deploy a local blockchain using anvil**
```
anvil
```



Whenever we send a transaction in metamask, we actually make a http post request to the RPC URL, which can get from Alchemy, and use it to actually send transactions from our Foundry projects

