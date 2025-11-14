---
title: DeleteDevice
sidebar_position: 4
---

#### Description



#### Usage  

| Request parameters | POST                           |
| ------------------ | :----------------------------- |
| URL                | /iapi/v1/DeleteDevice?session= |
| data               | none                           |

#### Parameters

| Name  | Type | Parameter mandatory | Description |
| :---- | :--- | :------------------ | :---------- |
| token |      |                     |             |

#### Response

| Name | Type | Description |
| ---- | ---- | ----------- |
|      |      |             |

#### Examples

```
http://192.168.100.145:8080/iapi/v1/DeleteDevice?session=c1782caf-b670-42d8-ba90-2244d0b0ee83
```

```
data:
{
 "token": "0001"
}

response:
{
    "code": "HPRO_CODE_OK",
    "msg": "Success"
}
```