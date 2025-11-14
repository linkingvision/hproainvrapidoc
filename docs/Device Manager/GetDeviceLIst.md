---
title: GetDeviceLIst
sidebar_position: 1
---

#### Description



#### Usage  

| Request parameters | GET                             |
| ------------------ | :------------------------------ |
| URL                | /iapi/v1/GetDeviceList?session= |
| data               | none                            |

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
http://192.168.100.145:8080/iapi/v1/GetDeviceList?session=c1782caf-b670-42d8-ba90-2244d0b0ee83
```

```
response:
{
    "code": "HPRO_CODE_OK",
    "msg": "Success",
    "result": {
        "dev": [
            {
                "nType": "H5_DEV_ONFSTG",
                "strName": "Group1",
                "strToken": "m3JS",
                "strUser": "admin",
                "strPasswd": "admin12345",
                "bPasswdEncrypt": false,
                "strDevIpAddress": "192.168.100.194",
                "strDevPort": "80",
                "bEnableAudio": true,
                "nMaxChannel": 0,
                "bCentralRecord": false,
                "bSandbox": false,
                "bISAPI": false,
                "bVMS": false,
                "nRBufferTime": 200,
                "bSubEvent": true,
                "nApiPort": 80,
                "bApiHttps": false,
                "strClientId": "clientid",
                "strClientSecret": "clientsecret",
                "bIntercom": false,
                "bApiListenMode": false,
                "bOnline": true,
                "strVer": ""
            },
            {
                "nType": "H5_DEV_ONFSTG",
                "strName": "Door 3",
                "strToken": "sLKs",
                "strUser": "admin",
                "strPasswd": "xue12345",
                "bPasswdEncrypt": false,
                "strDevIpAddress": "192.168.100.120",
                "strDevPort": "80",
                "bEnableAudio": true,
                "nMaxChannel": 0,
                "bCentralRecord": false,
                "bSandbox": false,
                "bISAPI": false,
                "bVMS": false,
                "nRBufferTime": 200,
                "bSubEvent": true,
                "nApiPort": 80,
                "bApiHttps": false,
                "strClientId": "clientid",
                "strClientSecret": "clientsecret",
                "bIntercom": false,
                "bApiListenMode": false,
                "bOnline": true,
                "strVer": ""
            }
        ]
    }
}
```