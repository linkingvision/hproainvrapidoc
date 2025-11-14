---
title: AddS3Bucket
sidebar_position: 13
---

#### Description



#### Usage  

| Request parameters | POST                         |
| ------------------ | :--------------------------- |
| URL                | iapi/v1/AddS3Bucket?session= |
| data               | none                         |

#### Parameters

| Name          | Type | Parameter mandatory | Description |
| :------------ | :--- | :------------------ | :---------- |
| part          |      |                     |             |
| nIndex        |      |                     |             |
| strAccessKey  |      |                     |             |
| strSecretKey  |      |                     |             |
| strRegionName |      |                     |             |
| strBucketName |      |                     |             |
| strEndpoint   |      |                     |             |
| update        |      |                     |             |

#### Response

| Name | Type | Description |
| ---- | ---- | ----------- |
|      |      |             |

#### Examples

```
http://192.168.100.145:8080iapi/v1/AddS3Bucket?session=c1782caf-b670-42d8-ba90-2244d0b0ee83
```

```
data:
{
  "part": 
​    {
  ​    "nIndex": 1,
  ​    "strAccessKey": "bMoLv2fz1sGTmeNGwYcy",
  ​    "strSecretKey": "XVfpS6Ps6CniOtfsvFtDu8Jn2r0Ryycc7Ye2uy1I",
  ​    "strRegionName": "region-a",
  ​    "strBucketName": "bucket-a",
  ​    "strEndpoint": "http://10.168.1.193:9001/"
​    },
  "update": false
}

response:
{
    "code": "HPRO_CODE_OK",
    "msg": "Success"
}
```