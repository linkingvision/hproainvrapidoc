---
title: DeleteS3Bucket
sidebar_position: 14
---

#### Description



#### Usage  

| Request parameters | POST                             |
| ------------------ | :------------------------------- |
| URL                | /iapi/v1/DeleteS3Bucket?session= |
| data               | none                             |

#### Parameters

| Name       | Type | Parameter mandatory | Description |
| :--------- | :--- | :------------------ | :---------- |
| index      |      |                     |             |
| bucketName |      |                     |             |
| endpoint   |      |                     |             |

#### Response

| Name | Type | Description |
| ---- | ---- | ----------- |
|      |      |             |

#### Examples

```
http://192.168.100.145:8080/iapi/v1/DeleteS3Bucket?session=c1782caf-b670-42d8-ba90-2244d0b0ee83
```

```
data:
{
  "index": 1,
  "bucketName": "bucket-a",
  "endpoint": "http://10.168.1.193:9001/"
}

response:
{
    "code": "HPRO_CODE_OK",
    "msg": "Success"
}
```