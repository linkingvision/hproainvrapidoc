---
title: DeleteObjPartition
sidebar_position: 11
---

#### Description



#### Usage  

| Request parameters | POST                                 |
| ------------------ | :----------------------------------- |
| URL                | /iapi/v1/DeleteObjPartition?session= |
| data               | none                                 |

#### Parameters

| Name       | Type | Parameter mandatory | Description |
| :--------- | :--- | :------------------ | :---------- |
| index      |      |                     |             |
| mountpoint |      |                     |             |

#### Response

| Name | Type | Description |
| ---- | ---- | ----------- |
|      |      |             |

#### Examples

```
https://192.168.100.161:16445/iapi/v1/DeleteObjPartition?session=c1782caf-b670-42d8-ba90-2244d0b0ee83
```

```
data:
{
 "index": 1,
 "mountpoint": "C:"
}

response:
{
    "code": "HPRO_CODE_OK",
    "msg": "Success"
}
```