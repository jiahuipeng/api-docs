[Type](../modules/Type.Type.md) / Matrix3x3

# Matrix3x3 <Badge type="tip" text="Class" /> <Score text="Matrix3x3" />

三维矩阵

::: warning Precautions

列矩阵

:::

## Table of contents

| Properties |
| :-----|
| **[m00](Type.Matrix3x3.md#m00)**: `number` <br> 矩阵第 0 列第 0 行的元素。|
| **[m01](Type.Matrix3x3.md#m01)**: `number` <br> 矩阵第 0 列第 1 行的元素。|
| **[m02](Type.Matrix3x3.md#m02)**: `number` <br> 矩阵第 0 列第 2 行的元素。|
| **[m10](Type.Matrix3x3.md#m10)**: `number` <br> 矩阵第 1 列第 0 行的元素。|
| **[m11](Type.Matrix3x3.md#m11)**: `number` <br> 矩阵第 1 列第 1 行的元素。|
| **[m12](Type.Matrix3x3.md#m12)**: `number` <br> 矩阵第 1 列第 2 行的元素。|
| **[m20](Type.Matrix3x3.md#m20)**: `number` <br> 矩阵第 2 列第 0 行的元素。|
| **[m21](Type.Matrix3x3.md#m21)**: `number` <br> 矩阵第 2 列第 1 行的元素。|
| **[m22](Type.Matrix3x3.md#m22)**: `number` <br> 矩阵第 2 列第 2 行的元素。|

| Accessors |
| :-----|
| **[identity](Type.Matrix3x3.md#identity)**(): `void` <br> 将当前矩阵设为单位矩阵。|

| Methods |
| :-----|
| **[add](Type.Matrix3x3.md#add)**([`Matrix3x3`](Type.Matrix3x3.md), [`Matrix3x3`](Type.Matrix3x3.md), [`Matrix3x3`](Type.Matrix3x3.md)): [`Matrix3x3`](Type.Matrix3x3.md) <br> 逐元素矩阵加法|
| **[clone](Type.Matrix3x3.md#clone)**([`Matrix3x3`](Type.Matrix3x3.md)): [`Matrix3x3`](Type.Matrix3x3.md) <br> 获得指定矩阵的拷贝|
| **[determinant](Type.Matrix3x3.md#determinant)**([`Matrix3x3`](Type.Matrix3x3.md)): `number` <br> 求目标矩阵行列式|
| **[equals](Type.Matrix3x3.md#equals)**([`Matrix3x3`](Type.Matrix3x3.md), [`Matrix3x3`](Type.Matrix3x3.md), `number`): `boolean` <br> 排除浮点数误差的矩阵近似等价判断|
| **[identity](Type.Matrix3x3.md#identity-1)**(): `void` <br> 将当前矩阵设为单位矩阵。|
| **[invert](Type.Matrix3x3.md#invert)**([`Matrix3x3`](Type.Matrix3x3.md), [`Matrix3x3`](Type.Matrix3x3.md)): [`Matrix3x3`](Type.Matrix3x3.md) <br> 将目标矩阵求逆，注意，在矩阵不可逆时，会返回一个全为 0 的矩阵。|
| **[multiply](Type.Matrix3x3.md#multiply)**([`Matrix3x3`](Type.Matrix3x3.md), [`Matrix3x3`](Type.Matrix3x3.md), [`Matrix3x3`](Type.Matrix3x3.md)): [`Matrix3x3`](Type.Matrix3x3.md) <br> 矩阵乘法|
| **[rotate](Type.Matrix3x3.md#rotate)**([`Matrix3x3`](Type.Matrix3x3.md), `number`, [`Matrix3x3`](Type.Matrix3x3.md)): [`Matrix3x3`](Type.Matrix3x3.md) <br> 在给定矩阵变换基础上加入新旋转变换|
| **[scale](Type.Matrix3x3.md#scale)**([`Matrix3x3`](Type.Matrix3x3.md), [`Vector`](Type.Vector.md), [`Matrix3x3`](Type.Matrix3x3.md)): [`Matrix3x3`](Type.Matrix3x3.md) <br> 在给定矩阵变换基础上加入新缩放变换|
| **[set](Type.Matrix3x3.md#set)**([`Matrix3x3`](Type.Matrix3x3.md)): [`Matrix3x3`](Type.Matrix3x3.md) <br> 设置当前矩阵使其与指定矩阵相等。|
| **[strictEquals](Type.Matrix3x3.md#strictequals)**([`Matrix3x3`](Type.Matrix3x3.md), [`Matrix3x3`](Type.Matrix3x3.md)): `boolean` <br> 矩阵等价判断|
| **[subtract](Type.Matrix3x3.md#subtract)**([`Matrix3x3`](Type.Matrix3x3.md), [`Matrix3x3`](Type.Matrix3x3.md), [`Matrix3x3`](Type.Matrix3x3.md)): [`Matrix3x3`](Type.Matrix3x3.md) <br> 逐元素矩阵减法|
| **[toString](Type.Matrix3x3.md#tostring)**(): `string` <br> 返回当前矩阵的字符串表示。|
| **[transpose](Type.Matrix3x3.md#transpose)**([`Matrix3x3`](Type.Matrix3x3.md), [`Matrix3x3`](Type.Matrix3x3.md)): [`Matrix3x3`](Type.Matrix3x3.md) <br> 将目标矩阵变为转置矩阵|
| **[add](Type.Matrix3x3.md#add-1)**([`Matrix3x3`](Type.Matrix3x3.md), [`Matrix3x3`](Type.Matrix3x3.md), [`Matrix3x3`](Type.Matrix3x3.md)): [`Matrix3x3`](Type.Matrix3x3.md) <br> 逐元素矩阵加法|
| **[clone](Type.Matrix3x3.md#clone-1)**([`Matrix3x3`](Type.Matrix3x3.md)): [`Matrix3x3`](Type.Matrix3x3.md) <br> 获得指定矩阵的拷贝|
| **[determinant](Type.Matrix3x3.md#determinant-1)**([`Matrix3x3`](Type.Matrix3x3.md)): `number` <br> 求目标矩阵行列式|
| **[equals](Type.Matrix3x3.md#equals-1)**([`Matrix3x3`](Type.Matrix3x3.md), [`Matrix3x3`](Type.Matrix3x3.md), `number`): `boolean` <br> 排除浮点数误差的矩阵近似等价判断|
| **[fromMat4](Type.Matrix3x3.md#frommat4)**([`Matrix4x4`](Type.Matrix4x4.md), [`Matrix3x3`](Type.Matrix3x3.md)): [`Matrix3x3`](Type.Matrix3x3.md) <br> 取四阶矩阵的前三阶|
| **[fromRotation](Type.Matrix3x3.md#fromrotation)**(`number`, [`Matrix3x3`](Type.Matrix3x3.md)): [`Matrix3x3`](Type.Matrix3x3.md) <br> 计算旋转矩阵|
| **[fromScaling](Type.Matrix3x3.md#fromscaling)**([`Vector2`](Type.Vector2.md), [`Matrix3x3`](Type.Matrix3x3.md)): [`Matrix3x3`](Type.Matrix3x3.md) <br> 计算缩放矩阵|
| **[fromTranslation](Type.Matrix3x3.md#fromtranslation)**([`Vector2`](Type.Vector2.md), [`Matrix3x3`](Type.Matrix3x3.md)): [`Matrix3x3`](Type.Matrix3x3.md) <br> 计算位移矩阵|
| **[fromViewUp](Type.Matrix3x3.md#fromviewup)**([`Vector`](Type.Vector.md), [`Vector`](Type.Vector.md), [`Matrix3x3`](Type.Matrix3x3.md), `number`): [`Matrix3x3`](Type.Matrix3x3.md) <br> 根据视口前方向和上方向计算矩阵|
| **[inverseTransposeMat4](Type.Matrix3x3.md#inversetransposemat4)**([`Matrix4x4`](Type.Matrix4x4.md), [`Matrix3x3`](Type.Matrix3x3.md)): [`Matrix3x3`](Type.Matrix3x3.md) <br> 计算指定四阶矩阵的逆转置三维矩阵|
| **[invert](Type.Matrix3x3.md#invert-1)**([`Matrix3x3`](Type.Matrix3x3.md), [`Matrix3x3`](Type.Matrix3x3.md)): [`Matrix3x3`](Type.Matrix3x3.md) <br> 将目标矩阵求逆，注意，在矩阵不可逆时，会返回一个全为 0 的矩阵。|
| **[multiply](Type.Matrix3x3.md#multiply-1)**([`Matrix3x3`](Type.Matrix3x3.md), [`Matrix3x3`](Type.Matrix3x3.md), [`Matrix3x3`](Type.Matrix3x3.md)): [`Matrix3x3`](Type.Matrix3x3.md) <br> 矩阵乘法|
| **[rotate](Type.Matrix3x3.md#rotate-1)**([`Matrix3x3`](Type.Matrix3x3.md), `number`, [`Matrix3x3`](Type.Matrix3x3.md)): [`Matrix3x3`](Type.Matrix3x3.md) <br> 在给定矩阵变换基础上加入新旋转变换|
| **[scale](Type.Matrix3x3.md#scale-1)**([`Matrix3x3`](Type.Matrix3x3.md), [`Vector`](Type.Vector.md), [`Matrix3x3`](Type.Matrix3x3.md)): [`Matrix3x3`](Type.Matrix3x3.md) <br> 在给定矩阵变换基础上加入新缩放变换|
| **[strictEquals](Type.Matrix3x3.md#strictequals-1)**([`Matrix3x3`](Type.Matrix3x3.md), [`Matrix3x3`](Type.Matrix3x3.md)): `boolean` <br> 矩阵等价判断|
| **[subtract](Type.Matrix3x3.md#subtract-1)**([`Matrix3x3`](Type.Matrix3x3.md), [`Matrix3x3`](Type.Matrix3x3.md), [`Matrix3x3`](Type.Matrix3x3.md)): [`Matrix3x3`](Type.Matrix3x3.md) <br> 逐元素矩阵减法|
| **[transformVector](Type.Matrix3x3.md#transformvector)**([`Matrix3x3`](Type.Matrix3x3.md), [`Vector`](Type.Vector.md), [`Vector`](Type.Vector.md)): [`Vector`](Type.Vector.md) <br> 向量与三维矩阵乘法|
| **[transformVector2](Type.Matrix3x3.md#transformvector2)**([`Matrix3x3`](Type.Matrix3x3.md), [`Vector2`](Type.Vector2.md), [`Vector2`](Type.Vector2.md)): [`Vector2`](Type.Vector2.md) <br> 向量与三维矩阵乘法，默认向量第三位为 1。|
| **[transpose](Type.Matrix3x3.md#transpose-1)**([`Matrix3x3`](Type.Matrix3x3.md), [`Matrix3x3`](Type.Matrix3x3.md)): [`Matrix3x3`](Type.Matrix3x3.md) <br> 将目标矩阵变为转置矩阵|

用给定的 Matrix3x3 构建一个新的 Matrix3x3

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `other` | [`Matrix3x3`](Type.Matrix3x3.md) | 给定的 Matrix3x3 对象 |

• **new Matrix3x3**(`m00?`, `m01?`, `m02?`, `m10?`, `m11?`, `m12?`, `m20?`, `m21?`, `m22?`)

用给定的元素构建一个新的 Matrix3x3

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `m00?` | `number` | 第 0 列第 0 行的元素 default:1 |
| `m01?` | `number` | 第 0 列第 1 行的元素 default:0 |
| `m02?` | `number` | 第 0 列第 2 行的元素 default:0 |
| `m10?` | `number` | 第 1 列第 0 行的元素 default:0 |
| `m11?` | `number` | 第 1 列第 1 行的元素 default:1 |
| `m12?` | `number` | 第 1 列第 2 行的元素 default:0 |
| `m20?` | `number` | 第 2 列第 0 行的元素 default:0 |
| `m21?` | `number` | 第 2 列第 1 行的元素 default:0 |
| `m22?` | `number` | 第 2 列第 2 行的元素 default:1 |

## Properties

### m00 <Score text="m" /> 

• **m00**: `number`

矩阵第 0 列第 0 行的元素。

___

### m01 <Score text="m" /> 

• **m01**: `number`

矩阵第 0 列第 1 行的元素。

___

### m02 <Score text="m" /> 

• **m02**: `number`

矩阵第 0 列第 2 行的元素。

___

### m10 <Score text="m" /> 

• **m10**: `number`

矩阵第 1 列第 0 行的元素。

___

### m11 <Score text="m" /> 

• **m11**: `number`

矩阵第 1 列第 1 行的元素。

___

### m12 <Score text="m" /> 

• **m12**: `number`

矩阵第 1 列第 2 行的元素。

___

### m20 <Score text="m" /> 

• **m20**: `number`

矩阵第 2 列第 0 行的元素。

___

### m21 <Score text="m" /> 

• **m21**: `number`

矩阵第 2 列第 1 行的元素。

___

### m22 <Score text="m" /> 

• **m22**: `number`

矩阵第 2 列第 2 行的元素。

## Accessors

### identity <Score text="identity" /> 

• `Static` `get` **identity**(): [`Matrix3x3`](Type.Matrix3x3.md)

获得一个默认矩阵

#### Returns

[`Matrix3x3`](Type.Matrix3x3.md)

## Methods

### add <Score text="add" /> 

• **add**(`mat`): [`Matrix3x3`](Type.Matrix3x3.md) <Badge type="tip" text="other" />

矩阵逐元素相加。


#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `mat` | [`Matrix3x3`](Type.Matrix3x3.md) | 矩阵 |

#### Returns

[`Matrix3x3`](Type.Matrix3x3.md)

this

___

### clone <Score text="clone" /> 

• **clone**(): [`Matrix3x3`](Type.Matrix3x3.md) <Badge type="tip" text="other" />

克隆当前矩阵。


#### Returns

[`Matrix3x3`](Type.Matrix3x3.md)

克隆的新矩阵

___

### determinant <Score text="determinant" /> 

• **determinant**(): `number` <Badge type="tip" text="other" />

计算当前矩阵的行列式。


#### Returns

`number`

当前矩阵的行列式。

___

### equals <Score text="equals" /> 

• **equals**(`other`, `epsilon?`): `boolean` <Badge type="tip" text="other" />

判断当前矩阵是否在误差范围内与指定矩阵相等。


#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `other` | [`Matrix3x3`](Type.Matrix3x3.md) | 比对的矩阵 |
| `epsilon?` | `number` | 误差值 default:1.e-7 |

#### Returns

`boolean`

比对的结果

___

### identity <Score text="identity" /> 

• **identity**(): `void` <Badge type="tip" text="other" />

将当前矩阵设为单位矩阵。



___

### invert <Score text="invert" /> 

• **invert**(): `void` <Badge type="tip" text="other" />

将当前矩阵计算为其逆矩阵。注意，在矩阵不可逆时，会返回一个全为 0 的矩阵。



___

### multiply <Score text="multiply" /> 

• **multiply**(`mat`): [`Matrix3x3`](Type.Matrix3x3.md) <Badge type="tip" text="other" />

矩阵乘法。将当前矩阵左乘指定矩阵的结果赋值给当前矩阵。


#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `mat` | [`Matrix3x3`](Type.Matrix3x3.md) | 矩阵 |

#### Returns

[`Matrix3x3`](Type.Matrix3x3.md)

this

• **multiply**(`v`): [`Matrix3x3`](Type.Matrix3x3.md) <Badge type="tip" text="other" />

矩阵数乘。将当前矩阵与指定标量的数乘结果赋值给当前矩阵。


#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `v` | `number` | 数 |

#### Returns

[`Matrix3x3`](Type.Matrix3x3.md)

this

___

### rotate <Score text="rotate" /> 

• **rotate**(`rad`): [`Matrix3x3`](Type.Matrix3x3.md) <Badge type="tip" text="other" />

将当前矩阵左乘旋转矩阵的结果赋值给当前矩阵，旋转矩阵由旋转轴和旋转角度给出。


#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `rad` | `number` | 旋转的弧度 |

#### Returns

[`Matrix3x3`](Type.Matrix3x3.md)

this

___

### scale <Score text="scale" /> 

• **scale**(`vec`): [`Matrix3x3`](Type.Matrix3x3.md) <Badge type="tip" text="other" />

将当前矩阵左乘缩放矩阵的结果赋值给当前矩阵，缩放矩阵由各个轴的缩放给出。


#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `vec` | [`Vector`](Type.Vector.md) | 对矩阵缩放的向量 |

#### Returns

[`Matrix3x3`](Type.Matrix3x3.md)

this

___

### set <Score text="set" /> 

• **set**(`other`): [`Matrix3x3`](Type.Matrix3x3.md) <Badge type="tip" text="other" />

设置当前矩阵使其与指定矩阵相等。


#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `other` | [`Matrix3x3`](Type.Matrix3x3.md) | 指定矩阵 |

#### Returns

[`Matrix3x3`](Type.Matrix3x3.md)

this

• **set**(`m00?`, `m01?`, `m02?`, `m10?`, `m11?`, `m12?`, `m20?`, `m21?`, `m22?`): [`Matrix3x3`](Type.Matrix3x3.md) <Badge type="tip" text="other" />

设置当前矩阵指定元素值。


#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `m00?` | `number` | 第0行第0列的元素 default:1 |
| `m01?` | `number` | 第0行第1列的元素 default:0 |
| `m02?` | `number` | 第0行第2列的元素 default:0 |
| `m10?` | `number` | 第1行第0列的元素 default:0 |
| `m11?` | `number` | 第1行第1列的元素 default:1 |
| `m12?` | `number` | 第1行第2列的元素 default:0 |
| `m20?` | `number` | 第2行第0列的元素 default:0 |
| `m21?` | `number` | 第2行第1列的元素 default:0 |
| `m22?` | `number` | 第2行第2列的元素 default:1 |

#### Returns

[`Matrix3x3`](Type.Matrix3x3.md)

this

___

### strictEquals <Score text="strictEquals" /> 

• **strictEquals**(`other`): `boolean` <Badge type="tip" text="other" />

判断当前矩阵是否与指定矩阵相等。


#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `other` | [`Matrix3x3`](Type.Matrix3x3.md) | 比对的矩阵 |

#### Returns

`boolean`

比对的结果

___

### subtract <Score text="subtract" /> 

• **subtract**(`mat`): [`Matrix3x3`](Type.Matrix3x3.md) <Badge type="tip" text="other" />

当前矩阵逐元素减去参数矩阵


#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `mat` | [`Matrix3x3`](Type.Matrix3x3.md) | 矩阵 |

#### Returns

[`Matrix3x3`](Type.Matrix3x3.md)

this

___

### toString <Score text="toString" /> 

• **toString**(): `string` <Badge type="tip" text="other" />

返回当前矩阵的字符串表示。


#### Returns

`string`

返回矩阵的字符串信息

___

### transpose <Score text="transpose" /> 

• **transpose**(): `void` <Badge type="tip" text="other" />

将当前矩阵计算为其转置矩阵。



___

### add <Score text="add" /> 

• `Static` **add**(`a`, `b`, `outer?`): [`Matrix3x3`](Type.Matrix3x3.md) <Badge type="tip" text="other" />

逐元素矩阵加法


::: warning Precautions

如果 outer 不为空, 返回 outer,否则返回一个新的 Matrix3x3 对象, 建议传入 outer 来减少 new 对象且 outer 不能为 null/undefined

:::

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `a` | [`Matrix3x3`](Type.Matrix3x3.md) | 矩阵a |
| `b` | [`Matrix3x3`](Type.Matrix3x3.md) | 矩阵b |
| `outer?` | [`Matrix3x3`](Type.Matrix3x3.md) | 接收结果的矩阵 default:null |

#### Returns

[`Matrix3x3`](Type.Matrix3x3.md)

计算后的矩阵

___

### clone <Score text="clone" /> 

• `Static` **clone**(`a`): [`Matrix3x3`](Type.Matrix3x3.md) <Badge type="tip" text="other" />

获得指定矩阵的拷贝


#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `a` | [`Matrix3x3`](Type.Matrix3x3.md) | 指定矩阵 |

#### Returns

[`Matrix3x3`](Type.Matrix3x3.md)

一个新的矩阵

___

### determinant <Score text="determinant" /> 

• `Static` **determinant**(`a`): `number` <Badge type="tip" text="other" />

求目标矩阵行列式


#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `a` | [`Matrix3x3`](Type.Matrix3x3.md) | 目标矩阵 |

#### Returns

`number`

行列式的结果

___

### equals <Score text="equals" /> 

• `Static` **equals**(`a`, `b`, `epsilon?`): `boolean` <Badge type="tip" text="other" />

排除浮点数误差的矩阵近似等价判断


#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `a` | [`Matrix3x3`](Type.Matrix3x3.md) | 矩阵a |
| `b` | [`Matrix3x3`](Type.Matrix3x3.md) | 矩阵b |
| `epsilon?` | `number` | 误差值 default:1.e-7 |

#### Returns

`boolean`

返回比对结果

___

### fromMat4 <Score text="fromMat" /> 

• `Static` **fromMat4**(`a`, `outer?`): [`Matrix3x3`](Type.Matrix3x3.md) <Badge type="tip" text="other" />

取四阶矩阵的前三阶


::: warning Precautions

如果 outer 不为空, 返回 outer,否则返回一个新的 Matrix3x3 对象, 建议传入 outer 来减少 new 对象且 outer 不能为 null/undefined

:::

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `a` | [`Matrix4x4`](Type.Matrix4x4.md) | 源四阶矩阵 |
| `outer?` | [`Matrix3x3`](Type.Matrix3x3.md) | 接收结果三维矩阵对象 default:null |

#### Returns

[`Matrix3x3`](Type.Matrix3x3.md)

提取后的三维矩阵

___

### fromRotation <Score text="fromRotation" /> 

• `Static` **fromRotation**(`rad`, `outer?`): [`Matrix3x3`](Type.Matrix3x3.md) <Badge type="tip" text="other" />

计算旋转矩阵


::: warning Precautions

如果 outer 不为空, 返回 outer,否则返回一个新的 Matrix3x3 对象, 建议传入 outer 来减少 new 对象且 outer 不能为 null/undefined

:::

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `rad` | `number` | 旋转弧度 |
| `outer?` | [`Matrix3x3`](Type.Matrix3x3.md) | 接收结果三维矩阵对象 default:null |

#### Returns

[`Matrix3x3`](Type.Matrix3x3.md)

含旋转信息的三维矩阵

___

### fromScaling <Score text="fromScaling" /> 

• `Static` **fromScaling**(`v`, `outer?`): [`Matrix3x3`](Type.Matrix3x3.md) <Badge type="tip" text="other" />

计算缩放矩阵


::: warning Precautions

如果 outer 不为空, 返回 outer,否则返回一个新的 Matrix3x3 对象, 建议传入 outer 来减少 new 对象且 outer 不能为 null/undefined

:::

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `v` | [`Vector2`](Type.Vector2.md) | 缩放信息的二维向量 |
| `outer?` | [`Matrix3x3`](Type.Matrix3x3.md) | 接收结果三维矩阵对象 default:null |

#### Returns

[`Matrix3x3`](Type.Matrix3x3.md)

含缩放信息的三维矩阵

___

### fromTranslation <Score text="fromTranslation" /> 

• `Static` **fromTranslation**(`v`, `outer?`): [`Matrix3x3`](Type.Matrix3x3.md) <Badge type="tip" text="other" />

计算位移矩阵


::: warning Precautions

如果 outer 不为空, 返回 outer,否则返回一个新的 Matrix3x3 对象, 建议传入 outer 来减少 new 对象且 outer 不能为 null/undefined

:::

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `v` | [`Vector2`](Type.Vector2.md) | 位移的二维向量 |
| `outer?` | [`Matrix3x3`](Type.Matrix3x3.md) | 接收结果三维矩阵对象 default:null |

#### Returns

[`Matrix3x3`](Type.Matrix3x3.md)

含位移信息的三维矩阵

___

### fromViewUp <Score text="fromViewUp" /> 

• `Static` **fromViewUp**(`view`, `up?`, `outer?`, `epsilon?`): [`Matrix3x3`](Type.Matrix3x3.md) <Badge type="tip" text="other" />

根据视口前方向和上方向计算矩阵


::: warning Precautions

如果 outer 不为空, 返回 outer,否则返回一个新的 Matrix3x3 对象, 建议传入 outer 来减少 new 对象且 outer 不能为 null/undefined

:::

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `view` | [`Vector`](Type.Vector.md) | 视口向量 |
| `up?` | [`Vector`](Type.Vector.md) | 视口的上向量 default:null |
| `outer?` | [`Matrix3x3`](Type.Matrix3x3.md) | 接收结果三维矩阵对象 default:null |
| `epsilon?` | `number` | 最小误差数 default:MathDefine.EPSILON |

#### Returns

[`Matrix3x3`](Type.Matrix3x3.md)

计算后的三维矩阵

___

### inverseTransposeMat4 <Score text="inverseTransposeMat" /> 

• `Static` **inverseTransposeMat4**(`a`, `outer?`): [`Matrix3x3`](Type.Matrix3x3.md) <Badge type="tip" text="other" />

计算指定四阶矩阵的逆转置三维矩阵


::: warning Precautions

如果 outer 不为空, 返回 outer,否则返回一个新的 Matrix3x3 对象, 建议传入 outer 来减少 new 对象且 outer 不能为 null/undefined

:::

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `a` | [`Matrix4x4`](Type.Matrix4x4.md) | 四阶矩阵 |
| `outer?` | [`Matrix3x3`](Type.Matrix3x3.md) | 接收结果三维矩阵对象 default:null |

#### Returns

[`Matrix3x3`](Type.Matrix3x3.md)

逆转置后的三维矩阵

___

### invert <Score text="invert" /> 

• `Static` **invert**(`a`, `outer?`): [`Matrix3x3`](Type.Matrix3x3.md) <Badge type="tip" text="other" />

将目标矩阵求逆，注意，在矩阵不可逆时，会返回一个全为 0 的矩阵。


::: warning Precautions

如果 outer 不为空, 返回 outer,否则返回一个新的 Matrix3x3 对象, 建议传入 outer 来减少 new 对象且 outer 不能为 null/undefined

:::

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `a` | [`Matrix3x3`](Type.Matrix3x3.md) | 目标矩阵 |
| `outer?` | [`Matrix3x3`](Type.Matrix3x3.md) | 写入数据的矩阵 default:null |

#### Returns

[`Matrix3x3`](Type.Matrix3x3.md)

求逆后的矩阵

___

### multiply <Score text="multiply" /> 

• `Static` **multiply**(`a`, `b`, `outer?`): [`Matrix3x3`](Type.Matrix3x3.md) <Badge type="tip" text="other" />

矩阵乘法


::: warning Precautions

如果 outer 不为空, 返回 outer,否则返回一个新的 Matrix3x3 对象, 建议传入 outer 来减少 new 对象且 outer 不能为 null/undefined

:::

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `a` | [`Matrix3x3`](Type.Matrix3x3.md) | 矩阵a |
| `b` | [`Matrix3x3`](Type.Matrix3x3.md) | 矩阵b |
| `outer?` | [`Matrix3x3`](Type.Matrix3x3.md) | 接收结果的矩阵 default:null |

#### Returns

[`Matrix3x3`](Type.Matrix3x3.md)

计算后的矩阵

• `Static` **multiply**(`a`, `b`, `outer?`): [`Matrix3x3`](Type.Matrix3x3.md) <Badge type="tip" text="other" />

取四阶矩阵的前三阶，与三维矩阵相乘


::: warning Precautions

如果 outer 不为空, 返回 outer,否则返回一个新的 Matrix3x3 对象, 建议传入 outer 来减少 new 对象且 outer 不能为 null/undefined

:::

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `a` | [`Matrix3x3`](Type.Matrix3x3.md) | 矩阵a |
| `b` | [`Matrix4x4`](Type.Matrix4x4.md) | 矩阵b |
| `outer?` | [`Matrix3x3`](Type.Matrix3x3.md) | 接收结果的矩阵 default:null |

#### Returns

[`Matrix3x3`](Type.Matrix3x3.md)

计算后的矩阵

• `Static` **multiply**(`a`, `b`, `outer?`): [`Matrix3x3`](Type.Matrix3x3.md) <Badge type="tip" text="other" />

矩阵标量乘法


::: warning Precautions

如果 outer 不为空, 返回 outer,否则返回一个新的 Matrix3x3 对象, 建议传入 outer 来减少 new 对象且 outer 不能为 null/undefined

:::

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `a` | [`Matrix3x3`](Type.Matrix3x3.md) | 矩阵a |
| `b` | `number` | 数字b |
| `outer?` | [`Matrix3x3`](Type.Matrix3x3.md) | 接收结果的矩阵 default:null |

#### Returns

[`Matrix3x3`](Type.Matrix3x3.md)

计算后的矩阵

___

### rotate <Score text="rotate" /> 

• `Static` **rotate**(`a`, `rad`, `outer?`): [`Matrix3x3`](Type.Matrix3x3.md) <Badge type="tip" text="other" />

在给定矩阵变换基础上加入新旋转变换


::: warning Precautions

如果 outer 不为空, 返回 outer,否则返回一个新的 Matrix3x3 对象, 建议传入 outer 来减少 new 对象且 outer 不能为 null/undefined

:::

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `a` | [`Matrix3x3`](Type.Matrix3x3.md) | 需要变换的矩阵 |
| `rad` | `number` | 旋转弧度 |
| `outer?` | [`Matrix3x3`](Type.Matrix3x3.md) | 接收结果三维矩阵对象 default:null |

#### Returns

[`Matrix3x3`](Type.Matrix3x3.md)

旋转后的三维矩阵

___

### scale <Score text="scale" /> 

• `Static` **scale**(`a`, `v`, `outer?`): [`Matrix3x3`](Type.Matrix3x3.md) <Badge type="tip" text="other" />

在给定矩阵变换基础上加入新缩放变换


::: warning Precautions

如果 outer 不为空, 返回 outer,否则返回一个新的 Matrix3x3 对象, 建议传入 outer 来减少 new 对象且 outer 不能为 null/undefined

:::

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `a` | [`Matrix3x3`](Type.Matrix3x3.md) | 三维矩阵 |
| `v` | [`Vector`](Type.Vector.md) | 缩放矩阵的三维向量 |
| `outer?` | [`Matrix3x3`](Type.Matrix3x3.md) | 接收结果三维矩阵对象 default:null |

#### Returns

[`Matrix3x3`](Type.Matrix3x3.md)

缩放后的三维矩阵

___

### strictEquals <Score text="strictEquals" /> 

• `Static` **strictEquals**(`a`, `b`): `boolean` <Badge type="tip" text="other" />

矩阵等价判断


#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `a` | [`Matrix3x3`](Type.Matrix3x3.md) | 矩阵a |
| `b` | [`Matrix3x3`](Type.Matrix3x3.md) | 矩阵b |

#### Returns

`boolean`

返回比对结果

___

### subtract <Score text="subtract" /> 

• `Static` **subtract**(`a`, `b`, `outer?`): [`Matrix3x3`](Type.Matrix3x3.md) <Badge type="tip" text="other" />

逐元素矩阵减法


::: warning Precautions

如果 outer 不为空, 返回 outer,否则返回一个新的 Matrix3x3 对象, 建议传入 outer 来减少 new 对象且 outer 不能为 null/undefined

:::

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `a` | [`Matrix3x3`](Type.Matrix3x3.md) | 矩阵a |
| `b` | [`Matrix3x3`](Type.Matrix3x3.md) | 矩阵b |
| `outer?` | [`Matrix3x3`](Type.Matrix3x3.md) | 接收结果的矩阵 default:null |

#### Returns

[`Matrix3x3`](Type.Matrix3x3.md)

计算后的矩阵

___

### transformVector <Score text="transformVector" /> 

• `Static` **transformVector**(`a`, `b`, `outer?`): [`Vector`](Type.Vector.md) <Badge type="tip" text="other" />

向量与三维矩阵乘法


::: warning Precautions

如果 outer 不为空, 返回 outer,否则返回一个新的 Matrix3x3 对象, 建议传入 outer 来减少 new 对象且 outer 不能为 null/undefined

:::

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `a` | [`Matrix3x3`](Type.Matrix3x3.md) | 三维矩阵 |
| `b` | [`Vector`](Type.Vector.md) | 三维向量 |
| `outer?` | [`Vector`](Type.Vector.md) | 被写入的三维向量 default:null |

#### Returns

[`Vector`](Type.Vector.md)

变换后的三维向量

___

### transformVector2 <Score text="transformVector" /> 

• `Static` **transformVector2**(`a`, `b`, `outer?`): [`Vector2`](Type.Vector2.md) <Badge type="tip" text="other" />

向量与三维矩阵乘法，默认向量第三位为 1。


::: warning Precautions

如果 outer 不为空, 返回 outer,否则返回一个新的 Matrix3x3 对象, 建议传入 outer 来减少 new 对象且 outer 不能为 null/undefined

:::

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `a` | [`Matrix3x3`](Type.Matrix3x3.md) | 三维矩阵 |
| `b` | [`Vector2`](Type.Vector2.md) | 二维向量 |
| `outer?` | [`Vector2`](Type.Vector2.md) | 被写入的二维向量 default:null |

#### Returns

[`Vector2`](Type.Vector2.md)

变换后的二维向量

___

### transpose <Score text="transpose" /> 

• `Static` **transpose**(`a`, `outer?`): [`Matrix3x3`](Type.Matrix3x3.md) <Badge type="tip" text="other" />

将目标矩阵变为转置矩阵


::: warning Precautions

如果 outer 不为空, 返回 outer,否则返回一个新的 Matrix3x3 对象, 建议传入 outer 来减少 new 对象且 outer 不能为 null/undefined

:::

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `a` | [`Matrix3x3`](Type.Matrix3x3.md) | 目标矩阵 |
| `outer?` | [`Matrix3x3`](Type.Matrix3x3.md) | 写入数据的矩阵 default:null |

#### Returns

[`Matrix3x3`](Type.Matrix3x3.md)

转置后的矩阵
