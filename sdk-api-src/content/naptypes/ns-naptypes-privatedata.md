---
UID: NS:naptypes.tagPrivateData
title: PrivateData (naptypes.h)
description: Is used to store and retrieve opaque data blobs.
old-location: nap\privatedata_struct.htm
tech.root: NAP
ms.assetid: e2859983-3780-464d-b878-e63d974ba386
ms.date: 12/05/2018
ms.keywords: PrivateData, PrivateData structure [NAP], nap.privatedata_struct, naptypes/PrivateData
ms.topic: struct
f1_keywords:
- naptypes/PrivateData
dev_langs:
- c++
req.header: naptypes.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows Vista [desktop apps only]
req.target-min-winversvr: Windows Server 2008 [desktop apps only]
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: NapTypes.idl
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
- NapTypes.h
api_name:
- PrivateData
targetos: Windows
req.typenames: PrivateData
req.redist: 
ms.custom: 19H1
---

# PrivateData structure


## -description


<div class="alert"><b>Note</b>  The Network Access Protection platform is not available starting with Windows 10</div><div> </div>The <b>PrivateData</b> structure is used to store and retrieve opaque data blobs.


## -struct-fields




### -field size

The size, in bytes,  of  <b>data</b> in the range 0 to <a href="https://docs.microsoft.com/windows/desktop/NAP/nap-type-constants">maxPrivateDataSize</a>.


### -field data

A pointer to the opaque data blob.


## -remarks



The <b>PrivateData</b> structure is used to store state information for the NapAgent and enforcement clients. It is queried and set by the <a href="https://docs.microsoft.com/windows/desktop/NAP/inapsystemhealthvalidationrequest">INapSystemHealthValidationRequest</a> and <a href="https://docs.microsoft.com/windows/desktop/NAP/inapenforcementclientconnection">INapEnforcementClientConnection</a> interfaces.




## -see-also




<a href="https://docs.microsoft.com/windows/desktop/NAP/nap-reference">NAP Reference</a>



<a href="https://docs.microsoft.com/windows/desktop/NAP/nap-structures">NAP Structures</a>
 

 

