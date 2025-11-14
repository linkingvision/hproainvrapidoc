---
title: GetS3Buckets
sidebar_position: 12
---

#### Description



#### Usage  

| Request parameters | GET                            |
| ------------------ | :----------------------------- |
| URL                | /iapi/v1/GetS3Buckets?session= |
| data               | none                           |

#### Parameters

| Name    | Type | Parameter mandatory | Description |
| :------ | :--- | :------------------ | :---------- |
| session |      |                     |             |

#### Response

| Name | Type | Description |
| ---- | ---- | ----------- |
|      |      |             |

#### Examples

```
https://192.168.100.161:16445/iapi/v1/GetS3Buckets?session=c1782caf-b670-42d8-ba90-2244d0b0ee83
```

```
response:
{
    "code": "HPRO_CODE_OK",
    "msg": "Success",
    "result": {
        "part": [
            {
                "nIndex": 1,
                "strAccessKey": "bMoLv2fz1sGtmeNgwyCY",
                "strSecretKey": "XVfpS6Ps6CniOtfsvFtDu8Jn2r0Ryycc7Ye2uy1I",
                "strRegionName": "region-a",
                "strBucketName": "bucket-a",
                "strEndpoint": "http://10.168.1.193:9001/",
                "bMount": false,
                "strStartTime": "",
                "strEndTime": "",
                "chRec": []
            }
        ]
    }
}
```