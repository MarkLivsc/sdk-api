---
UID: NF:faxcomex.IFaxOutboundRoutingRules.get__NewEnum
title: IFaxOutboundRoutingRules::get__NewEnum (faxcomex.h)
description: The IFaxOutboundRoutingRules::get__NewEnum method returns a reference to an enumerator object that you can use to iterate through the FaxOutboundRoutingRules collection.
old-location: fax\_mfax_ifaxoutboundroutingrules_get__newenum.htm
tech.root: Fax
ms.assetid: VS|fax|~\fax\faxinto_z_2a7h.htm
ms.date: 12/05/2018
ms.keywords: IFaxOutboundRoutingRules interface [Fax Service],get__NewEnum method, IFaxOutboundRoutingRules.get__NewEnum, IFaxOutboundRoutingRules::get__NewEnum, _mfax_ifaxoutboundroutingrules_get__newenum, fax._mfax_ifaxoutboundroutingrules_get__newenum, faxcomex/IFaxOutboundRoutingRules::get__NewEnum, get__NewEnum, get__NewEnum method [Fax Service], get__NewEnum method [Fax Service],IFaxOutboundRoutingRules interface
ms.topic: method
f1_keywords:
- faxcomex/IFaxOutboundRoutingRules.get__NewEnum
dev_langs:
- c++
req.header: faxcomex.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows XP [desktop apps only]
req.target-min-winversvr: Windows Server 2003 [desktop apps only]
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
req.dll: Fxscomex.dll
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- COM
api_location:
- Fxscomex.dll
api_name:
- IFaxOutboundRoutingRules.get__NewEnum
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# IFaxOutboundRoutingRules::get__NewEnum


## -description


The <b>IFaxOutboundRoutingRules::get__NewEnum</b> method returns a reference to an enumerator object that you can use to iterate through the <a href="https://docs.microsoft.com/previous-versions/windows/desktop/fax/-mfax-faxoutboundroutingrules">FaxOutboundRoutingRules</a> collection.


## -parameters




### -param ppUnk [out, retval]

Type: <b><a href="https://docs.microsoft.com/windows/desktop/api/unknwn/nn-unknwn-iunknown">IUnknown</a>**</b>

 Receives an indirect pointer to the enumerator object <a href="https://docs.microsoft.com/windows/desktop/api/unknwn/nn-unknwn-iunknown">IUnknown</a> interface for this collection.


## -returns



Type: <b>HRESULT</b>

If this method succeeds, it returns <b xmlns:loc="http://microsoft.com/wdcml/l10n">S_OK</b>. Otherwise, it returns an <b xmlns:loc="http://microsoft.com/wdcml/l10n">HRESULT</b> error code.




## -see-also




<a href="https://docs.microsoft.com/previous-versions/windows/desktop/fax/-mfax-faxoutboundroutingrules">FaxOutboundRoutingRules</a>



<a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/faxcomex/nn-faxcomex-ifaxoutboundroutingrules">IFaxOutboundRoutingRules</a>
 

 

