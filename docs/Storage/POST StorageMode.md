---
title: POST StorageMode
sidebar_position: 6
---

#### Description



#### Usage  

| Request parameters | POST                          |
| ------------------ | :---------------------------- |
| URL                | /iapi/v1/StorageMode?session= |
| data               | none                          |

#### Parameters

| Name | Type | Parameter mandatory | Description |
| :--- | :--- | :------------------ | :---------- |
| mode |      |                     |             |

#### Response

| Name | Type | Description |
| ---- | ---- | ----------- |
|      |      |             |

#### Examples

```
https://192.168.100.161:16445/iapi/v1/StorageMode?session=c1782caf-b670-42d8-ba90-2244d0b0ee83
```

```
data:
{
  "mode": "HPRO_STORAGE_MODE_OBJECT"
}

response:
{
    "code": "HPRO_CODE_OK",
    "msg": "Success"
}
```