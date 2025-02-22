---
UID: NF:winuser.RealGetWindowClassW
title: RealGetWindowClassW function (winuser.h)
description: Retrieves a string that specifies the window type.
old-location: winmsg\realgetwindowclass.htm
tech.root: winmsg
ms.assetid: VS|winui|~\winui\windowsuserinterface\windowing\windows\windowreference\windowfunctions\realgetwindowclass.htm
ms.date: 12/05/2018
ms.keywords: RealGetWindowClass, RealGetWindowClass function [Windows and Messages], RealGetWindowClassW, _win32_RealGetWindowClass, _win32_realgetwindowclass_cpp, winmsg.realgetwindowclass, winui._win32_realgetwindowclass, winuser/RealGetWindowClass, winuser/RealGetWindowClassW
ms.topic: function
f1_keywords:
- winuser/RealGetWindowClass
dev_langs:
- c++
req.header: winuser.h
req.include-header: Windows.h
req.target-type: Windows
req.target-min-winverclnt: Windows 2000 Professional [desktop apps only]
req.target-min-winversvr: Windows 2000 Server [desktop apps only]
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: RealGetWindowClassW (Unicode)
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: User32.lib
req.dll: User32.dll
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- DllExport
api_location:
- User32.dll
- Ext-MS-Win-NTUser-Windowclass-l1-1-1.dll
- Ext-MS-Win-RTCore-NTUser-Window-Ext-l1-1-0.dll
- minuser.dll
- ext-ms-win-ntuser-windowclass-l1-1-2.dll
api_name:
- RealGetWindowClass
- RealGetWindowClassW
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# RealGetWindowClassW function


## -description


Retrieves a string that specifies the window type.


## -parameters




### -param hwnd [in]

Type: <b>HWND</b>

A handle to the window whose type will be retrieved. 


### -param ptszClassName [out]

Type: <b>LPTSTR</b>

A pointer to a string that receives the window type. 


### -param cchClassNameMax [in]

Type: <b>UINT</b>

The length, in characters, of the buffer pointed to by the <i>pszType</i> parameter. 


## -returns



Type: <strong>Type: <b>UINT</b>
</strong>

If the function succeeds, the return value is the number of characters copied to the specified buffer. 

If the function fails, the return value is zero. To get extended error information, call <a href="https://docs.microsoft.com/windows/desktop/api/errhandlingapi/nf-errhandlingapi-getlasterror">GetLastError</a>. 




## -see-also




<a href="https://docs.microsoft.com/windows/desktop/winmsg/windows">Windows Overview</a>
 

 

