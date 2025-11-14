---
title: GetDevice
sidebar_position: 2
---

#### Description



#### Usage  

| Request parameters | POST                        |
| ------------------ | :-------------------------- |
| URL                | /iapi/v1/GetDevice?session= |
| data               | none                        |

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
http://192.168.100.145:8080/iapi/v1/GetDevice?session=c1782caf-b670-42d8-ba90-2244d0b0ee83
```

```
data:
{
 "token": "002a--00100"
}

response:
{
    "code": "HPRO_CODE_FAILED",
    "msg": "Failed",
    "result": {
        "dev": []
    }
}
```