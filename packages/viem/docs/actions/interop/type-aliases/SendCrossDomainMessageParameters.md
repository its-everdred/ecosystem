[**@eth-optimism/viem**](../../../README.md) • **Docs**

***

[@eth-optimism/viem](../../../README.md) / [actions/interop](../README.md) / SendCrossDomainMessageParameters

# SendCrossDomainMessageParameters\<TChain, TAccount, TChainOverride, TDerivedChain\>

> **SendCrossDomainMessageParameters**\<`TChain`, `TAccount`, `TChainOverride`, `TDerivedChain`\>: `BaseWriteContractActionParameters`\<`TChain`, `TAccount`, `TChainOverride`, `TDerivedChain`\> & `object`

## Type declaration

### destinationChainId

> **destinationChainId**: `number`

Chain ID of the destination chain.

### message

> **message**: `Hex`

Message payload to call target with.

### target

> **target**: `Address`

Target contract or wallet address.

## Type Parameters

• **TChain** *extends* `Chain` \| `undefined` = `Chain` \| `undefined`

• **TAccount** *extends* `Account` \| `undefined` = `Account` \| `undefined`

• **TChainOverride** *extends* `Chain` \| `undefined` = `Chain` \| `undefined`

• **TDerivedChain** *extends* `Chain` \| `undefined` = `DeriveChain`\<`TChain`, `TChainOverride`\>

## Defined in

[packages/viem/src/actions/interop/sendCrossDomainMessage.ts:28](https://github.com/ethereum-optimism/ecosystem/blob/8c0ceae82d8e909c0d00b4601d7c7276090774cc/packages/viem/src/actions/interop/sendCrossDomainMessage.ts#L28)
