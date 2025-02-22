---
UID: NF:windows.media.streaming.IMediaRenderer.GetMuteAsync
title: IMediaRenderer::streaming (windows.media.streaming.h)
description: Queries the DMR asynchronously to determine if audio is currently muted or unmuted.
old-location: mediastreaming\imediarenderer_getmuteasync.htm
tech.root: mediastreaming
ms.assetid: 411CAF71-2888-46A3-8777-80B0D6D9CDE5
ms.date: 12/05/2018
ms.keywords: GetMuteAsync, GetMuteAsync method [Media Streaming API], GetMuteAsync method [Media Streaming API],IMediaRenderer interface, IMediaRenderer interface [Media Streaming API],GetMuteAsync method, IMediaRenderer.GetMuteAsync, IMediaRenderer.streaming, IMediaRenderer::GetMuteAsync, IMediaRenderer::streaming, mediastreaming.imediarenderer_getmuteasync, windows/IMediaRenderer::GetMuteAsync
ms.topic: method
f1_keywords:
- windows.media.streaming/IMediaRenderer.GetMuteAsync
dev_langs:
- c++
req.header: windows.media.streaming.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: 
req.target-min-winversvr: 
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: 
req.dll: 
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- COM
api_location:
- windows.media.streaming.h
api_name:
- IMediaRenderer.GetMuteAsync
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# IMediaRenderer::streaming


## -description


Queries the DMR asynchronously to determine if audio is currently muted or unmuted.


## -parameters




### -param value [out]

Receives a reference to a  <a href="https://docs.microsoft.com/windows/desktop/mediastreaming/getmuteoperation">GetMuteOperation</a> object that is used to get results from the asynchronous operation.


## -returns



The method returns an <b>HRESULT</b>. Possible values include, but are not limited to, those in the following table.

<table>
<tr>
<th>Return code</th>
<th>Description</th>
</tr>
<tr>
<td width="40%">
<dl>
<dt><b>S_OK</b></dt>
</dl>
</td>
<td width="60%">
The method succeeded.

</td>
</tr>
</table>
 




## -see-also




<a href="https://docs.microsoft.com/windows/desktop/mediastreaming/imediarenderer">IMediaRenderer</a>
 

 

