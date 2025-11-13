---
title: AddObjPartition
sidebar_position: 10
---

#### Description



#### Usage  

| Request parameters | POST                              |
| ------------------ | :-------------------------------- |
| URL                | /iapi/v1/AddObjPartition?session= |
| data               | none                              |

#### Parameters

| Name          | Type | Parameter mandatory | Description |
| :------------ | :--- | :------------------ | :---------- |
| part          |      |                     |             |
| nIndex        |      |                     |             |
| strDevice     |      |                     |             |
| strMountpoint |      |                     |             |
| update        |      |                     |             |

#### Response

| Name | Type | Description |
| ---- | ---- | ----------- |
|      |      |             |

#### Examples

```
http://192.168.100.145:8080/iapi/v1/AddObjPartition?session=c1782caf-b670-42d8-ba90-2244d0b0ee83
```

data:

```
{
  "part": 
​    {
​    "nIndex": 1,
​    "strDevice": "C:",
​    "strMountpoint": "C:"
​    },
  "update": false
}
```