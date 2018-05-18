---
title: CLUSCTL\_CLOUD\_WITNESS\_RESOURCE\_UPDATE\_KEY control code
description: TBD.
audience: developer
author: REDMOND\\markl
manager: REDMOND\\markl
ms.assetid: '0BE65701-7AD8-4C21-8921-AB555A3BD943'
ms.prod: 'windows-server-dev'
ms.technology: 'failover-clustering'
ms.tgt_platform: multiple
keywords: ["CLUSCTL_CLOUD_WITNESS_RESOURCE_UPDATE_KEY control code Failover Cluster"]
---

# CLUSCTL\_CLOUD\_WITNESS\_RESOURCE\_UPDATE\_KEY control code

TBD. Applications use this [control code](about-control-codes.md) as a [**ClusterResourceControl**](clusterresourcecontrol.md) parameter.


```C++
ClusterResourceControl( 
  hResource,                       // resource handle
  hHostNode,                       // optional node handle
  CLUSCTL_CLOUD_WITNESS_RESOURCE_UPDATE_TOKEN,   // this control code
  lpInBuffer,                      // input buffer
  cbInBufferSize,                  // input buffer size (bytes)
  lpOutBuffer,                     // output buffer
  cbOutBufferSize,                 // output buffer size (bytes)
  lpcbBytesReturned );             // resulting data size (bytes)
```



## Parameters

The following control code function parameter is specific to this control code. For complete parameter descriptions, see [**ClusterResourceControl**](clusterresourcecontrol.md).

<dl> <dt>

*lpOutBuffer* 
</dt> <dd>

TBD.

</dd> </dl>

## Return value

[**ClusterResourceControl**](clusterresourcecontrol.md) returns one of the following values.

<dl> <dt>

**ERROR\_SUCCESS**
</dt> <dd>

0

The operation completed successfully. The *lpcbBytesReturned* parameter points to the actual size of the returned data.

</dd> <dt>

**ERROR\_MORE\_DATA**
</dt> <dd>

234 (0xEA)

More data is available. The output buffer pointed to by *lpOutBuffer* was not large enough to hold the data resulting from the operation. The *lpcbBytesReturned* parameter points to the size required for the output buffer.

</dd> <dt>

**[System error code](https://msdn.microsoft.com/library/windows/desktop/ms681381)**
</dt> <dd>

If any other value is returned, then the operation failed. The value of *lpcbBytesReturned* is unreliable.

</dd> </dl>

## Remarks

ClusAPI.h defines the 32 bits of CLUSCTL\_CLOUD\_WITNESS\_RESOURCE\_UPDATE\_KEY (0x014020f6) as follows (for more information, see [Control Code Architecture](control-code-architecture.md)).



| Component      | Bit location | Value                                                                  |
|----------------|--------------|------------------------------------------------------------------------|
| Object code    | 24�31        | **CLUS\_OBJECT\_RESOURCE** (0x1)<br/>                            |
| Global bit     | 23           | **CLUS\_NOT\_GLOBAL** (0x0)<br/>                                 |
| Modify bit     | 22           | **CLUS\_MODIFY** (0x1)<br/>                                      |
| User bit       | 21           | **CLCTL\_CLUSTER\_BASE** (0x0)<br/>                              |
| Type bit       | 20           | External (0x0)<br/>                                              |
| Operation code | 0�23         | **CLCTL\_CLOUD\_WITNESS\_RESOURCE\_UPDATE\_KEY** (0x4020f6)<br/> |
| Access code    | 0�1          | **CLUS\_ACCESS\_WRITE** (0x2)<br/>                               |



�

## Requirements



|                                     |                                                                                      |
|-------------------------------------|--------------------------------------------------------------------------------------|
| Minimum supported client<br/> | None supported<br/>                                                            |
| Minimum supported server<br/> | Windows Server�2016 \[desktop apps only\]<br/>                                 |
| Header<br/>                   | <dl> <dt>ClusAPI.h</dt> </dl> |



## See also

<dl> <dt>

[External Resource Control Codes](external-resource-control-codes.md)
</dt> <dt>

[Control Codes](about-control-codes.md)
</dt> </dl>

�

�




