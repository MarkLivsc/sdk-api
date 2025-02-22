---
UID: NS:wsdtypes._WSD_LOCALIZED_STRING_LIST
title: WSD_LOCALIZED_STRING_LIST (wsdtypes.h)
description: Represents a node in a single-linked list of localized strings.
old-location: ncd\wsd_localized_string_list_struct.htm
tech.root: WsdApi
ms.assetid: 4941885c-d349-4e43-838f-b60c3cdc32ba
ms.date: 12/05/2018
ms.keywords: WSD_LOCALIZED_STRING_LIST, WSD_LOCALIZED_STRING_LIST structure, ncd.wsd_localized_string_list_struct, wsdtypes/WSD_LOCALIZED_STRING_LIST
ms.topic: struct
f1_keywords:
- wsdtypes/WSD_LOCALIZED_STRING_LIST
dev_langs:
- c++
req.header: wsdtypes.h
req.include-header: Wsdapi.h
req.target-type: Windows
req.target-min-winverclnt: Windows Vista [desktop apps only]
req.target-min-winversvr: Windows Server 2008 [desktop apps only]
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
- WsdTypes.h
api_name:
- WSD_LOCALIZED_STRING_LIST
targetos: Windows
req.typenames: WSD_LOCALIZED_STRING_LIST
req.redist: 
ms.custom: 19H1
---

# WSD_LOCALIZED_STRING_LIST structure


## -description


Represents a node in a single-linked list of localized strings.


## -struct-fields




### -field Next

Reference to the next node in the linked list of <b>WSD_LOCALIZED_STRING_LIST</b> structures.


### -field Element

The localized string referenced by this node.

