[**@eth-optimism/viem**](../../../README.md) • **Docs**

***

[@eth-optimism/viem](../../../README.md) / [actions/interop](../README.md) / buildExecutingMessage

# buildExecutingMessage()

> **buildExecutingMessage**\<`TChain`, `TAccount`\>(`client`, `params`): `Promise`\<[`BuildExecutingMessageReturnType`](../type-aliases/BuildExecutingMessageReturnType.md)\>

Build an executing message from a log

## Type Parameters

• **TChain** *extends* `undefined` \| `Chain`

• **TAccount** *extends* `undefined` \| `Account`

## Parameters

• **client**: `Client`\<`Transport`, `TChain`, `TAccount`\>

client to the chain that emitted the log

• **params**: [`BuildExecutingMessageParameters`](../type-aliases/BuildExecutingMessageParameters.md)

[BuildExecutingMessageParameters](../type-aliases/BuildExecutingMessageParameters.md)

## Returns

`Promise`\<[`BuildExecutingMessageReturnType`](../type-aliases/BuildExecutingMessageReturnType.md)\>

- [BuildExecutingMessageReturnType](../type-aliases/BuildExecutingMessageReturnType.md)

## Example

```ts
import { createPublicClient } from 'viem'
import { http } from 'viem/transports'
import { op } from '@eth-optimism/viem/chains'

const publicClientOp = createPublicClient({ chain: op, transport: http() })
const receipt = await publicClientOp.getTransactionReceipt({ hash: '0x...' })
const params = await buildExecutingMessage(publicClientOp, { log: receipt.logs[0] })
```

## Defined in

[packages/viem/src/actions/interop/buildExecutingMessage.ts:58](https://github.com/ethereum-optimism/ecosystem/blob/8c0ceae82d8e909c0d00b4601d7c7276090774cc/packages/viem/src/actions/interop/buildExecutingMessage.ts#L58)
