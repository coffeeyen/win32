---
Description: 'The event type class for ADO.NET ETW adapter events. (Unicode).'
audience: developer
author: 'REDMOND\\markl'
manager: 'REDMOND\\markl'
ms.assetid: '326dd6a3-2edd-48b0-b6f4-c4f25828697f'
ms.prod: 'windows-server-dev'
ms.technology:
- 'dotnet-ado'
- 'windows-management-instrumentation'
ms.tgt_platform: multiple
title: 'Bid2Etw\_ADONETDIAG\_ETW\_Trace\_TextW class'
---

# Bid2Etw\_ADONETDIAG\_ETW\_Trace\_TextW class

The event type class for ADO.NET ETW adapter events. (Unicode)

The following syntax is simplified from Managed Object Format (MOF) code and includes all of the inherited properties.

## Syntax

``` syntax
[dynamic, EventType(18), EventTypeName("TextW")]
class Bid2Etw_ADONETDIAG_ETW_Trace_TextW : Bid2Etw_ADONETDIAG_ETW_Trace
{
  uint16 EventSize;
  uint16 ReservedHeaderField;
  uint8� EventType;
  uint8� TraceLevel;
  uint16 TraceVersion;
  uint64 ThreadId;
  uint64 TimeStamp;
  uint8� EventGuid[];
  uint32 KernelTime;
  uint32 UserTime;
  uint32 InstanceId;
  uint8� ParentGuid[];
  uint32 ParentInstanceId;
  uint32 MofData;
  uint32 MofLength;
  uint32 ModID;
  object msgStr;
};
```

## Members

The **Bid2Etw\_ADONETDIAG\_ETW\_Trace\_TextW** class has these types of members:

