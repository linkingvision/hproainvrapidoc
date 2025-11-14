---
title: GetNonce
sidebar_position: 2
---

#### Description



#### Usage  

| Request parameters | GET               |
| ------------------ | :---------------- |
| URL                | /iapi/v1/GetNonce |
| data               | none              |

#### Parameters

| Name | Type | Parameter mandatory | Description |
| :--- | :--- | :------------------ | :---------- |
| none | none | none                | none        |

#### Response

| Name | Type | Description |
| ---- | ---- | ----------- |
|      |      |             |

#### Examples

```
http://192.168.100.145:8080/iapi/v1/
```

```
response:
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