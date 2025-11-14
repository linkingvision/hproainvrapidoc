---
slug: /
title: Login
sidebar_position: 1
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

```
data:
{
 "username": "admin",
 "nonceKey": "4d3e2fcf-1031-40d1-a11b-a7a234d8de11",
 "digestAlgorithm": "HPRO_DIGEST_ALGO_MD5", 
 "password": "9b61a2136443d798e098402a79a76c2d"
}

reponse:
{
    "code": "HPRO_CODE_OK",
    "msg": "Success",
    "result": {
        "nonce": "5c3846c4-0b86-4d03-8c81-c6441a7fa241",
        "realm": "hproainvr.com",
        "digestAlgorithm": [
            "HPRO_DIGEST_ALGO_MD5",
            "HPRO_DIGEST_ALGO_SHA256"
        ],
        "nonceKey": "eabab8eb-23d8-4632-8aaf-16d1e4f606b3"
    }
}
```