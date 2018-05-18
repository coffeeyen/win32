---
Description: 'The CIM\_RelatedStatistics association represents hierarchies and dependencies of related CIM\_StatisticalInformation classes.'
audience: developer
author: 'REDMOND\\markl'
manager: 'REDMOND\\markl'
ms.assetid: 'f5cea01d-7854-4ad4-a89e-db0ce9f4a83f'
ms.prod: 'windows-server-dev'
ms.technology:
- cimwin32
- 'windows-management-instrumentation'
ms.tgt_platform: multiple
title: 'CIM\_RelatedStatistics class'
---

# CIM\_RelatedStatistics class

The **CIM\_RelatedStatistics** association represents hierarchies and dependencies of related [**CIM\_StatisticalInformation**](cim-statisticalinformation.md) classes.

> \[!Important\]  
> The DMTF (Distributed Management Task Force) CIM (Common Information Model) classes are the parent classes upon which WMI classes are built. WMI currently supports only the [CIM 2.x version schemas](Http://Go.Microsoft.Com/FWLink/p/?LinkID=309367).

�

The following syntax is simplified from Managed Object Format (MOF) code and includes all of its inherited properties. Properties are listed in alphabetic order, not MOF order.

## Syntax

``` syntax
[Abstract, Association, UUID("{956597A4-7D80-11D2-AAD3-006008C78BC7}"), AMENDMENT]
class CIM_RelatedStatistics
{
  CIM_StatisticalInformation REF RelatedStats;
  CIM_StatisticalInformation REF Stats;
};
```

## Members

The **CIM\_RelatedStatistics** class has these types of members:

-   [Properties](#properties)

### Properties

The **CIM\_RelatedStatistics** class has these properties.

<dl> <dt>

**RelatedStats**
</dt> <dd> <dl> <dt>

Data type: **CIM\_StatisticalInformation**
</dt> <dt>

Access type: Read-only
</dt> </dl>

Reference to the related statistics or metrics.

</dd> <dt>

**Stats**
</dt> <dd> <dl> <dt>

Data type: **CIM\_StatisticalInformation**
</dt> <dt>

Access type: Read-only
</dt> </dl>

Reference to the statistic information or object.

</dd> </dl>

## Remarks

WMI does not implement this class.

This documentation is derived from the CIM class descriptions published by the DMTF. Microsoft may have made changes to correct minor errors, conform to Microsoft SDK documentation standards, or provide more information.

## Requirements



|                                     |                                                                                         |
|-------------------------------------|-----------------------------------------------------------------------------------------|
| Minimum supported client<br/> | Windows�Vista<br/>                                                                |
| Minimum supported server<br/> | Windows Server�2008<br/>                                                          |
| Namespace<br/>                | Root\\CIMV2<br/>                                                                  |
| MOF<br/>                      | <dl> <dt>CIMWin32.mof</dt> </dl> |
| DLL<br/>                      | <dl> <dt>CIMWin32.dll</dt> </dl> |



�

�



