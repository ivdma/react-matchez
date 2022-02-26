---
id: "getPatternMatch"
title: "Function: getPatternMatch"
sidebar_label: "getPatternMatch"
sidebar_position: 0
custom_edit_url: null
---

▸ `Const` **getPatternMatch**<`Shape`\>(`value?`): `Object`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `Shape` | extends `Object` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `value?` | `Shape` |

#### Returns

`Object`

| Name | Type |
| :------ | :------ |
| `Exact` | `ComponentType`<[`ExactProps`](../types/ExactProps.md)<`Shape`\>\> |
| `Match` | `ComponentType`<[`MatchProps`](../interfaces/MatchProps.md)<`Shape`\>\> |
| `Otherwise` | (`props`: [`OtherwiseProps`](../interfaces/OtherwiseProps.md)) => `Element` |
| `Switch` | `ComponentType`<[`SwitchProps`](../types/SwitchProps.md)<`Shape`\>\> |
| `When` | `ComponentType`<[`WhenProps`](../interfaces/WhenProps.md)<`Shape`\>\> |
| `With` | `ComponentType`<[`WithProps`](../types/WithProps.md)<`Shape`\>\> |

#### Defined in

[src/utils/pattern-match.ts:17](https://github.com/ythecombinator/react-matchez/blob/c3e2afb/src/utils/pattern-match.ts#L17)
