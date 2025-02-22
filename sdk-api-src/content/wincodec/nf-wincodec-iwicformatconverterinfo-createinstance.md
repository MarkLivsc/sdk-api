---
UID: NF:wincodec.IWICFormatConverterInfo.CreateInstance
title: IWICFormatConverterInfo::CreateInstance (wincodec.h)
description: Creates a new IWICFormatConverter instance.
old-location: wic\_wic_codec_iwicformatconverterinfo_createinstance.htm
tech.root: wic
ms.assetid: 5b0f2cac-6bd7-46a8-884c-89735f3968a0
ms.date: 12/05/2018
ms.keywords: CreateInstance, CreateInstance method [Windows Imaging Component], CreateInstance method [Windows Imaging Component],IWICFormatConverterInfo interface, IWICFormatConverterInfo interface [Windows Imaging Component],CreateInstance method, IWICFormatConverterInfo.CreateInstance, IWICFormatConverterInfo::CreateInstance, _wic_codec_iwicformatconverterinfo_createinstance, wic._wic_codec_iwicformatconverterinfo_createinstance, wincodec/IWICFormatConverterInfo::CreateInstance
ms.topic: method
f1_keywords:
- wincodec/IWICFormatConverterInfo.CreateInstance
dev_langs:
- c++
req.header: wincodec.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows XP with SP2, Windows Vista [desktop apps \| UWP apps]
req.target-min-winversvr: Windows Server 2008 [desktop apps \| UWP apps]
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: Wincodec.idl
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: Windowscodecs.lib
req.dll: Windowscodecs.dll
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- COM
api_location:
- Windowscodecs.dll
api_name:
- IWICFormatConverterInfo.CreateInstance
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# IWICFormatConverterInfo::CreateInstance


## -description


Creates a new <a href="https://docs.microsoft.com/windows/desktop/api/wincodec/nn-wincodec-iwicformatconverter">IWICFormatConverter</a> instance.


## -parameters




### -param ppIConverter [out]

Type: <b><a href="https://docs.microsoft.com/windows/desktop/api/wincodec/nn-wincodec-iwicformatconverter">IWICFormatConverter</a>**</b>

A pointer that receives a new <a href="https://docs.microsoft.com/windows/desktop/api/wincodec/nn-wincodec-iwicformatconverter">IWICFormatConverter</a> instance.


## -returns



Type: <b>HRESULT</b>

If this method succeeds, it returns <b xmlns:loc="http://microsoft.com/wdcml/l10n">S_OK</b>. Otherwise, it returns an <b xmlns:loc="http://microsoft.com/wdcml/l10n">HRESULT</b> error code.



