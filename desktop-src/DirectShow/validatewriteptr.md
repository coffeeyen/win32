﻿---
Description: 'Verifies that the calling process has write access to a memory block. If not, the macro calls the DbgBreak macro.'
ms.assetid: 'efbb5ca6-0289-487d-b55a-f85b38d0515a'
title: ValidateWritePtr macro
---

# ValidateWritePtr macro

Verifies that the calling process has write access to a memory block. If not, the macro calls the [**DbgBreak**](dbgbreak.md) macro.

> [!Note]  
> This macro is deprecated. In the Windows SDK for Windows Vista (and later) this macro does not do anything.

 

## Syntax


```C++
void ValidateWritePtr(
   const void *p,
         UINT cb
);
```



## Parameters

<dl> <dt>

*p* 
</dt> <dd>

Pointer to a memory block.

</dd> <dt>

*cb* 
</dt> <dd>

Size of the memory block, in bytes.

</dd> </dl>

## Return value

This macro does not return a value.

## Remarks

This macro is ignored unless DEBUG, \_DEBUG, or VFWROBUST is defined when the DirectShow base-class header file is included. This macro can have a significant performance cost.

## Requirements



|                   |                                                                                                          |
|-------------------|----------------------------------------------------------------------------------------------------------|
| Header<br/> | <dl> <dt>Wxdebug.h (include Streams.h)</dt> </dl> |



## See also

<dl> <dt>

[Pointer Validation Macros](pointer-validation-macros.md)
</dt> </dl>

 

 



