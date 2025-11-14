---
title: GET MetaStorage
sidebar_position: 7
---

#### Description



#### Usage  

| Request parameters | GET                           |
| ------------------ | :---------------------------- |
| URL                | /iapi/v1/MetaStorage?session= |
| data               | none                          |

#### Parameters

| Name    | Type | Parameter mandatory | Description |
| :------ | :--- | :------------------ | :---------- |
| session |      |                     |             |

#### Response

| Name | Type | Description |
| ---- | ---- | ----------- |
|      |      |             |

#### Examples

```
http://192.168.100.145:8080/iapi/v1/MetaStorage?session=c1782caf-b670-42d8-ba90-2244d0b0ee83
```

```
response:
{
    "code": "HPRO_CODE_OK",
    "msg": "Success",
    "result": {
        "bEnableMetaStorage": true,
        "strMetaPartitionDevice": "D:",
        "strMetaPartitionMountpoint": "D:",
        "nMetaRetentionInDay": 30
    }
}
```