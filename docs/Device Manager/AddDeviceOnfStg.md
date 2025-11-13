---
title: AddDeviceOnfStg
sidebar_position: 5
---

#### Description



#### Usage  

| Request parameters | POST                              |
| ------------------ | :-------------------------------- |
| URL                | /iapi/v1/AddDeviceOnfStg?session= |
| data               | none                              |

#### Parameters

| Name        | Type | Parameter mandatory | Description |
| :---------- | :--- | :------------------ | :---------- |
| name        |      |                     |             |
| token       |      |                     |             |
| user        |      |                     |             |
| password    |      |                     |             |
| ip          |      |                     |             |
| port        |      |                     |             |
| audio       |      |                     |             |
| sandbox     |      |                     |             |
| maxchannel  |      |                     |             |
| update      |      |                     |             |
| rbuffertime |      |                     |             |

#### Response

| Name | Type | Description |
| ---- | ---- | ----------- |
|      |      |             |

#### Examples

```
http://192.168.100.145:8080/iapi/v1/AddDeviceOnfStg?session=c1782caf-b670-42d8-ba90-2244d0b0ee83
```

data:

```
{
 "name": "onvifstg1",
 "token": "002a",
 "user": "admin",
 "password": "admin12345",
 "ip": "192.168.100.194",
 "port": "80",
 "audio": true,
 "sandbox": false,
 "maxchannel": 0,
 "update": true,
 "rbuffertime": 200
}
```

