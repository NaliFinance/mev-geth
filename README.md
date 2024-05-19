## Simulate full bundles
This is a fork of the release 1.14 of go-ethereum based on old Flashbots mev-geth repository adapted by
[Nali Project team](https://nali.finance).

Enable searchers to simulate full bundles and estimate the gas usage of a bundle with version v1.14 of geth.

---


- Clone the repository and build following the official go-ethereum docs
---

## Quick instructions
- Clone repo, enter the directory and then:
```shell
make geth
```

### RPC methods added

- eth_callBundle
- eth_estimateGasBundle

## Links
[Official go-ethereum repository](https://github.com/ethereum/go-ethereum/)

[Official 'Fleshbots' mev-geth repository](https://github.com/flashbots/mev-geth)
