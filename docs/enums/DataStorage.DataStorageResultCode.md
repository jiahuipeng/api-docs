[DataStorage](../modules/DataStorage.DataStorage.md) / DataStorageResultCode

# DataStorageResultCode <Badge type="tip" text="Enumeration" /> <Score text="DataStorageResultCode" />

数据储存返回代码

## Table of contents

| Enumeration Members |
| :-----|
| **[ExceededSizeLimit](DataStorage.DataStorageResultCode.md#exceededsizelimit)** = ``2`` <br> 数据保存失败：文件大小过大|
| **[Failure](DataStorage.DataStorageResultCode.md#failure)** = ``400`` <br> 未知错误失败|
| **[KeyValueError](DataStorage.DataStorageResultCode.md#keyvalueerror)** = ``1010`` <br> key或者Value格式错误|
| **[OnlyServerCall](DataStorage.DataStorageResultCode.md#onlyservercall)** = ``3`` <br> 非法调用 只可服务器端调用|
| **[RequestIntervalTooClose](DataStorage.DataStorageResultCode.md#requestintervaltooclose)** = ``423`` <br> 请求间隔错误|
| **[RequestTooFrequent](DataStorage.DataStorageResultCode.md#requesttoofrequent)** = ``424`` <br> 请求频率过高|
| **[Success](DataStorage.DataStorageResultCode.md#success)** = ``200`` <br> 操作成功|

## Enumeration Members

### ExceededSizeLimit <Score text="ExceededSizeLimit" /> 

• **ExceededSizeLimit** = ``2``

数据保存失败：文件大小过大

___

### Failure <Score text="Failure" /> 

• **Failure** = ``400``

未知错误失败

___

### KeyValueError <Score text="KeyValueError" /> 

• **KeyValueError** = ``1010``

key或者Value格式错误

___

### OnlyServerCall <Score text="OnlyServerCall" /> 

• **OnlyServerCall** = ``3``

非法调用 只可服务器端调用

___

### RequestIntervalTooClose <Score text="RequestIntervalTooClose" /> 

• **RequestIntervalTooClose** = ``423``

请求间隔错误

___

### RequestTooFrequent <Score text="RequestTooFrequent" /> 

• **RequestTooFrequent** = ``424``

请求频率过高

___

### Success <Score text="Success" /> 

• **Success** = ``200``

操作成功
