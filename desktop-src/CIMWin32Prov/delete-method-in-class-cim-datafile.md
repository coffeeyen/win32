---
Description: The Delete method deletes the logical file (or directory) that is specified in the object path. This method is inherited from CIM\_LogicalFile.
ms.assetid: bc2ff005-b2c3-4098-b597-3a96d345b497
ms.tgt_platform: multiple
title: Delete method of the CIM_DataFile class
ms.topic: reference
ms.date: 05/31/2018
topic_type: 
- APIRef
- kbSyntax
api_name: 
- CIM_DataFile.Delete
api_type: 
- COM
api_location: 
- CIMWin32.dll
---

# Delete method of the CIM\_DataFile class

The **Delete** method deletes the logical file (or directory) that is specified in the object path. This method is inherited from [**CIM\_LogicalFile**](cim-logicalfile.md).

> [!IMPORTANT]
> The DMTF (Distributed Management Task Force) CIM (Common Information Model) classes are the parent classes upon which WMI classes are built. WMI currently supports only the [CIM 2.x version schemas](https://dmtf.org/standards/cim/schemas).

 

This topic uses Managed Object Format (MOF) syntax. For more information about using this method, see [Calling a Method](https://docs.microsoft.com/windows/desktop/WmiSdk/calling-a-method).

## Syntax


```mof
uint32 Delete();
```



## Parameters

This method has no parameters.

## Return value

Returns a value of 0 (zero) on success, and any other number to indicate an error. For additional error codes, see [**WMI Error Constants**](https://docs.microsoft.com/windows/desktop/WmiSdk/wmi-error-constants) or [**WbemErrorEnum**](https://docs.microsoft.com/windows/desktop/api/wbemdisp/ne-wbemdisp-wbemerrorenum). For general **HRESULT** values, see [System Error Codes](https://docs.microsoft.com/windows/desktop/Debug/system-error-codes).

<dl> <dt>

**0**
</dt> <dd>

Success.

</dd> <dt>

**2**
</dt> <dd>

Access denied.

</dd> <dt>

**8**
</dt> <dd>

Unspecified failure.

</dd> <dt>

**9**
</dt> <dd>

Invalid object.

</dd> <dt>

**10**
</dt> <dd>

Object already exists.

</dd> <dt>

**11**
</dt> <dd>

File system not NTFS.

</dd> <dt>

**12**
</dt> <dd>

Platform not Windows.

</dd> <dt>

**13**
</dt> <dd>

Drive not the same.

</dd> <dt>

**14**
</dt> <dd>

Directory not empty.

</dd> <dt>

**15**
</dt> <dd>

Sharing violation.

</dd> <dt>

**16**
</dt> <dd>

Invalid start file.

</dd> <dt>

**17**
</dt> <dd>

Privilege not held.

</dd> <dt>

**21**
</dt> <dd>

Invalid parameter.

</dd> </dl>

## Remarks

The **Delete** method in [**CIM\_DataFile**](cim-datafile.md) is implemented by WMI.

This documentation is derived from the CIM class descriptions published by the DMTF. Microsoft may have made changes to correct minor errors, conform to Microsoft SDK documentation standards, or provide more information.

## Requirements



|                                     |                                                                                         |
|-------------------------------------|-----------------------------------------------------------------------------------------|
| Minimum supported client<br/> | Windows Vista<br/>                                                                |
| Minimum supported server<br/> | Windows Server 2008<br/>                                                          |
| Namespace<br/>                | Root\\CIMV2<br/>                                                                  |
| MOF<br/>                      | <dl> <dt>CIMWin32.mof</dt> </dl> |
| DLL<br/>                      | <dl> <dt>CIMWin32.dll</dt> </dl> |



## See also

<dl> <dt>

[CIM\_DataFile](delete-method-in-class-cim-datafile.md)
</dt> <dt>

[**CIM\_DataFile**](cim-datafile.md)
</dt> <dt>

[WMI Tasks: Files and Folders](https://docs.microsoft.com/windows/desktop/WmiSdk/wmi-tasks--files-and-folders)
</dt> <dt>

[**File and Directory Access Rights Constants**](https://docs.microsoft.com/windows/desktop/WmiSdk/file-and-directory-access-rights-constants)
</dt> </dl>

 

 




