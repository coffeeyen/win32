﻿---
Description: 'Specifies whether a stream is mutually exclusive with other streams of the same type.'
ms.assetid: '00a426ae-297c-4fcb-8132-d9c538bc9f1a'
title: 'MF\_SD\_MUTUALLY\_EXCLUSIVE attribute'
---

# MF\_SD\_MUTUALLY\_EXCLUSIVE attribute

Specifies whether a stream is mutually exclusive with other streams of the same type.

## Data type

**UINT32**

## Get/set

To get this attribute, call [**IMFAttributes::GetUINT32**](imfattributes-getuint32.md).

To set this attribute, call [**IMFAttributes::SetUINT32**](imfattributes-setuint32.md).

## Applies to

[**IMFStreamDescriptor**](imfstreamdescriptor.md)

## Remarks

If this attribute is **TRUE** (nonzero), the stream is mutually exclusive with other streams of the same type, such as audio or video, within the same presentation. For example, if an AVI file contains multiple audio streams, they are marked as mutually exclusive, because only one audio stream should be played at one time.

The default value is **FALSE**.

> [!Note]  
> This attribute is not used for Advanced Systems Format (ASF) files, which have a more sophisticated way to represent mutual exclusion criteria. For more information, see [**IMFASFMutualExclusion**](imfasfmutualexclusion.md).

 

The GUID constant for this attribute is exported from mfuuid.lib.

## Requirements



|                                     |                                                                                    |
|-------------------------------------|------------------------------------------------------------------------------------|
| Minimum supported client<br/> | Windows 7 \[desktop apps \| UWP apps\]<br/>                                  |
| Minimum supported server<br/> | Windows Server 2008 R2 \[desktop apps \| UWP apps\]<br/>                     |
| Header<br/>                   | <dl> <dt>Mfidl.h</dt> </dl> |



## See also

<dl> <dt>

[Alphabetical List of Media Foundation Attributes](alphabetical-list-of-media-foundation-attributes.md)
</dt> <dt>

[Stream Descriptor Attributes](stream-descriptor-attributes.md)
</dt> </dl>

 

 



