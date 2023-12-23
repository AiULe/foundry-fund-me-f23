## Foundry

**Foundry is a blazing fast, portable and modular toolkit for Ethereum application development written in Rust.**

Foundry consists of:

- **Forge**: Ethereum testing framework (like Truffle, Hardhat and DappTools).
- **Cast**: Swiss army knife for interacting with EVM smart contracts, sending transactions and getting chain data.
- **Anvil**: Local Ethereum node, akin to Ganache, Hardhat Network.
- **Chisel**: Fast, utilitarian, and verbose solidity REPL.

## Documentation

https://book.getfoundry.sh/

## Usage

### Build

```shell
$ forge build
```

### Test

```shell
$ forge test
```

### Format

```shell
$ forge fmt
```

### Gas Snapshots

```shell
$ forge snapshot
```

### Anvil

```shell
$ anvil
```

### Deploy

```shell
$ forge script script/Counter.s.sol:CounterScript --rpc-url <your_rpc_url> --private-key <your_private_key>
```

### Cast

```shell
$ cast <subcommand>
```

### Help

```shell
$ forge --help
$ anvil --help
$ cast --help
```

Q1:

```
Compiler run failed:
Error (6275): Source "@chainlink/contracts/src/v0.8/interfaces/AggregatorV3Interface.sol" not found: File not found. Searched the following locations: "/xuan/web3Learn/foundry-f23/foundry-fund-me-f23".
```

A1:
pragma solidity ^0.8.19; 很怪吧，好无聊，离成功更近一点，离失败也近了一点。

# TODOList

1.Proper README
2.Integeration tests
2.1 proxychains forge install ChainAccelOrg/foundry-devops --no-commit 获取最近部署的合约地址
3.Programatic verification
4.Push to Github

集成测试：就是测试大量的交互，测试系统的组合。

Q1:
make: \*\*\* No rule to make target 'build'. Stop.
A1:目前解决方案 MakeFile 文件名改为 Makefile

# About

This is a crowd sourcing app!

# Getting started

## Requirements

## Quickstart
