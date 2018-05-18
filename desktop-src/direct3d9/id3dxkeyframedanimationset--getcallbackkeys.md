﻿---
Description: 'Fills an array with callback key data used for key frame animation.'
ms.assetid: '2a2aa04a-a889-415b-8aa2-cc5f2bed1f9a'
title: 'ID3DXKeyframedAnimationSet::GetCallbackKeys method'
---

# ID3DXKeyframedAnimationSet::GetCallbackKeys method

Fills an array with callback key data used for key frame animation.

## Syntax


```C++
HRESULT GetCallbackKeys(
  [out] LPD3DXKEY_CALLBACK pCallbackKeys
);
```



## Parameters

<dl> <dt>

*pCallbackKeys* \[out\]
</dt> <dd>

Type: **[**LPD3DXKEY\_CALLBACK**](d3dxkey-callback.md)**

Pointer to a user-allocated array of [**D3DXKEY\_CALLBACK**](d3dxkey-callback.md) structures that the method is to fill with callback data.

</dd> </dl>

## Return value

Type: **[**HRESULT**](455d07e9-52c3-4efb-a9dc-2955cbfd38cc)**

If the method succeeds, the return value is S\_OK. If the method fails, the following value will be returned: D3DERR\_INVALIDCALL.

## Requirements



|                    |                                                                                        |
|--------------------|----------------------------------------------------------------------------------------|
| Header<br/>  | <dl> <dt>D3dx9anim.h</dt> </dl> |
| Library<br/> | <dl> <dt>D3dx9.lib</dt> </dl>   |



## See also

<dl> <dt>

[ID3DXKeyframedAnimationSet](id3dxkeyframedanimationset.md)
</dt> <dt>

[**ID3DXKeyframedAnimationSet::GetNumCallbackKeys**](id3dxkeyframedanimationset--getnumcallbackkeys.md)
</dt> </dl>

 

 



