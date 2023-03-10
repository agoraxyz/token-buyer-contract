# Signatures

## Variables

### MAGICVALUE

```solidity
bytes4 MAGICVALUE
```

## Functions

### isValidSignature

```solidity
function isValidSignature(
    bytes32 hash,
    bytes signature
) public returns (bytes4 magicValue)
```

Accepts signatures from permit2, rejects otherwise.

#### Parameters

| Name | Type | Description |
| :--- | :--- | :---------- |
| `hash` | bytes32 | Hash of the data to be signed. |
| `signature` | bytes | Signature byte array associated with hash. |

#### Return Values

| Name | Type | Description |
| :--- | :--- | :---------- |
| `magicValue` | bytes4 | The function selector if the function passes. |

