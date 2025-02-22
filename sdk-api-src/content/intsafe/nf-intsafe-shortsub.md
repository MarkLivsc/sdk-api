---
UID: NF:intsafe.ShortSub
title: ShortSub function (intsafe.h)
description: Subtracts one value of type SHORT from another.
old-location: shell\ShortSub.htm
tech.root: shell
ms.assetid: df438d87-5786-4c55-81f2-534fa9532f09
ms.date: 12/05/2018
ms.keywords: ShortSub, ShortSub function [Windows Shell], intsafe/ShortSub, shell.ShortSub
ms.topic: function
f1_keywords:
- intsafe/ShortSub
dev_langs:
- c++
req.header: intsafe.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows 7 [desktop apps \| UWP apps]
req.target-min-winversvr: Windows Server 2008 R2 [desktop apps \| UWP apps]
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
- HeaderDef
api_location:
- intsafe.h
api_name:
- ShortSub
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# ShortSub function


## -description


Subtracts one value of type <b>SHORT</b> from another.


## -parameters




### -param sMinuend [in]

The first value.


### -param sSubtrahend [in]

The value to subtract.


### -param psResult [out]

The result.


## -returns



If this function succeeds, it returns <b xmlns:loc="http://microsoft.com/wdcml/l10n">S_OK</b>. Otherwise, it returns an <b xmlns:loc="http://microsoft.com/wdcml/l10n">HRESULT</b> error code.



