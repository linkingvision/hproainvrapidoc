---
title: GetObjPartitions
sidebar_position: 9
---

#### Description



#### Usage  

| Request parameters | GET                                |
| ------------------ | :--------------------------------- |
| URL                | /iapi/v1/GetObjPartitions?session= |
| data               | none                               |

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
http://192.168.100.145:8080/iapi/v1/GetObjPartitions?session=c1782caf-b670-42d8-ba90-2244d0b0ee83
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
                "strDevice": "D:",
                "strMountpoint": "D:",
                "bMount": true,
                "strStartTime": "2025-11-14T08:54:55+08:00",
                "strEndTime": "2025-11-14T09:38:06+08:00",
                "chRec": [
                    {
                        "nChan": 1,
                        "strStartTime": "2025-11-14T09:00:54+08:00",
                        "strEndTime": "2025-11-14T09:38:06+08:00"
                    },
                    {
                        "nChan": 2,
                        "strStartTime": "2025-11-14T08:54:55+08:00",
                        "strEndTime": "2025-11-14T09:37:53+08:00"
                    },
                    {
                        "nChan": 3,
                        "strStartTime": "2025-11-14T08:54:55+08:00",
                        "strEndTime": "2025-11-14T09:37:49+08:00"
                    },
                    {
                        "nChan": 4,
                        "strStartTime": "2025-11-14T09:00:41+08:00",
                        "strEndTime": "2025-11-14T09:27:16+08:00"
                    }
                ]
            },
            {
                "nIndex": 2,
                "strDevice": "C:",
                "strMountpoint": "C:",
                "bMount": true,
                "strStartTime": "",
                "strEndTime": "",
                "chRec": []
            }
        ]
    }
}
```