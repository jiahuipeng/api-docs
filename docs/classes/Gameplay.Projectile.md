[Gameplay](../modules/Gameplay.Gameplay.md) / Projectile

# Projectile <Badge type="tip" text="Class" /> <Score text="Projectile" />

投掷物逻辑对象

## Hierarchy

- [`GameObject`](Gameplay.GameObject.md)

  ↳ **`Projectile`**

## Table of contents

| Properties |
| :-----|
| **[onProjectileBeginOverlap](Gameplay.Projectile.md#onprojectilebeginoverlap)**: [`MulticastDelegateInterface`](../interfaces/Type.MulticastDelegateInterface.md)<(`hitGameObject`: `GameObject`, `otherBodyIndex`: `number`, `fromSweep`: `boolean`, `sweepResult`: [`HitResult`](Gameplay.HitResult.md)) => `void`\> <br> 当投掷物与其他物体开始接触重叠时执行绑定函数|
| **[onProjectileBounce](Gameplay.Projectile.md#onprojectilebounce)**: [`MulticastDelegateInterface`](../interfaces/Type.MulticastDelegateInterface.md)<(`impactResult`: [`HitResult`](Gameplay.HitResult.md), `impactVelocity`: [`Vector`](Type.Vector.md), `bounceNum`: `number`) => `void`\> <br> 当投掷物发生弹跳时执行绑定函数|
| **[onProjectileEndOverlap](Gameplay.Projectile.md#onprojectileendoverlap)**: [`MulticastDelegateInterface`](../interfaces/Type.MulticastDelegateInterface.md)<(`hitGameObject`: `GameObject`, `otherBodyIndex`: `number`) => `void`\> <br> 当投掷物与其他物体结束接触重叠时执行绑定函数|
| **[onProjectileHit](Gameplay.Projectile.md#onprojectilehit)**: [`MulticastDelegateInterface`](../interfaces/Type.MulticastDelegateInterface.md)<(`hitGameObject`: `GameObject`, `normalImpulse`: [`Vector`](Type.Vector.md), `hitResult`: [`HitResult`](Gameplay.HitResult.md)) => `void`\> <br> 当投掷物发生碰撞时执行绑定函数|
| **[onProjectileInterrupt](Gameplay.Projectile.md#onprojectileinterrupt)**: [`MulticastDelegateInterface`](../interfaces/Type.MulticastDelegateInterface.md)<() => `void`\> <br> 当投掷物自动终止时执行绑定函数|

| Accessors |
| :-----|
| **[collisionLength](Gameplay.Projectile.md#collisionlength)**(): `number` <br> 包围盒高度|
| **[collisionRadius](Gameplay.Projectile.md#collisionradius)**(): `number` <br> 包围盒半径|
| **[flyRange](Gameplay.Projectile.md#flyrange)**(): `number` <br> 飞行距离|
| **[gravityScale](Gameplay.Projectile.md#gravityscale)**(): `number` <br> 重力缩放值|
| **[initialSpeed](Gameplay.Projectile.md#initialspeed)**(): `number` <br> 初始速度|
| **[maxBounceCount](Gameplay.Projectile.md#maxbouncecount)**(): `number` <br> 最大弹跳|
| **[simulatePhysics](Gameplay.Projectile.md#simulatephysics)**(): `boolean` <br> 模拟物理|


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
| **[bindPlayer](Gameplay.Projectile.md#bindplayer)**([`Player`](Gameplay.Player.md)): `boolean` <br> 绑定玩家，需要使用该接口在Server绑定具体的Player|
| **[init](Gameplay.Projectile.md#init)**(`number`, `number`, `number`, `number`, `number`, `boolean`): `void` <br> 子弹初始化,只有在客户端调用时会自动绑定当前角色|
| **[launch](Gameplay.Projectile.md#launch)**(): `void` <br> 发射投掷物，将目前射程清零|
| **[pause](Gameplay.Projectile.md#pause)**(): `void` <br> 暂停投掷物|
| **[resume](Gameplay.Projectile.md#resume)**(): `void` <br> 唤醒投掷物|


::: details 点击查看继承
| Methods |
| :-----|
| **[addDestroyCallback](Gameplay.GameObject.md#adddestroycallback)**((...`arg`: `unknown`[]) => `void`): `void` <br> 添加物体Destroy事件回调|
| **[asyncGetScriptByName](Gameplay.GameObject.md#asyncgetscriptbyname)**(`string`): `Promise`<`Script`\> <br> 异步获得当前物体下的指定脚本 客户端不维系父子关系|
| **[attachComponent](Gameplay.GameObject.md#attachcomponent)**(`Component`, `boolean`): `boolean` <br> 附加组件|
| **[attachToGameObject](Gameplay.GameObject.md#attachtogameobject)**(`GameObject`): `void` <br> 将物体附着到指定物体上|
| **[clone](Gameplay.GameObject.md#clone)**(`boolean`): `GameObject` <br> 复制对象|
| **[deleteDestroyCallback](Gameplay.GameObject.md#deletedestroycallback)**((...`arg`: `unknown`[]) => `void`): `void` <br> 移除物体Destroy事件回调|
| **[destroy](Gameplay.GameObject.md#destroy)**(): `void` <br> 删除对象|
| **[detachComponent](Gameplay.GameObject.md#detachcomponent)**(`string` \): `void` <br> 移除组件|
| **[detachFromGameObject](Gameplay.GameObject.md#detachfromgameobject)**(): `void` <br> 将此物体与当前附着的物体分离|
| **[getBoundingBoxSize](Gameplay.GameObject.md#getboundingboxsize)**(`boolean`, `boolean`, [`Vector`](Type.Vector.md)): [`Vector`](Type.Vector.md) <br> 获取物体包围盒大小|
| **[getBounds](Gameplay.GameObject.md#getbounds)**(`boolean`, [`Vector`](Type.Vector.md), [`Vector`](Type.Vector.md), `boolean`): `void` <br> 获取GameObject边界|
| **[getChildByGuid](Gameplay.GameObject.md#getchildbyguid)**(`string`): `undefined` \| `GameObject` <br> 根据GUID查找子物体|
| **[getChildByName](Gameplay.GameObject.md#getchildbyname)**(`string`): `undefined` \| `GameObject` <br> 根据名称查找子物体|
| **[getChildren](Gameplay.GameObject.md#getchildren)**(): `undefined` \| `GameObject`[] <br> 获取Children，客户端不维系父子关系。推荐使用Find替代|
| **[getChildrenBoxCenter](Gameplay.GameObject.md#getchildrenboxcenter)**([`Vector`](Type.Vector.md)): [`Vector`](Type.Vector.md) <br> 获取所有子对象包围盒中心点(不包含父对象,父对象不可用返回[0,0,0])|
| **[getCollision](Gameplay.GameObject.md#getcollision)**(): [`PropertyStatus`](../enums/Type.PropertyStatus.md) \| [`CollisionStatus`](../enums/Type.CollisionStatus.md) <br> 返回碰撞状态|
| **[getForwardVector](Gameplay.GameObject.md#getforwardvector)**([`Vector`](Type.Vector.md)): [`Vector`](Type.Vector.md) <br> 获取当前物体的向前向量|
| **[getRelativeLocation](Gameplay.GameObject.md#getrelativelocation)**([`Vector`](Type.Vector.md)): [`Vector`](Type.Vector.md) <br> 获取相对位置|
| **[getRelativeRotation](Gameplay.GameObject.md#getrelativerotation)**([`Rotation`](Type.Rotation.md)): [`Rotation`](Type.Rotation.md) <br> 获取相对旋转|
| **[getRelativeScale](Gameplay.GameObject.md#getrelativescale)**([`Vector`](Type.Vector.md)): [`Vector`](Type.Vector.md) <br> 获取相对缩放|
| **[getRightVector](Gameplay.GameObject.md#getrightvector)**([`Vector`](Type.Vector.md)): [`Vector`](Type.Vector.md) <br> 获取当前物体的向右向量|
| **[getScriptByGuid](Gameplay.GameObject.md#getscriptbyguid)**(`string`): `undefined` \| `Script` <br> 获得当前物体下的指定脚本 客户端不维系父子关系 推荐使用Find替代|
| **[getScriptByName](Gameplay.GameObject.md#getscriptbyname)**(`string`): `undefined` \| `Script` <br> 获得当前物体下的指定脚本 客户端不维系父子关系 推荐使用Find替代|
| **[getScripts](Gameplay.GameObject.md#getscripts)**(): `undefined` \| `Script`[] <br> 获得当前物体下的所有脚本 客户端不维系父子关系 推荐使用Find替代|
| **[getSourceAssetGuid](Gameplay.GameObject.md#getsourceassetguid)**(): `string` <br> 获取当前物体使用资源的GUID|
| **[getTransform](Gameplay.GameObject.md#gettransform)**([`Transform`](Type.Transform.md)): [`Transform`](Type.Transform.md) <br> 返回当前物体Transform|
| **[getUpVector](Gameplay.GameObject.md#getupvector)**([`Vector`](Type.Vector.md)): [`Vector`](Type.Vector.md) <br> 获取当前物体的向上向量|
| **[getVisibility](Gameplay.GameObject.md#getvisibility)**(): `boolean` <br> 获取GameObject是否被显示|
| **[getWorldLocation](Gameplay.GameObject.md#getworldlocation)**([`Vector`](Type.Vector.md)): [`Vector`](Type.Vector.md) <br> 获取物体的世界坐标|
| **[getWorldRotation](Gameplay.GameObject.md#getworldrotation)**([`Rotation`](Type.Rotation.md)): [`Rotation`](Type.Rotation.md) <br> 获取物体的世界旋转|
| **[getWorldScale](Gameplay.GameObject.md#getworldscale)**([`Vector`](Type.Vector.md)): [`Vector`](Type.Vector.md) <br> 获取物体的世界缩放|
| **[isRunningClient](Gameplay.GameObject.md#isrunningclient)**(): `boolean` <br> 是否为客户端|
| **[onDestroy](Gameplay.GameObject.md#ondestroy)**(): `void` <br> 周期函数 被销毁时调用|
| **[onReplicated](Gameplay.GameObject.md#onreplicated)**(`string`, `unknown`, `unknown`): `void` <br> 属性被同步事件 ClientOnly|
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
| **[getGameObjectByName](Gameplay.GameObject.md#getgameobjectbyname)**(`string`): `undefined` \| `GameObject` <br> 通过名字查找物体|
| **[getGameObjectsByName](Gameplay.GameObject.md#getgameobjectsbyname)**(`string`): `GameObject`[] <br> 通过名字查找物体|
| **[spawnGameObject](Gameplay.GameObject.md#spawngameobject)**(`string`, `boolean`): `GameObject` <br> 构造一个 GameObject|
:::


## Properties

### onProjectileBeginOverlap <Score text="onProjectileBeginOverlap" /> 

• **onProjectileBeginOverlap**: [`MulticastDelegateInterface`](../interfaces/Type.MulticastDelegateInterface.md)<(`hitGameObject`: `GameObject`, `otherBodyIndex`: `number`, `fromSweep`: `boolean`, `sweepResult`: [`HitResult`](Gameplay.HitResult.md)) => `void`\>

当投掷物与其他物体开始接触重叠时执行绑定函数

___

### onProjectileBounce <Score text="onProjectileBounce" /> 

• **onProjectileBounce**: [`MulticastDelegateInterface`](../interfaces/Type.MulticastDelegateInterface.md)<(`impactResult`: [`HitResult`](Gameplay.HitResult.md), `impactVelocity`: [`Vector`](Type.Vector.md), `bounceNum`: `number`) => `void`\>

当投掷物发生弹跳时执行绑定函数

___

### onProjectileEndOverlap <Score text="onProjectileEndOverlap" /> 

• **onProjectileEndOverlap**: [`MulticastDelegateInterface`](../interfaces/Type.MulticastDelegateInterface.md)<(`hitGameObject`: `GameObject`, `otherBodyIndex`: `number`) => `void`\>

当投掷物与其他物体结束接触重叠时执行绑定函数

___

### onProjectileHit <Score text="onProjectileHit" /> 

• **onProjectileHit**: [`MulticastDelegateInterface`](../interfaces/Type.MulticastDelegateInterface.md)<(`hitGameObject`: `GameObject`, `normalImpulse`: [`Vector`](Type.Vector.md), `hitResult`: [`HitResult`](Gameplay.HitResult.md)) => `void`\>

当投掷物发生碰撞时执行绑定函数

___

### onProjectileInterrupt <Score text="onProjectileInterrupt" /> 

• **onProjectileInterrupt**: [`MulticastDelegateInterface`](../interfaces/Type.MulticastDelegateInterface.md)<() => `void`\>

当投掷物自动终止时执行绑定函数

## Accessors

### collisionLength <Score text="collisionLength" /> 

• `get` **collisionLength**(): `number`

包围盒高度

#### Returns

`number`

• `set` **collisionLength**(`length`): `void`

包围盒高度

#### Parameters

| Name | Type |
| :------ | :------ |
| `length` | `number` |


___

### collisionRadius <Score text="collisionRadius" /> 

• `get` **collisionRadius**(): `number`

包围盒半径

#### Returns

`number`

• `set` **collisionRadius**(`radius`): `void`

包围盒半径

#### Parameters

| Name | Type |
| :------ | :------ |
| `radius` | `number` |


___

### flyRange <Score text="flyRange" /> 

• `get` **flyRange**(): `number`

飞行距离

#### Returns

`number`

• `set` **flyRange**(`range`): `void`

飞行距离

#### Parameters

| Name | Type |
| :------ | :------ |
| `range` | `number` |



### gravityScale <Score text="gravityScale" /> 

• `get` **gravityScale**(): `number`

重力缩放值

#### Returns

`number`

• `set` **gravityScale**(`scale`): `void`

重力缩放值

#### Parameters

| Name | Type |
| :------ | :------ |
| `scale` | `number` |



### initialSpeed <Score text="initialSpeed" /> 

• `get` **initialSpeed**(): `number`

初始速度

#### Returns

`number`

• `set` **initialSpeed**(`value`): `void`

初始速度

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | `number` |



### maxBounceCount <Score text="maxBounceCount" /> 

• `get` **maxBounceCount**(): `number`

最大弹跳

#### Returns

`number`

• `set` **maxBounceCount**(`bounceCount`): `void`

最大弹跳

#### Parameters

| Name | Type |
| :------ | :------ |
| `bounceCount` | `number` |



### simulatePhysics <Score text="simulatePhysics" /> 

• `get` **simulatePhysics**(): `boolean`

模拟物理

#### Returns

`boolean`

• `set` **simulatePhysics**(`isSimulated`): `void`

模拟物理

#### Parameters

| Name | Type |
| :------ | :------ |
| `isSimulated` | `boolean` |



## Methods

### bindPlayer <Score text="bindPlayer" /> 

• **bindPlayer**(`player`): `boolean` <Badge type="tip" text="other" />

绑定玩家，需要使用该接口在Server绑定具体的Player

::: warning Precautions

单端调用即可，不需要重复调用。

:::

客户端调用自动同步至服务端

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `player` | [`Player`](Gameplay.Player.md) |  需要使用投掷物的角色 |

#### Returns

`boolean`

当有对内部玩家进行赋值时，返回 true


### init <Score text="init" /> 

• **init**(`Speed?`, `CollisionLength?`, `CollisionRadius?`, `FlyRange?`, `GravityScale?`, `SimulatePhysics?`): `void` <Badge type="tip" text="other" />

子弹初始化,只有在客户端调用时会自动绑定当前角色


#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `Speed?` | `number` |  初始速度 default: 1000 |
| `CollisionLength?` | `number` |  碰撞胶囊长度 default: 0.5 |
| `CollisionRadius?` | `number` |  碰撞胶囊半径 default: 0.5 |
| `FlyRange?` | `number` |  飞行范围 default: 10000 |
| `GravityScale?` | `number` |  重力设置 default: 0 |
| `SimulatePhysics?` | `boolean` |  是否模拟物理 default: false |



### launch <Score text="launch" /> 

• **launch**(): `void` <Badge type="tip" text="other" />

发射投掷物，将目前射程清零

::: warning Precautions

请先 bindPlayer 后再调用
在客户端调用时，如果已经调用过init同时更新了当前player，此函数在一定时间内调用会因RPC延时导致失败

:::



• **launch**(`fromLoc`, `toLoc`): `void` <Badge type="tip" text="other" />

发射投掷物，将目前射程清零

::: warning Precautions

- 请先 bindPlayer 后再调用
 - 在客户端调用时，如果已经调用过init同时更新了当前player，此函数在一定时间内调用会因RPC延时导致失败
 - 在关闭物理模拟时，会限制最大飞行距离为起点和终点之间的距离；开启物理后，将不限制距离，请注意及时手动停止

:::


#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `fromLoc` | [`Vector`](Type.Vector.md) |  发射点 |
| `toLoc` | [`Vector`](Type.Vector.md) |  目标点（开启物理，有重力时，投掷物呈抛物线运动，不保证能到达目标点） |



### pause <Score text="pause" /> 

• **pause**(): `void` <Badge type="tip" text="other" />

暂停投掷物




### resume <Score text="resume" /> 

• **resume**(): `void` <Badge type="tip" text="other" />

唤醒投掷物


