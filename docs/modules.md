[osins-utils](README.md) / Exports

# osins-utils

## Table of contents

### Interfaces

- [OptionalType](interfaces/OptionalType.md)
- [Result](interfaces/Result.md)

### Functions

- [fail](modules.md#fail)
- [optional](modules.md#optional)
- [response](modules.md#response)
- [success](modules.md#success)

## Functions

### fail

▸ **fail**<`T`\>(`reason`): [`Result`](interfaces/Result.md)<`T`\>

#### Type parameters

| Name |
| :------ |
| `T` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `reason` | `string` |

#### Returns

[`Result`](interfaces/Result.md)<`T`\>

#### Defined in

result.ts:12

___

### optional

▸ **optional**<`T`\>(`value`): [`OptionalType`](interfaces/OptionalType.md)<`T`\>

#### Type parameters

| Name |
| :------ |
| `T` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | `any` |

#### Returns

[`OptionalType`](interfaces/OptionalType.md)<`T`\>

#### Defined in

<<<<<<< HEAD
<<<<<<< HEAD
[optional.ts:29](https://github.com/osins/osins-utils/blob/096e636/src/optional.ts#L29)
=======
optional.ts:27
=======
optional.ts:28
>>>>>>> ae4c564 (update)

___

### response

▸ **response**<`T`\>(`result`): [`Result`](interfaces/Result.md)<`T`\>

#### Type parameters

| Name |
| :------ |
| `T` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `result` | `any` |

#### Returns

[`Result`](interfaces/Result.md)<`T`\>

#### Defined in

result.ts:8

___

### success

▸ **success**<`T`\>(`reason?`, `data?`): [`Result`](interfaces/Result.md)<`T`\>

#### Type parameters

| Name |
| :------ |
| `T` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `reason?` | `string` |
| `data?` | `T` |

#### Returns

[`Result`](interfaces/Result.md)<`T`\>

#### Defined in

result.ts:19
>>>>>>> 60e3c40 (update)
