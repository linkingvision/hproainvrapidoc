---
title: UpdateUser
sidebar_position: 5
---

#### Description



#### Usage  

| Request parameters | POST                         |
| ------------------ | :--------------------------- |
| URL                | /iapi/v1/UpdateUser?session= |
| data               | none                         |

#### Parameters

| Name        | Type | Parameter mandatory | Description |
| :---------- | :--- | :------------------ | :---------- |
| username    |      |                     |             |
| oldPassword |      |                     |             |
| newPassword |      |                     |             |

#### Response

| Name | Type | Description |
| ---- | ---- | ----------- |
|      |      |             |

#### Examples

```
https://192.168.100.161:16445/iapi/v1/UpdateUser?session=c1782caf-b670-42d8-ba90-2244d0b0ee83
```

```
data:
{
 "username": "admin",
 "oldPassword": "Vision@168",
 "newPassword": "Vision@1680"
}

response:
{
    "code": "HPRO_CODE_OK",
    "msg": "Success"
}
```