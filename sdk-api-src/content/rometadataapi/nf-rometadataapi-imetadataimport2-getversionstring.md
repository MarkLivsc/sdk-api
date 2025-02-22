---
UID: NF:rometadataapi.IMetaDataImport2.GetVersionString
title: IMetaDataImport2::GetVersionString (rometadataapi.h)
description: Gets the version number of the runtime that was used to build the assembly.
old-location: winrt\imetadataimport2_getversionstring.htm
tech.root: WinRT
ms.assetid: 9f04ee6f-4a7d-4cdb-868e-eec2e9f41678
ms.date: 12/05/2018
ms.keywords: GetVersionString, GetVersionString method [Windows Runtime], GetVersionString method [Windows Runtime],IMetaDataImport2 interface, IMetaDataImport2 interface [Windows Runtime],GetVersionString method, IMetaDataImport2.GetVersionString, IMetaDataImport2::GetVersionString, rometadataapi/IMetaDataImport2::GetVersionString, winrt.imetadataimport2_getversionstring
ms.topic: method
f1_keywords:
- rometadataapi/IMetaDataImport2.GetVersionString
dev_langs:
- c++
req.header: rometadataapi.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: 
req.target-min-winversvr: 
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: Rometadataapi.idl
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
- rometadataapi.h
api_name:
- IMetaDataImport2.GetVersionString
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# IMetaDataImport2::GetVersionString


## -description


Gets the version number of the runtime that was used to build the assembly.


## -parameters




### -param pwzBuf [out]

An array to store the string that specifies the version.


### -param ccBufSize [in]

The size, in wide characters, of the <i>pwzBuf</i> array.


### -param pccBufSize [out]

The number of wide characters, including a null terminator, returned in the <i>pwzBuf</i> array.


## -returns



If this method succeeds, it returns <b xmlns:loc="http://microsoft.com/wdcml/l10n">S_OK</b>. Otherwise, it returns an <b xmlns:loc="http://microsoft.com/wdcml/l10n">HRESULT</b> error code.




## -remarks



The <b>GetVersionString</b> method gets the built-for version of the current metadata scope. If the scope has never been saved, it will not have a built-for version, and an empty string will be returned.




## -see-also




<a href="https://docs.microsoft.com/windows/desktop/api/rometadataapi/nn-rometadataapi-imetadataimport2">IMetaDataImport2</a>
 

 

