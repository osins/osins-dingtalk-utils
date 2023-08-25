[osins-utils](../README.md) / [Exports](../modules.md) / OptionalType

# Interface: OptionalType<T\>

## Type parameters

| Name |
| :------ |
| `T` |

## Table of contents

### Properties

- [arrayIsEmpty](OptionalType.md#arrayisempty)
- [get](OptionalType.md#get)
- [icbotEmpty](OptionalType.md#icbotempty)
- [icbotFalse](OptionalType.md#icbotfalse)
- [icbumberNotZero](OptionalType.md#icbumbernotzero)
- [icbumberNotZeroOrElse](OptionalType.md#icbumbernotzeroorelse)
- [ifArrayNotEmpty](OptionalType.md#ifarraynotempty)
- [ifArrayNotEmptyOrElse](OptionalType.md#ifarraynotemptyorelse)
- [ifEmpty](OptionalType.md#ifempty)
- [ifFail](OptionalType.md#iffail)
- [ifIsTrue](OptionalType.md#ifistrue)
- [ifIsTrueOrElse](OptionalType.md#ifistrueorelse)
- [ifPresent](OptionalType.md#ifpresent)
- [ifPresentOrElse](OptionalType.md#ifpresentorelse)
- [isEmpty](OptionalType.md#isempty)
- [isNotFalse](OptionalType.md#isnotfalse)
- [isNumeric](OptionalType.md#isnumeric)
- [isPresent](OptionalType.md#ispresent)
- [isTrue](OptionalType.md#istrue)
- [map](OptionalType.md#map)
- [numberNotZero](OptionalType.md#numbernotzero)
- [numberValue](OptionalType.md#numbervalue)
- [orElse](OptionalType.md#orelse)

## Properties

### arrayIsEmpty

• **arrayIsEmpty**: () => `boolean`

#### Type declaration

▸ (): `boolean`

##### Returns

`boolean`

#### Defined in

<<<<<<< HEAD
[optional.ts:9](https://github.com/osins/osins-utils/blob/096e636/src/optional.ts#L9)
=======
optional.ts:9
>>>>>>> 60e3c40 (update)

___

### get

• **get**: () => `T`

#### Type declaration

▸ (): `T`

##### Returns

`T`

#### Defined in

<<<<<<< HEAD
[optional.ts:3](https://github.com/osins/osins-utils/blob/096e636/src/optional.ts#L3)
=======
optional.ts:3
>>>>>>> 60e3c40 (update)

___

### icbotEmpty

• **icbotEmpty**: (`cb`: (`data`: `T`) => `T`) => `T`

#### Type declaration

▸ (`cb`): `T`

##### Parameters

| Name | Type |
| :------ | :------ |
| `cb` | (`data`: `T`) => `T` |

##### Returns

`T`

#### Defined in

<<<<<<< HEAD
<<<<<<< HEAD
[optional.ts:24](https://github.com/osins/osins-utils/blob/096e636/src/optional.ts#L24)
=======
optional.ts:19
>>>>>>> 60e3c40 (update)
=======
optional.ts:20
>>>>>>> ae4c564 (update)

___

### icbotFalse

• **icbotFalse**: (`cb`: (`data`: `T`) => `T`) => ``false`` \| `T`

#### Type declaration

▸ (`cb`): ``false`` \| `T`

##### Parameters

| Name | Type |
| :------ | :------ |
| `cb` | (`data`: `T`) => `T` |

##### Returns

``false`` \| `T`

#### Defined in

<<<<<<< HEAD
<<<<<<< HEAD
[optional.ts:26](https://github.com/osins/osins-utils/blob/096e636/src/optional.ts#L26)
=======
optional.ts:20
>>>>>>> 60e3c40 (update)
=======
optional.ts:21

___

### ifEmpty

• **ifEmpty**: (`cb`: () => `any`) => `T`

#### Type declaration

▸ (`cb`): `T`

##### Parameters

| Name | Type |
| :------ | :------ |
| `cb` | () => `any` |

##### Returns

`T`

#### Defined in

optional.ts:14
>>>>>>> ae4c564 (update)

___

### icbumberNotZero

• **icbumberNotZero**: (`cb`: (`value`: `T`) => `T`) => `T`

#### Type declaration

▸ (`cb`): `T`

##### Parameters

| Name | Type |
| :------ | :------ |
| `cb` | (`value`: `T`) => `T` |

##### Returns

`T`

#### Defined in

<<<<<<< HEAD
<<<<<<< HEAD
[optional.ts:11](https://github.com/osins/osins-utils/blob/096e636/src/optional.ts#L11)
=======
optional.ts:14
>>>>>>> 60e3c40 (update)
=======
optional.ts:15
>>>>>>> ae4c564 (update)

___

### icbumberNotZeroOrElse

• **icbumberNotZeroOrElse**: (`cb1`: (`value`: `T`) => `T`, `cb2`: (`value`: `T`) => `T`) => `T`

#### Type declaration

▸ (`cb1`, `cb2`): `T`

##### Parameters

| Name | Type |
| :------ | :------ |
| `cb1` | (`value`: `T`) => `T` |
| `cb2` | (`value`: `T`) => `T` |

##### Returns

`T`

#### Defined in

<<<<<<< HEAD
<<<<<<< HEAD
[optional.ts:12](https://github.com/osins/osins-utils/blob/096e636/src/optional.ts#L12)
=======
optional.ts:22
>>>>>>> 60e3c40 (update)
=======
optional.ts:23
>>>>>>> ae4c564 (update)

___

### ifArrayNotEmpty

• **ifArrayNotEmpty**: (`cb`: (`data`: `T`) => `T`) => ``null`` \| `T`

#### Type declaration

▸ (`cb`): ``null`` \| `T`

##### Parameters

| Name | Type |
| :------ | :------ |
| `cb` | (`data`: `T`) => `T` |

##### Returns

``null`` \| `T`

#### Defined in

<<<<<<< HEAD
<<<<<<< HEAD
[optional.ts:22](https://github.com/osins/osins-utils/blob/096e636/src/optional.ts#L22)
=======
optional.ts:21
>>>>>>> 60e3c40 (update)
=======
optional.ts:22
>>>>>>> ae4c564 (update)

___

### ifArrayNotEmptyOrElse

• **ifArrayNotEmptyOrElse**: (`cb1`: (`data`: `T`) => `T`, `cb2`: (`data`: `T`) => `T`) => ``null`` \| `T`

#### Type declaration

▸ (`cb1`, `cb2`): ``null`` \| `T`

##### Parameters

| Name | Type |
| :------ | :------ |
| `cb1` | (`data`: `T`) => `T` |
| `cb2` | (`data`: `T`) => `T` |

##### Returns

``null`` \| `T`

#### Defined in

<<<<<<< HEAD
<<<<<<< HEAD
[optional.ts:23](https://github.com/osins/osins-utils/blob/096e636/src/optional.ts#L23)
=======
optional.ts:24
>>>>>>> 60e3c40 (update)
=======
optional.ts:25
>>>>>>> ae4c564 (update)

___

### ifFail

• **ifFail**: (`cb`: (`value`: `T`) => `void`) => `void`

#### Type declaration

▸ (`cb`): `void`

##### Parameters

| Name | Type |
| :------ | :------ |
| `cb` | (`value`: `T`) => `void` |

##### Returns

`void`

#### Defined in

<<<<<<< HEAD
[optional.ts:17](https://github.com/osins/osins-utils/blob/096e636/src/optional.ts#L17)
=======
optional.ts:11
>>>>>>> 60e3c40 (update)

___

### ifIsTrue

• **ifIsTrue**: (`cb`: (`data`: `T`) => `T`) => ``false`` \| `T`

#### Type declaration

▸ (`cb`): ``false`` \| `T`

##### Parameters

| Name | Type |
| :------ | :------ |
| `cb` | (`data`: `T`) => `T` |

##### Returns

``false`` \| `T`

#### Defined in

[optional.ts:15](https://github.com/osins/osins-utils/blob/096e636/src/optional.ts#L15)

___

### ifIsTrueOrElse

• **ifIsTrueOrElse**: (`cb1`: (`data`: `T`) => `any`, `cb2`: (`data`: `T`) => `T`) => `void`

#### Type declaration

▸ (`cb1`, `cb2`): `void`

##### Parameters

| Name | Type |
| :------ | :------ |
| `cb1` | (`data`: `T`) => `any` |
| `cb2` | (`data`: `T`) => `T` |

##### Returns

`void`

#### Defined in

<<<<<<< HEAD
[optional.ts:16](https://github.com/osins/osins-utils/blob/096e636/src/optional.ts#L16)
=======
optional.ts:12
>>>>>>> 60e3c40 (update)

___

### ifPresent

• **ifPresent**: (`cb`: (`value`: `T`) => `T`) => ``null`` \| `T`

#### Type declaration

▸ (`cb`): ``null`` \| `T`

##### Parameters

| Name | Type |
| :------ | :------ |
| `cb` | (`value`: `T`) => `T` |

##### Returns

``null`` \| `T`

#### Defined in

<<<<<<< HEAD
[optional.ts:10](https://github.com/osins/osins-utils/blob/096e636/src/optional.ts#L10)
=======
optional.ts:10
>>>>>>> 60e3c40 (update)

___

### ifPresentOrElse

• **ifPresentOrElse**: (`cb1`: `undefined` \| (`value`: `T`) => `void`, `cb2`: `undefined` \| (`value`: `T`) => `void`) => ``null`` \| `T`

#### Type declaration

▸ (`cb1`, `cb2`): ``null`` \| `T`

##### Parameters

| Name | Type |
| :------ | :------ |
| `cb1` | `undefined` \| (`value`: `T`) => `void` |
| `cb2` | `undefined` \| (`value`: `T`) => `void` |

##### Returns

``null`` \| `T`

#### Defined in

<<<<<<< HEAD
<<<<<<< HEAD
[optional.ts:18](https://github.com/osins/osins-utils/blob/096e636/src/optional.ts#L18)
=======
optional.ts:15
>>>>>>> 60e3c40 (update)
=======
optional.ts:16
>>>>>>> ae4c564 (update)

___

### isEmpty

• **isEmpty**: () => `boolean`

#### Type declaration

▸ (): `boolean`

##### Returns

`boolean`

#### Defined in

<<<<<<< HEAD
[optional.ts:13](https://github.com/osins/osins-utils/blob/096e636/src/optional.ts#L13)
=======
optional.ts:13
>>>>>>> 60e3c40 (update)

___

### isNotFalse

• **isNotFalse**: () => `boolean`

#### Type declaration

▸ (): `boolean`

##### Returns

`boolean`

#### Defined in

<<<<<<< HEAD
<<<<<<< HEAD
[optional.ts:25](https://github.com/osins/osins-utils/blob/096e636/src/optional.ts#L25)
=======
optional.ts:23
>>>>>>> 60e3c40 (update)
=======
optional.ts:24
>>>>>>> ae4c564 (update)

___

### isNumeric

• **isNumeric**: () => `boolean`

#### Type declaration

▸ (): `boolean`

##### Returns

`boolean`

#### Defined in

<<<<<<< HEAD
[optional.ts:6](https://github.com/osins/osins-utils/blob/096e636/src/optional.ts#L6)
=======
optional.ts:6
>>>>>>> 60e3c40 (update)

___

### isPresent

• **isPresent**: () => `boolean`

#### Type declaration

▸ (): `boolean`

##### Returns

`boolean`

#### Defined in

<<<<<<< HEAD
[optional.ts:2](https://github.com/osins/osins-utils/blob/096e636/src/optional.ts#L2)

___

### isTrue

• **isTrue**: () => `boolean`

#### Type declaration

▸ (): `boolean`

##### Returns

`boolean`

#### Defined in

[optional.ts:14](https://github.com/osins/osins-utils/blob/096e636/src/optional.ts#L14)
=======
optional.ts:2
>>>>>>> 60e3c40 (update)

___

### map

• **map**: <S\>(`key`: `string`) => [`OptionalType`](OptionalType.md)<`S`\>

#### Type declaration

▸ <`S`\>(`key`): [`OptionalType`](OptionalType.md)<`S`\>

##### Type parameters

| Name |
| :------ |
| `S` |

##### Parameters

| Name | Type |
| :------ | :------ |
| `key` | `string` |

##### Returns

[`OptionalType`](OptionalType.md)<`S`\>

#### Defined in

<<<<<<< HEAD
[optional.ts:5](https://github.com/osins/osins-utils/blob/096e636/src/optional.ts#L5)
=======
optional.ts:5
>>>>>>> 60e3c40 (update)

___

### numberNotZero

• **numberNotZero**: () => `boolean`

#### Type declaration

▸ (): `boolean`

##### Returns

`boolean`

#### Defined in

<<<<<<< HEAD
[optional.ts:8](https://github.com/osins/osins-utils/blob/096e636/src/optional.ts#L8)
=======
optional.ts:8
>>>>>>> 60e3c40 (update)

___

### numberValue

• **numberValue**: () => `number`

#### Type declaration

▸ (): `number`

##### Returns

`number`

#### Defined in

<<<<<<< HEAD
[optional.ts:7](https://github.com/osins/osins-utils/blob/096e636/src/optional.ts#L7)
=======
optional.ts:7
>>>>>>> 60e3c40 (update)

___

### orElse

• **orElse**: (`elseValue`: `T`) => `T`

#### Type declaration

▸ (`elseValue`): `T`

##### Parameters

| Name | Type |
| :------ | :------ |
| `elseValue` | `T` |

##### Returns

`T`

#### Defined in

<<<<<<< HEAD
[optional.ts:4](https://github.com/osins/osins-utils/blob/096e636/src/optional.ts#L4)
=======
optional.ts:4
>>>>>>> 60e3c40 (update)