-   [Properties](#properties)

### Properties

The **Bid2Etw\_ADONETDIAG\_ETW\_Trace\_TextW** class has these properties.

<dl> <dt>

**EventGuid**
</dt> <dd> <dl> <dt>

Data type: **uint8** array
</dt> <dt>

Access type: Read-only
</dt> <dt>

Qualifiers: [**WmiDataId**](https://msdn.microsoft.com/library/windows/desktop/aa363800) (8), **Max** (16)
</dt> </dl>

Event trace class **GUID** of this event.

</dd> <dt>

**EventSize**
</dt> <dd> <dl> <dt>

Data type: **uint16**
</dt> <dt>

Access type: Read-only
</dt> <dt>

Qualifiers: [**WmiDataId**](https://msdn.microsoft.com/library/windows/desktop/aa363800) (1)
</dt> </dl>

Total number of bytes of the event.

</dd> <dt>

**EventType**
</dt> <dd> <dl> <dt>

Data type: **uint8**
</dt> <dt>

Access type: Read-only
</dt> <dt>

Qualifiers: [**WmiDataId**](https://msdn.microsoft.com/library/windows/desktop/aa363800) (3)
</dt> </dl>

Provider-defined event type. Tells you which event type class to use to decipher the provider-defined event data (the data pointed to by **MofData**.

</dd> <dt>

**InstanceId**
</dt> <dd> <dl> <dt>

Data type: **uint32**
</dt> <dt>

Access type: Read-only
</dt> <dt>

Qualifiers: [**WmiDataId**](https://msdn.microsoft.com/library/windows/desktop/aa363800) (11)
</dt> </dl>

Identifier of this event instance.

</dd> <dt>

**KernelTime**
</dt> <dd> <dl> <dt>

Data type: **uint32**
</dt> <dt>

Access type: Read-only
</dt> <dt>

Qualifiers: [**WmiDataId**](https://msdn.microsoft.com/library/windows/desktop/aa363800) (9)
</dt> </dl>

Elapsed execution time for kernel-mode instructions, in CPU ticks.

</dd> <dt>

**ModID**
</dt> <dd> <dl> <dt>

Data type: **uint32**
</dt> <dt>

Access type: Read-only
</dt> <dt>

Qualifiers: [**WmiDataId**](https://msdn.microsoft.com/library/windows/desktop/aa363800) (1)
</dt> </dl>

The identifier of the module that generated the event.

</dd> <dt>

**MofData**
</dt> <dd> <dl> <dt>

Data type: **uint32**
</dt> <dt>

Access type: Read-only
</dt> <dt>

Qualifiers: [**WmiDataId**](https://msdn.microsoft.com/library/windows/desktop/aa363800) (14), **Pointer**
</dt> </dl>

Pointer to the provider-specific event data.

</dd> <dt>

**MofLength**
</dt> <dd> <dl> <dt>

Data type: **uint32**
</dt> <dt>

Access type: Read-only
</dt> <dt>

Qualifiers: [**WmiDataId**](https://msdn.microsoft.com/library/windows/desktop/aa363800) (15)
</dt> </dl>

Length of the provider-specific event data.

</dd> <dt>

**msgStr**
</dt> <dd> <dl> <dt>

Data type: **object**
</dt> <dt>

Access type: Read-only
</dt> <dt>

Qualifiers: [**WmiDataId**](https://msdn.microsoft.com/library/windows/desktop/aa363800) (2), **extension** ("RWString")
</dt> </dl>

The Unicode message string.

</dd> <dt>

**ParentGuid**
</dt> <dd> <dl> <dt>

Data type: **uint8** array
</dt> <dt>

Access type: Read-only
</dt> <dt>

Qualifiers: [**WmiDataId**](https://msdn.microsoft.com/library/windows/desktop/aa363800) (12), **Max** (16)
</dt> </dl>

Event trace class **GUID** of the parent instance.

</dd> <dt>

**ParentInstanceId**
</dt> <dd> <dl> <dt>

Data type: **uint32**
</dt> <dt>

Access type: Read-only
</dt> <dt>

Qualifiers: [**WmiDataId**](https://msdn.microsoft.com/library/windows/desktop/aa363800) (13)
</dt> </dl>

Identifier of the parent instance data.

</dd> <dt>

**ReservedHeaderField**
</dt> <dd> <dl> <dt>

Data type: **uint16**
</dt> <dt>

Access type: Read-only
</dt> <dt>

Qualifiers: [**WmiDataId**](https://msdn.microsoft.com/library/windows/desktop/aa363800) (2)
</dt> </dl>

Reserved.

</dd> <dt>

**ThreadId**
</dt> <dd> <dl> <dt>

Data type: **uint64**
</dt> <dt>

Access type: Read-only
</dt> <dt>

Qualifiers: [**WmiDataId**](https://msdn.microsoft.com/library/windows/desktop/aa363800) (6), **Pointer**
</dt> </dl>

Identifies the thread that generated the event.

</dd> <dt>

**TimeStamp**
</dt> <dd> <dl> <dt>

Data type: **uint64**
</dt> <dt>

Access type: Read-only
</dt> <dt>

Qualifiers: [**WmiDataId**](https://msdn.microsoft.com/library/windows/desktop/aa363800) (7)
</dt> </dl>

Contains the date and time when the event occurred.

</dd> <dt>

**TraceLevel**
</dt> <dd> <dl> <dt>

Data type: **uint8**
</dt> <dt>

Access type: Read-only
</dt> <dt>

Qualifiers: [**WmiDataId**](https://msdn.microsoft.com/library/windows/desktop/aa363800) (4)
</dt> </dl>

Provider-defined value that defines the severity level used to generate the event.

</dd> <dt>

**TraceVersion**
</dt> <dd> <dl> <dt>

Data type: **uint16**
</dt> <dt>

Access type: Read-only
</dt> <dt>

Qualifiers: [**WmiDataId**](https://msdn.microsoft.com/library/windows/desktop/aa363800) (5)
</dt> </dl>

Provider-defined version number of the event trace class used to generate the event.

</dd> <dt>

**UserTime**
</dt> <dd> <dl> <dt>

Data type: **uint32**
</dt> <dt>

Access type: Read-only
</dt> <dt>

Qualifiers: [**WmiDataId**](https://msdn.microsoft.com/library/windows/desktop/aa363800) (10)
</dt> </dl>

Elapsed execution time for user-mode instructions, in CPU ticks.

</dd> </dl>

## Requirements



|                                     |                                                                                           |
|-------------------------------------|-------------------------------------------------------------------------------------------|
| Minimum supported client<br/> | Windows�Vista<br/>                                                                  |
| Minimum supported server<br/> | Windows Server�2008<br/>                                                            |
| Namespace<br/>                | Root\\WMI<br/>                                                                      |
| MOF<br/>                      | <dl> <dt>AdoNetDiag.mof</dt> </dl> |
| DLL<br/>                      | <dl> <dt>AdoNetDiag.dll</dt> </dl> |



�

�



