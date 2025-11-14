---
title: GET SchedRecordConfig
sidebar_position: 2
---

#### Description



#### Usage  

| Request parameters | GET                                 |
| ------------------ | :---------------------------------- |
| URL                | /iapi/v1/SchedRecordConfig?session= |
| data               | none                                |

#### Parameters

| Name    | Type | Parameter mandatory | Description |
| :------ | :--- | :------------------ | :---------- |
| session |      |                     |             |
| token   |      |                     |             |

#### Response

| Name | Type | Description |
| ---- | ---- | ----------- |
|      |      |             |

#### Examples

```
https://192.168.100.161:16445/iapi/v1/SchedRecordConfig?session=c1782caf-b670-42d8-ba90-2244d0b0ee83&token=002a--00100
```

```
response:
{
    "code": "HPRO_CODE_OK",
    "msg": "Success",
    "result": {
        "metaEnable": false
    }
}
```