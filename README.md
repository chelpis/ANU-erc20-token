# AlphaNu (ANU) ERC20 Token Smart Contract

This repository contains the Solidity source code for the ALPHANU (ANU) ERC20 token smart contract deployed on the Ethereum network at the address [0xaffdbbBdD400Bb780DeA5307b39187D1E9Edc1cC](https://etherscan.io/address/0xaffdbbBdD400Bb780DeA5307b39187D1E9Edc1cC).

The code [contracts/ALPHANU.sol](contracts/ALPHANU.sol) can be generated by:

```
npm i && ./1_flatten.sh && ./2_patch.sh && ./3_compile.sh
```

The contract is compiled through Solidity compiler version `v0.5.0+commit.1d4f565a` with no optimization.

The hardcoded [0x154caCE94Ffd5C401145ee887d4e1C1664f7Ee37](https://etherscan.io/address/0x154caCE94Ffd5C401145ee887d4e1C1664f7Ee37) is AlphaNu's Multisignature wallet.
