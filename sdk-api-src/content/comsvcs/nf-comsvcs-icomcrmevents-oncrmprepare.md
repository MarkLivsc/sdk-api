---
UID: NF:comsvcs.IComCRMEvents.OnCRMPrepare
title: IComCRMEvents::OnCRMPrepare (comsvcs.h)
description: Generated when CRM clerk receives a prepare notification to pass on to the CRM compensator.
old-location: cos\icomcrmevents_oncrmprepare.htm
tech.root: cossdk
ms.assetid: 16ecd4a5-6ca6-443d-ab03-f9ceb951ed13
ms.date: 12/05/2018
ms.keywords: IComCRMEvents interface [COM+],OnCRMPrepare method, IComCRMEvents.OnCRMPrepare, IComCRMEvents::OnCRMPrepare, OnCRMPrepare, OnCRMPrepare method [COM+], OnCRMPrepare method [COM+],IComCRMEvents interface, _dtc_IComCRMEvents_OnCRMPrepare, comsvcs/IComCRMEvents::OnCRMPrepare, cos.icomcrmevents_oncrmprepare
ms.topic: method
f1_keywords:
- comsvcs/IComCRMEvents.OnCRMPrepare
dev_langs:
- c++
req.header: comsvcs.h
req.include-header: 
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
req.lib: 
req.dll: 
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- COM
api_location:
- ComSvcs.h
api_name:
- IComCRMEvents.OnCRMPrepare
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# IComCRMEvents::OnCRMPrepare


## -description


Generated when CRM clerk receives a prepare notification to pass on to the CRM compensator.


## -parameters




### -param pInfo [in]

A pointer to a <a href="https://docs.microsoft.com/windows/win32/api/comsvcs/ns-comsvcs-comsvcseventinfo">COMSVCSEVENTINFO</a> structure.


### -param guidClerkCLSID [in]

The identifier of the CRM clerk.


## -returns



The user verifies the return values from this method.




## -see-also




<a href="https://docs.microsoft.com/windows/desktop/api/comsvcs/nn-comsvcs-icomcrmevents">IComCRMEvents</a>
 

 

