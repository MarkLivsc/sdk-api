---
UID: NF:control.IVideoWindow.get_AutoShow
title: IVideoWindow::get_AutoShow (control.h)
description: The get_AutoShow method queries whether the video renderer automatically shows the video window when it receives video data.
old-location: dshow\ivideowindow_get_autoshow.htm
tech.root: DirectShow
ms.assetid: 6f42e37d-af67-4f9e-8a02-d1f4154df391
ms.date: 12/05/2018
ms.keywords: IVideoWindow interface [DirectShow],get_AutoShow method, IVideoWindow.get_AutoShow, IVideoWindow::get_AutoShow, IVideoWindowget_AutoShow, control/IVideoWindow::get_AutoShow, dshow.ivideowindow_get_autoshow, get_AutoShow, get_AutoShow method [DirectShow], get_AutoShow method [DirectShow],IVideoWindow interface
ms.topic: method
f1_keywords:
- control/IVideoWindow.get_AutoShow
dev_langs:
- c++
req.header: control.h
req.include-header: Dshow.h
req.target-type: Windows
req.target-min-winverclnt: Windows 2000 Professional [desktop apps only]
req.target-min-winversvr: Windows 2000 Server [desktop apps only]
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: Strmiids.lib
req.dll: 
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- COM
api_location:
- Strmiids.lib
- Strmiids.dll
api_name:
- IVideoWindow.get_AutoShow
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# IVideoWindow::get_AutoShow


## -description



The <code>get_AutoShow</code> method queries whether the video renderer automatically shows the video window when it receives video data.




## -parameters




### -param AutoShow [out]

Receives one of the following values.

<table>
<tr>
<th>Value
                </th>
<th>Description
                </th>
</tr>
<tr>
<td>OATRUE
                </td>
<td>If the video renderer pauses or runs, it will automatically show the video window.</td>
</tr>
<tr>
<td>OAFALSE
                </td>
<td>The video renderer will not automatically show the video window.</td>
</tr>
</table>
 


## -returns



Possible return values include the following:

<table>
<tr>
<th>Return code</th>
<th>Description</th>
</tr>
<tr>
<td width="40%">
<dl>
<dt><b>E_POINTER</b></dt>
</dl>
</td>
<td width="60%">
<b>NULL</b> pointer.

</td>
</tr>
<tr>
<td width="40%">
<dl>
<dt><b>S_OK</b></dt>
</dl>
</td>
<td width="60%">
Success.

</td>
</tr>
<tr>
<td width="40%">
<dl>
<dt><b>VFW_E_NOT_CONNECTED</b></dt>
</dl>
</td>
<td width="60%">
The video renderer filter is not connected.

</td>
</tr>
</table>
 




## -see-also




<a href="https://docs.microsoft.com/windows/desktop/DirectShow/error-and-success-codes">Error and Success Codes</a>



<a href="https://docs.microsoft.com/windows/desktop/api/control/nn-control-ivideowindow">IVideoWindow Interface</a>
 

 

