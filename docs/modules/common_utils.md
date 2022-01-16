[awesome-nestjs-boilerplate](../README.md) / [Modules](../modules.md) / common/utils

# Module: common/utils

## Table of contents

### Functions

- [generateHash](common_utils.md#generatehash)
- [getVariableName](common_utils.md#getvariablename)
- [validateHash](common_utils.md#validatehash)

## Functions

### generateHash

▸ **generateHash**(`password`): `string`

generate hash from password or string

#### Parameters

| Name | Type |
| :------ | :------ |
| `password` | `string` |

#### Returns

`string`

#### Defined in

[common/utils.ts:10](https://github.com/klub-deepak/awesome-nest-boilerplate/blob/260b9ca/src/common/utils.ts#L10)

___

### getVariableName

▸ **getVariableName**<`TResult`\>(`getVar`): `string`

#### Type parameters

| Name |
| :------ |
| `TResult` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `getVar` | () => `TResult` |

#### Returns

`string`

#### Defined in

[common/utils.ts:31](https://github.com/klub-deepak/awesome-nest-boilerplate/blob/260b9ca/src/common/utils.ts#L31)

___

### validateHash

▸ **validateHash**(`password`, `hash`): `Promise`<`boolean`\>

validate text with hash

#### Parameters

| Name | Type |
| :------ | :------ |
| `password` | `Optional`<`string`\> |
| `hash` | `Optional`<`string`\> |

#### Returns

`Promise`<`boolean`\>

#### Defined in

[common/utils.ts:20](https://github.com/klub-deepak/awesome-nest-boilerplate/blob/260b9ca/src/common/utils.ts#L20)
