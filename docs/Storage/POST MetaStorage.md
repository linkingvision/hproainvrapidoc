---
title: POST MetaStorage
sidebar_position: 8
---

#### Description



#### Usage  

| Request parameters | POST                          |
| ------------------ | :---------------------------- |
| URL                | /iapi/v1/MetaStorage?session= |
| data               | none                          |

#### Parameters

| Name                    | Type | Parameter mandatory | Description |
| :---------------------- | :--- | :------------------ | :---------- |
| enableMetaStorage       |      |                     |             |
| metaPartitionDevice     |      |                     |             |
| metaPartitionMountpoint |      |                     |             |
| metaRetentionInDay      |      |                     |             |

#### Response

| Name | Type | Description |
| ---- | ---- | ----------- |
|      |      |             |

#### Examples

```
http://192.168.100.145:8080/iapi/v1/MetaStorage?session=c1782caf-b670-42d8-ba90-2244d0b0ee83
```

```
data:
{
  "enableMetaStorage": true,
  "metaPartitionDevice": "C:",
  "metaPartitionMountpoint": "C:",
  "metaRetentionInDay": 30
}

response:
{
    "code": "HPRO_CODE_OK",
    "msg": "Success"
}
```