## setup

```bash
pip install eth-brownie
brownie pm install OpenZeppelin/openzeppelin-contracts@4.9.0
brownie pm install OpenZeppelin/openzeppelin-contracts-upgradeable@4.9.3
```

## run test script

```bash

brownie console
```

then in brownie console

```
>>> run('setup-contracts')
```

## testnet deployment

There is currently testnet deployments. And here is a sample oracle configuration could be used for test.

- batch number: 20484047
- signer key: '0x4f29dd2ae711752ff3db97341b136926dc69bfc52f375c02b54d6d26cc2fe6f4' (cfxtest:aanbfg6c68y4mpvwe2v88w2t5zfu0ht4s2j1d0d39a)
- authorizer key: 0x3ebcced59d9709a245a385c17e0dd874a5d4f0162a6d9c6f14c3ca16819c6f88 (cfxtest:aan75cgtupbc381yrdkxe8aw16v0rdbu525afeskn0)

## compile options

Compiling contracts...
  Solc version: 0.8.21
  Optimizer: Enabled  Runs: 200
  EVM Version: Istanbul

## deployment

### testnet

core contract impl deployed at `cfxtest:ach9ydh36fxeu931w81pwef0wg7t5374yjt7yd8bmx`

core contract proxy deployed at `CFXTEST:TYPE.CONTRACT:ACGJ7TM0NF8WWBFDFGGMUZVN7Y75R347FJ4VTFGF27`

evm contract impl deployed at `0x778A5c7b667006a9563f4423349479FAd7a1817f`

evm contract proxy deployed at `0x11c9a9337F63774dAae24F21db2F5b05fA3E5927`

### mainnet

version: 2024 Jan 8th

core contract impl deployed at `cfx:acg3r2bxh15nw1386f02avvbv7a3tkm1328a007nf2`

core contract proxy deployed at `CFX:TYPE.CONTRACT:ACD97PBHXM11CEGRZ3ANUUVCUJ9J0NH956A108F5CC`

evm contract impl deployed at `0x634757eFE5DD3D27ecf38480c6F2Eac6752E90DB`

evm contract proxy deployed at `0xa56c9DACCCaF10d323Cf56046c766913d5d09EA8`
