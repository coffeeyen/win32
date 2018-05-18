﻿---
Description: 'The Certificates property retrieves a Certificates collection that represents the certificates in the chain. This is the default property.'
ms.assetid: 'c3e6953f-35e5-469a-a1aa-e3a4ebe21ac3'
title: 'IChain2::Certificates property'
---

# IChain2::Certificates property

\[CAPICOM is a 32-bit only component that is available for use in the following operating systems: Windows Server 2008, Windows Vista, and Windows XP. Instead, use the [**X509Chain Class**](T:System.Security.Cryptography.X509Certificates.X509Chain) in the [**System.Security.Cryptography.X509Certificates**](frlrfSystemSecurityCryptographyX509Certificates) namespace.\]

The **Certificates** property retrieves a [**Certificates**](certificates.md) collection that represents the certificates in the chain. This is the default property.

This property is read-only.

## Syntax


```VB
Chain.Certificates As Certificates
```



## Property value

A [**Certificates**](certificates.md) collection that is used to retrieve information about each certificate in the chain. The first certificate in the returned collection, **Certificates.Item**(1), is the end certificate of the chain. The last certificate in the collection, **Certificates.Item**(**Certificates.Count**), is the [*root certificate*](security.r_gly#-security-root-certificate-gly) of the chain.

## Requirements



|                                  |                                                                                        |
|----------------------------------|----------------------------------------------------------------------------------------|
| End of client support<br/> | Windows Vista<br/>                                                               |
| End of server support<br/> | Windows Server 2008<br/>                                                         |
| Redistributable<br/>       | CAPICOM 2.0 or later on Windows Server 2003 and Windows XP<br/>                  |
| DLL<br/>                   | <dl> <dt>Capicom.dll</dt> </dl> |



 

 



