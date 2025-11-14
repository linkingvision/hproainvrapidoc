---
title: GetDiskPartitions
sidebar_position: 15
---

#### Description



#### Usage  

| Request parameters | GET                                 |
| ------------------ | :---------------------------------- |
| URL                | /iapi/v1/GetDiskPartitions?session= |
| data               | none                                |

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
http://192.168.100.145:8080/iapi/v1/GetDiskPartitions?session=c1782caf-b670-42d8-ba90-2244d0b0ee83
```

```
response:
{
    "code": "HPRO_CODE_OK",
    "msg": "Success",
    "result": {
        "part": [
            {
                "strDevice": "C:\\",
                "strPath": "C:\\",
                "bTotal": "607003",
                "bFree": "462242",
                "bReadOnly": false,
                "bSystem": true,
                "bBoot": true,
                "strSerial": "WD-WX22D91RRTSY",
                "strSerialFull": "WDC WD22EJRX-89BEMY0_WD-WX22D91RRTSY",
                "strFileSystem": "NTFS"
            },
            {
                "strDevice": "D:\\",
                "strPath": "D:\\",
                "bTotal": "1299998",
                "bFree": "1296834",
                "bReadOnly": false,
                "bSystem": false,
                "bBoot": false,
                "strSerial": "WD-WX22D91RRTSY",
                "strSerialFull": "WDC WD22EJRX-89BEMY0_WD-WX22D91RRTSY",
                "strFileSystem": "NTFS"
            },
            {
                "strDevice": "E:\\",
                "strPath": "E:\\",
                "bTotal": "1907711",
                "bFree": "1757713",
                "bReadOnly": false,
                "bSystem": false,
                "bBoot": false,
                "strSerial": "WFL51MWQ",
                "strSerialFull": "ST2000DM008-2FR102_WFL51MWQ",
                "strFileSystem": "NTFS"
            }
        ]
    }
}
```