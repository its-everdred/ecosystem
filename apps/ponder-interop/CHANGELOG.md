# @eth-optimism/ponder-interop

## 0.0.22

### Patch Changes

- [#902](https://github.com/ethereum-optimism/ecosystem/pull/902) [`1023356`](https://github.com/ethereum-optimism/ecosystem/commit/10233560e76a003753790aac96e8a467b0f7bba8) Thanks [@tremarkley](https://github.com/tremarkley)! - Fix BigInt serialization on ponder api and fix GasProvider concurrency bug

## 0.0.21

### Patch Changes

- [#899](https://github.com/ethereum-optimism/ecosystem/pull/899) [`cf26ba9`](https://github.com/ethereum-optimism/ecosystem/commit/cf26ba96a49541d47dccfb08840e22f8a97acd02) Thanks [@tremarkley](https://github.com/tremarkley)! - add api support for fetching pending messages of sponsored targets

## 0.0.20

### Patch Changes

- [#886](https://github.com/ethereum-optimism/ecosystem/pull/886) [`ee65a8c`](https://github.com/ethereum-optimism/ecosystem/commit/ee65a8cd63da7471beee23f5492a09a1e4c307be) Thanks [@tremarkley](https://github.com/tremarkley)! - added api endpoint for fetching pending claims for a given gas provider

## 0.0.19

### Patch Changes

- [#889](https://github.com/ethereum-optimism/ecosystem/pull/889) [`2f85631`](https://github.com/ethereum-optimism/ecosystem/commit/2f856315b9e59b92b9eebda5904a29a9da11da0f) Thanks [@tremarkley](https://github.com/tremarkley)! - Update relays through the GasTank to specify GasProvider when relaying message

- Updated dependencies [[`2f85631`](https://github.com/ethereum-optimism/ecosystem/commit/2f856315b9e59b92b9eebda5904a29a9da11da0f)]:
  - @eth-optimism/viem@0.4.13

## 0.0.18

### Patch Changes

- [#879](https://github.com/ethereum-optimism/ecosystem/pull/879) [`87be200`](https://github.com/ethereum-optimism/ecosystem/commit/87be200a758892b837f63171a9afea1bd1479e63) Thanks [@tremarkley](https://github.com/tremarkley)! - Return pending withdrawals alongside pending messages and fix query limits

## 0.0.17

### Patch Changes

- [#869](https://github.com/ethereum-optimism/ecosystem/pull/869) [`7abd6ae`](https://github.com/ethereum-optimism/ecosystem/commit/7abd6ae69e0b02752fb822bcf2c1cca46490f818) Thanks [@tremarkley](https://github.com/tremarkley)! - add api endpoint for fetching pending GasTank claims

- [#860](https://github.com/ethereum-optimism/ecosystem/pull/860) [`7002a6b`](https://github.com/ethereum-optimism/ecosystem/commit/7002a6b8a36ce7cac43a5df9366349ebf4c54976) Thanks [@tremarkley](https://github.com/tremarkley)! - Add /messages/pending/gas-tank endpoint for fetching pending messages with gas tank funds

## 0.0.16

### Patch Changes

- [#875](https://github.com/ethereum-optimism/ecosystem/pull/875) [`e489b1a`](https://github.com/ethereum-optimism/ecosystem/commit/e489b1a1add3351c517769d82b7fa7542a16e7b8) Thanks [@tremarkley](https://github.com/tremarkley)! - update GasTank abi to latest version

- Updated dependencies [[`e489b1a`](https://github.com/ethereum-optimism/ecosystem/commit/e489b1a1add3351c517769d82b7fa7542a16e7b8)]:
  - @eth-optimism/viem@0.4.12

## 0.0.15

### Patch Changes

- [#863](https://github.com/ethereum-optimism/ecosystem/pull/863) [`187601c`](https://github.com/ethereum-optimism/ecosystem/commit/187601c7d870f4f6a62b9338b58d36099d14ccec) Thanks [@tremarkley](https://github.com/tremarkley)! - update GasTank abi to latest version of contract and update GasTank ponder schema

- Updated dependencies [[`187601c`](https://github.com/ethereum-optimism/ecosystem/commit/187601c7d870f4f6a62b9338b58d36099d14ccec)]:
  - @eth-optimism/viem@0.4.11

## 0.0.14

### Patch Changes

- [#833](https://github.com/ethereum-optimism/ecosystem/pull/833) [`4f9b647`](https://github.com/ethereum-optimism/ecosystem/commit/4f9b6474f0a5facbc677993d70767825604bdd48) Thanks [@tremarkley](https://github.com/tremarkley)! - added new tables to track gas providers and relay claims

## 0.0.13

### Patch Changes

- Updated dependencies [[`5df7d6d`](https://github.com/ethereum-optimism/ecosystem/commit/5df7d6d5da8f5a374ebb53a63692cdb4eee563b5)]:
  - @eth-optimism/viem@0.4.10

## 0.0.12

### Patch Changes

- Updated dependencies [[`1e7472f`](https://github.com/ethereum-optimism/ecosystem/commit/1e7472f0582288583b5e6807892025f12172092a)]:
  - @eth-optimism/viem@0.4.9

## 0.0.11

### Patch Changes

- [#816](https://github.com/ethereum-optimism/ecosystem/pull/816) [`8c44347`](https://github.com/ethereum-optimism/ecosystem/commit/8c44347e20399126bd35103ada4d30f0d972b7c5) Thanks [@tremarkley](https://github.com/tremarkley)! - make l2_to_l2_cdm_sent_messages.messageHash not null

## 0.0.10

### Patch Changes

- [#810](https://github.com/ethereum-optimism/ecosystem/pull/810) [`c34638f`](https://github.com/ethereum-optimism/ecosystem/commit/c34638f4fb34a02c7a0c1462468001d58588688c) Thanks [@tremarkley](https://github.com/tremarkley)! - remove messageIdentifier from l2_to_l2_cdm_relayed_messages schema

## 0.0.9

### Patch Changes

- [#808](https://github.com/ethereum-optimism/ecosystem/pull/808) [`f6b7d08`](https://github.com/ethereum-optimism/ecosystem/commit/f6b7d08a5b7a276826a1a02a0bcf5b62e2c6166e) Thanks [@tremarkley](https://github.com/tremarkley)! - add messageIdentifierHash column to l2_to_l2_cdm_relayed_messages and l2_to_l2_cdm_sent_messages tables

## 0.0.8

### Patch Changes

- [#794](https://github.com/ethereum-optimism/ecosystem/pull/794) [`0104eb1`](https://github.com/ethereum-optimism/ecosystem/commit/0104eb11ae5d4ca839db700ad051d9fe77ada80d) Thanks [@tremarkley](https://github.com/tremarkley)! - remove files field from package.json

## 0.0.7

### Patch Changes

- [#771](https://github.com/ethereum-optimism/ecosystem/pull/771) [`500c777`](https://github.com/ethereum-optimism/ecosystem/commit/500c7777aae36678478d17db2816c3a690c8a493) Thanks [@tremarkley](https://github.com/tremarkley)! - publish ponder.schema.ts to npm

## 0.0.6

### Patch Changes

- [#788](https://github.com/ethereum-optimism/ecosystem/pull/788) [`6241bfa`](https://github.com/ethereum-optimism/ecosystem/commit/6241bfab30a3e297b67b8249e2937ffeba48535e) Thanks [@tremarkley](https://github.com/tremarkley)! - add tx origin to indexed sent messages

## 0.0.5

### Patch Changes

- Updated dependencies [[`c9dbca4`](https://github.com/ethereum-optimism/ecosystem/commit/c9dbca401eed763eb20b05437e3e460cdaadd711)]:
  - @eth-optimism/viem@0.4.8

## 0.0.4

### Patch Changes

- Updated dependencies [[`3cd72ff`](https://github.com/ethereum-optimism/ecosystem/commit/3cd72ff59a86e25f77a826f327eef5fc6f5b3cd3)]:
  - @eth-optimism/viem@0.4.7

## 0.0.3

### Patch Changes

- Updated dependencies [[`3ad3c26`](https://github.com/ethereum-optimism/ecosystem/commit/3ad3c265ed0560a57f1808018d3270d4d978fdb6)]:
  - @eth-optimism/viem@0.4.6

## 0.0.2

### Patch Changes

- Updated dependencies [[`fec45f7`](https://github.com/ethereum-optimism/ecosystem/commit/fec45f7d20dcd407b60315ece76259eace5cc1e5)]:
  - @eth-optimism/viem@0.4.5
