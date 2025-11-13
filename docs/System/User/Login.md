---
title: Login
sidebar_position: 2
---

#### Description



#### Usage  

| Request parameters | POST           |
| ------------------ | -------------- |
| URL                | /iapi/v1/Login |
| data               | none           |

#### Parameters

| Name            | Type | Parameter mandatory | Description |
| --------------- | ---- | ------------------- | ----------- |
| username        |      |                     |             |
| nonceKey        |      |                     |             |
| digestAlgorithm |      |                     |             |
| password        |      |                     |             |

#### Response

| Name | Type | Description |
| ---- | ---- | ----------- |
|      |      |             |

#### Examples

```
http://192.168.100.145:8080/iapi/v1/Login
```

data:
```
{
 "username": "admin",
 "nonceKey": "4d3e2fcf-1031-40d1-a11b-a7a234d8de11",
 "digestAlgorithm": "HPRO_DIGEST_ALGO_MD5", 
 "password": "9b61a2136443d798e098402a79a76c2d"
}
```