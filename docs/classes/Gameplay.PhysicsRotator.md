[Gameplay](../modules/Gameplay.Gameplay.md) / PhysicsRotator

# PhysicsRotator <Badge type="tip" text="Class" /> <Score text="PhysicsRotator" />

**`Description`**

旋转轴

## Hierarchy

- [`GameObject`](Gameplay.GameObject.md)

  ↳ **`PhysicsRotator`**

## Table of contents

| Properties |
| :-----|
| **[onRotationStart](Gameplay.PhysicsRotator.md#onrotationstart)**: [`MulticastDelegateInterface`](../interfaces/Type.MulticastDelegateInterface.md)<() => `void`\> <br> 旋转轴开始事件|
| **[onRotationStop](Gameplay.PhysicsRotator.md#onrotationstop)**: [`MulticastDelegateInterface`](../interfaces/Type.MulticastDelegateInterface.md)<() => `void`\> <br> 旋转轴停止事件|

| Accessors |
| :-----|
| **[limitAngle](Gameplay.PhysicsRotator.md#limitangle)**(): `number` <br> 获取最大可旋转角度|
| **[limitEnable](Gameplay.PhysicsRotator.md#limitenable)**(): `boolean` <br> 获取是否开启约束旋转角度|
| **[limitType](Gameplay.PhysicsRotator.md#limittype)**(): [`AxisType`](../enums/Gameplay.AxisType.md) <br> 获取旋转轴限制类型|
| **[maxRotationalAngularVelocity](Gameplay.PhysicsRotator.md#maxrotationalangularvelocity)**(): `number` <br> 最大旋转角速度Get|
| **[physicsEnable](Gameplay.PhysicsRotator.md#physicsenable)**(): `boolean` <br> 获取是否启用物理旋转|
| **[recoveryStrength](Gameplay.PhysicsRotator.md#recoverystrength)**(): `number` <br> 获取回复强度|
| **[rotationalAngularAcceleration](Gameplay.PhysicsRotator.md#rotationalangularacceleration)**(): `number` <br> 旋转角加速度Get|
| **[rotationalAngularVelocity](Gameplay.PhysicsRotator.md#rotationalangularvelocity)**(): `number` <br> 旋转角速度Get|


::: details 点击查看继承
| Accessors |
| :-----|
| **[forwardVector](Gameplay.GameObject.md#forwardvector)**(): [`Vector`](Type.Vector.md) <br> 获取当前物体的向前向量|
| **[guid](Gameplay.GameObject.md#guid)**(): `string` <br> 获取对象的GUID（唯一标识一个对象的字符串）。|
| **[lockStatus](Gameplay.GameObject.md#lockstatus)**(): `boolean` <br> 获取对象是否锁定|
| **[name](Gameplay.GameObject.md#name)**(): `string` <br> 返回当前物体名称|
| **[netStatus](Gameplay.GameObject.md#netstatus)**(): [`NetStatus`](../enums/Type.NetStatus.md) <br> 获取当前物体同步状态|
| **[parent](Gameplay.GameObject.md#parent)**(): `GameObject` <br> 获取当前父物体|
| **[relativeLocation](Gameplay.GameObject.md#relativelocation)**(): [`Vector`](Type.Vector.md) <br> 获取相对位置|
| **[relativeRotation](Gameplay.GameObject.md#relativerotation)**(): [`Rotation`](Type.Rotation.md) <br> 获取相对旋转|
| **[relativeScale](Gameplay.GameObject.md#relativescale)**(): [`Vector`](Type.Vector.md) <br> 获取相对缩放|
| **[rightVector](Gameplay.GameObject.md#rightvector)**(): [`Vector`](Type.Vector.md) <br> 获取当前物体的向右向量|
| **[staticStatus](Gameplay.GameObject.md#staticstatus)**(): `boolean` <br> 获取对象是否静态|
| **[tag](Gameplay.GameObject.md#tag)**(): `string` <br> 获取当前物体的Tag|
| **[transform](Gameplay.GameObject.md#transform)**(): [`Transform`](Type.Transform.md) <br> 返回当前物体transform|
| **[upVector](Gameplay.GameObject.md#upvector)**(): [`Vector`](Type.Vector.md) <br> 获取当前物体的向上向量|
| **[useUpdate](Gameplay.GameObject.md#useupdate)**(): `boolean` <br> 获取对象是否使用更新|
| **[visible](Gameplay.GameObject.md#visible)**(): `boolean` <br> since:v0.20.0 reason:api重构 replacement:getVisibility()|
| **[worldLocation](Gameplay.GameObject.md#worldlocation)**(): [`Vector`](Type.Vector.md) <br> 获取物体的世界坐标|
| **[worldRotation](Gameplay.GameObject.md#worldrotation)**(): [`Rotation`](Type.Rotation.md) <br> 获取物体的世界旋转|
| **[worldScale](Gameplay.GameObject.md#worldscale)**(): [`Vector`](Type.Vector.md) <br> 获取物体的世界缩放|
:::


| Methods |
| :-----|
| **[getConstraintTargetGUID](Gameplay.PhysicsRotator.md#getconstrainttargetguid)**(): `string` <br> 获取约束对象GUID|
| **[reverse](Gameplay.PhysicsRotator.md#reverse)**(): `void` <br> 激活旋转轴非物理旋转，此时会触发OnRotationRun代理|
| **[setConstraintTargetByGUID](Gameplay.PhysicsRotator.md#setconstrainttargetbyguid)**(`string`): `void` <br> 设置约束对象GUID|
| **[start](Gameplay.PhysicsRotator.md#start)**(): `void` <br> Running|
| **[stop](Gameplay.PhysicsRotator.md#stop)**(): `void` <br> 停止旋转轴非物理旋转，此时会触发OnRotationStop代理|


::: details 点击查看继承
| Methods |
| :-----|
| **[addDestroyCallback](Gameplay.GameObject.md#adddestroycallback)**((...`arg`: `unknown`[]) => `void`): `void` <br> 添加物体Destroy事件回调|
| **[asyncGetScriptByName](Gameplay.GameObject.md#asyncgetscriptbyname)**(`string`): `Promise`<`Script`\> <br> 异步获得当前物体下的指定脚本 客户端不维系父子关系|
| **[attachToGameObject](Gameplay.GameObject.md#attachtogameobject)**(`GameObject`): `void` <br> 将物体附着到指定物体上|
| **[clone](Gameplay.GameObject.md#clone)**(`boolean`): `GameObject` <br> 复制对象|
| **[deleteDestroyCallback](Gameplay.GameObject.md#deletedestroycallback)**((...`arg`: `unknown`[]) => `void`): `void` <br> 移除物体Destroy事件回调|
| **[destroy](Gameplay.GameObject.md#destroy)**(): `void` <br> 删除对象|
| **[detachFromGameObject](Gameplay.GameObject.md#detachfromgameobject)**(): `void` <br> 将此物体与当前附着的物体分离|
| **[getBoundingBoxSize](Gameplay.GameObject.md#getboundingboxsize)**(`boolean`, `boolean`, [`Vector`](Type.Vector.md)): [`Vector`](Type.Vector.md) <br> 获取物体包围盒大小|
| **[getBounds](Gameplay.GameObject.md#getbounds)**(`boolean`, [`Vector`](Type.Vector.md), [`Vector`](Type.Vector.md), `boolean`): `void` <br> 获取GameObject边界|
| **[getChildByGuid](Gameplay.GameObject.md#getchildbyguid)**(`string`): `GameObject` <br> 根据GUID查找子物体|
| **[getChildByName](Gameplay.GameObject.md#getchildbyname)**(`string`): `GameObject` <br> 根据名称查找子物体|
| **[getChildren](Gameplay.GameObject.md#getchildren)**(): `GameObject`[] <br> 获取Children，客户端不维系父子关系。推荐使用Find替代|
| **[getChildrenBoxCenter](Gameplay.GameObject.md#getchildrenboxcenter)**([`Vector`](Type.Vector.md)): [`Vector`](Type.Vector.md) <br> 获取所有子对象包围盒中心点(不包含父对象,父对象不可用返回[0,0,0])|
| **[getCollision](Gameplay.GameObject.md#getcollision)**(): [`PropertyStatus`](../enums/Type.PropertyStatus.md) \| [`CollisionStatus`](../enums/Type.CollisionStatus.md) <br> 返回碰撞状态|
| **[getForwardVector](Gameplay.GameObject.md#getforwardvector)**([`Vector`](Type.Vector.md)): [`Vector`](Type.Vector.md) <br> 获取当前物体的向前向量|
| **[getRelativeLocation](Gameplay.GameObject.md#getrelativelocation)**([`Vector`](Type.Vector.md)): [`Vector`](Type.Vector.md) <br> 获取相对位置|
| **[getRelativeRotation](Gameplay.GameObject.md#getrelativerotation)**([`Rotation`](Type.Rotation.md)): [`Rotation`](Type.Rotation.md) <br> 获取相对旋转|
| **[getRelativeScale](Gameplay.GameObject.md#getrelativescale)**([`Vector`](Type.Vector.md)): [`Vector`](Type.Vector.md) <br> 获取相对缩放|
| **[getRightVector](Gameplay.GameObject.md#getrightvector)**([`Vector`](Type.Vector.md)): [`Vector`](Type.Vector.md) <br> 获取当前物体的向右向量|
| **[getScriptByGuid](Gameplay.GameObject.md#getscriptbyguid)**(`string`): `Script` <br> 获得当前物体下的指定脚本 客户端不维系父子关系 推荐使用Find替代|
| **[getScriptByName](Gameplay.GameObject.md#getscriptbyname)**(`string`): `Script` <br> 获得当前物体下的指定脚本 客户端不维系父子关系 推荐使用Find替代|
| **[getScripts](Gameplay.GameObject.md#getscripts)**(): `Script`[] <br> 获得当前物体下的所有脚本 客户端不维系父子关系 推荐使用Find替代|
| **[getSourceAssetGuid](Gameplay.GameObject.md#getsourceassetguid)**(): `string` <br> 获取当前物体使用资源的GUID|
| **[getTransform](Gameplay.GameObject.md#gettransform)**([`Transform`](Type.Transform.md)): [`Transform`](Type.Transform.md) <br> 返回当前物体Transform|
| **[getUpVector](Gameplay.GameObject.md#getupvector)**([`Vector`](Type.Vector.md)): [`Vector`](Type.Vector.md) <br> 获取当前物体的向上向量|
| **[getVisibility](Gameplay.GameObject.md#getvisibility)**(): `boolean` <br> 获取GameObject是否被显示|
| **[getWorldLocation](Gameplay.GameObject.md#getworldlocation)**([`Vector`](Type.Vector.md)): [`Vector`](Type.Vector.md) <br> 获取物体的世界坐标|
| **[getWorldRotation](Gameplay.GameObject.md#getworldrotation)**([`Rotation`](Type.Rotation.md)): [`Rotation`](Type.Rotation.md) <br> 获取物体的世界旋转|
| **[getWorldScale](Gameplay.GameObject.md#getworldscale)**([`Vector`](Type.Vector.md)): [`Vector`](Type.Vector.md) <br> 获取物体的世界缩放|
| **[isRunningClient](Gameplay.GameObject.md#isrunningclient)**(): `boolean` <br> 是否为客户端|
| **[onDestroy](Gameplay.GameObject.md#ondestroy)**(): `void` <br> 周期函数 被销毁时调用|
| **[onStart](Gameplay.GameObject.md#onstart)**(): `void` <br> 周期函数 脚本开始执行时调用|
| **[onUpdate](Gameplay.GameObject.md#onupdate)**(`number`): `void` <br> 周期函数 useUpdate 设置为 true 后,每帧被执行,设置为false,不会执行|
| **[ready](Gameplay.GameObject.md#ready)**(): `Promise`<[`GameObject`](Gameplay.GameObject.md)\> <br> GameObject准备好后返回|
| **[setCollision](Gameplay.GameObject.md#setcollision)**([`PropertyStatus`](../enums/Type.PropertyStatus.md) \, `boolean`): `void` <br> 设置碰撞状态|
| **[setLocationAndRotation](Gameplay.GameObject.md#setlocationandrotation)**([`Vector`](Type.Vector.md), [`Rotation`](Type.Rotation.md)): `void` <br> 同时设置物体的世界位置与旋转|
| **[setRelativeLocation](Gameplay.GameObject.md#setrelativelocation)**([`Vector`](Type.Vector.md)): `void` <br> 设置相对位置|
| **[setRelativeRotation](Gameplay.GameObject.md#setrelativerotation)**([`Rotation`](Type.Rotation.md)): `void` <br> 设置相对旋转|
| **[setRelativeScale](Gameplay.GameObject.md#setrelativescale)**([`Vector`](Type.Vector.md)): `void` <br> 设置相对缩放|
| **[setTransform](Gameplay.GameObject.md#settransform)**([`Transform`](Type.Transform.md)): `void` <br> 设置当前物体transform|
| **[setVisibility](Gameplay.GameObject.md#setvisibility)**([`PropertyStatus`](../enums/Type.PropertyStatus.md), `boolean`): `void` <br> 设置GameObject是否被显示|
| **[setWorldLocation](Gameplay.GameObject.md#setworldlocation)**([`Vector`](Type.Vector.md)): `void` <br> 设置物体的世界坐标|
| **[setWorldRotation](Gameplay.GameObject.md#setworldrotation)**([`Rotation`](Type.Rotation.md)): `void` <br> 设置物体的世界旋转|
| **[setWorldScale](Gameplay.GameObject.md#setworldscale)**([`Vector`](Type.Vector.md)): `void` <br> 设置物体的世界缩放|
| **[asyncFind](Gameplay.GameObject.md#asyncfind)**(`string`): `Promise`<`GameObject`\> <br> 通过GUID异步查找GameObject,默认是五秒,可以通过 `core.setGlobalAsyncOverTime(5000);|
| **[asyncSpawnGameObject](Gameplay.GameObject.md#asyncspawngameobject)**(`string`, `boolean`): `Promise`<`GameObject`\> <br> 异步构造一个 GameObject 资源不存在会先去下载资源再去创建|
| **[find](Gameplay.GameObject.md#find)**(`string`): `GameObject` <br> 通过GUID查找GameObject|
| **[findGameObjectByTag](Gameplay.GameObject.md#findgameobjectbytag)**(`string`): `GameObject`[] <br> 通过自定义Tag获取GameObject|
| **[getGameObjectByName](Gameplay.GameObject.md#getgameobjectbyname)**(`string`): `GameObject` <br> 通过名字查找物体|
| **[getGameObjectsByName](Gameplay.GameObject.md#getgameobjectsbyname)**(`string`): `GameObject`[] <br> 通过名字查找物体|
| **[spawnGameObject](Gameplay.GameObject.md#spawngameobject)**(`string`, `boolean`): `GameObject` <br> 构造一个 GameObject|
:::


## Properties

### onRotationStart <Score text="onRotationStart" /> 

• **onRotationStart**: [`MulticastDelegateInterface`](../interfaces/Type.MulticastDelegateInterface.md)<() => `void`\>

**`Description`**

旋转轴开始事件

___

### onRotationStop <Score text="onRotationStop" /> 

• **onRotationStop**: [`MulticastDelegateInterface`](../interfaces/Type.MulticastDelegateInterface.md)<() => `void`\>

**`Description`**

旋转轴停止事件

## Accessors

### limitAngle <Score text="limitAngle" /> 

• `get` **limitAngle**(): `number`

**`Description`**

获取最大可旋转角度

#### Returns

`number`

最大可旋转角度

• `set` **limitAngle**(`value`): `void`

**`Description`**

设置最大可旋转角度

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `value` | `number` | 最大可旋转角度 |


___

### limitEnable <Score text="limitEnable" /> 

• `get` **limitEnable**(): `boolean`

**`Description`**

获取是否开启约束旋转角度

#### Returns

`boolean`

是否开启约束旋转角度

• `set` **limitEnable**(`value`): `void`

**`Description`**

设置是否开启约束旋转角度

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `value` | `boolean` | 是否开启约束旋转角度 |


___

### limitType <Score text="limitType" /> 

• `get` **limitType**(): [`AxisType`](../enums/Gameplay.AxisType.md) <Badge type="tip" text="other" />

**`Description`**

获取旋转轴限制类型


#### Returns

[`AxisType`](../enums/Gameplay.AxisType.md)

旋转轴限制类型

• `set` **limitType**(`value`): `void` <Badge type="tip" text="other" />

**`Description`**

设置旋转轴限制类型


#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `value` | [`AxisType`](../enums/Gameplay.AxisType.md) | 旋转轴限制类型 |



### maxRotationalAngularVelocity <Score text="maxRotationalAngularVelocity" /> 

• `get` **maxRotationalAngularVelocity**(): `number` <Badge type="tip" text="other" />

**`Description`**

最大旋转角速度Get


#### Returns

`number`

最大旋转角速度

• `set` **maxRotationalAngularVelocity**(`value`): `void` <Badge type="tip" text="other" />

**`Description`**

最大旋转角速度Set


#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `value` | `number` | 最大旋转角速度 |



### physicsEnable <Score text="physicsEnable" /> 

• `get` **physicsEnable**(): `boolean`

**`Description`**

获取是否启用物理旋转

#### Returns

`boolean`

是否启用物理旋转

• `set` **physicsEnable**(`value`): `void`

**`Description`**

设置是否启用物理旋转

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `value` | `boolean` | 是否启用物理旋转 |


___

### recoveryStrength <Score text="recoveryStrength" /> 

• `get` **recoveryStrength**(): `number`

**`Description`**

获取回复强度

#### Returns

`number`

回复强度

• `set` **recoveryStrength**(`value`): `void`

**`Description`**

设置回复强度

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `value` | `number` | 回复强度 |



### rotationalAngularAcceleration <Score text="rotationalAngularAcceleration" /> 

• `get` **rotationalAngularAcceleration**(): `number` <Badge type="tip" text="other" />

**`Description`**

旋转角加速度Get


#### Returns

`number`

角加速度

• `set` **rotationalAngularAcceleration**(`value`): `void` <Badge type="tip" text="other" />

**`Description`**

旋转角加速度Set


#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `value` | `number` | 角加速度 |


___

### rotationalAngularVelocity <Score text="rotationalAngularVelocity" /> 

• `get` **rotationalAngularVelocity**(): `number` <Badge type="tip" text="other" />

**`Description`**

旋转角速度Get


#### Returns

`number`

角速度

• `set` **rotationalAngularVelocity**(`value`): `void` <Badge type="tip" text="other" />

**`Description`**

旋转角速度Set


#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `value` | `number` | 角速度 |



## Methods

### getConstraintTargetGUID <Score text="getConstraintTargetGUID" /> 

▸ **getConstraintTargetGUID**(): `string` <Badge type="tip" text="other" />

**`Description`**

获取约束对象GUID


#### Returns

`string`

对象GUID


### reverse <Score text="reverse" /> 

▸ **reverse**(): `void` <Badge type="tip" text="other" />

**`Description`**

激活旋转轴非物理旋转，此时会触发OnRotationRun代理




### setConstraintTargetByGUID <Score text="setConstraintTargetByGUID" /> 

▸ **setConstraintTargetByGUID**(`value`): `void` <Badge type="tip" text="other" />

**`Description`**

设置约束对象GUID


#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `value` | `string` | 对象GUID |



### start <Score text="start" /> 

▸ **start**(): `void` <Badge type="tip" text="other" />

**`Description`**

Running



___

### stop <Score text="stop" /> 

▸ **stop**(): `void` <Badge type="tip" text="other" />

**`Description`**

停止旋转轴非物理旋转，此时会触发OnRotationStop代理

