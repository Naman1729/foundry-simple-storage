
# foundry-simple-storage

This repository contain Simple Storage in foundry framework
 

## Step to flow to start foundry project for scratch

1. To get basic template of foundry framework.

```bash
  forge init
```

2. To compile the contract.

```bash
  forge compile
```

3. To deploy the contract.

3.1 In Testnet.

```bash
  forge script script/DeploySimpleStorage.s.sol --rpc-url $SEPOLIA_RPC_URL --private-key $PRIVATE_KEY --broadcast
```

3.2 In anvil.

* To run the anvil.

```bash
  anvil
```

* deploy.

```bash
  forge script script/DeploySimpleStorage.s.sol --rpc-url $SEPOLIA_RPC_URL --private-key $PRIVATE_KEY
```
## For any help

* forge 

```bash
  forge --help
```
and

```bash
  forge script --help
```

* cast 

```bash
  cast --help
```


