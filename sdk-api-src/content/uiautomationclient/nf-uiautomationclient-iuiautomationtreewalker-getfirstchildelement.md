---
UID: NF:uiautomationclient.IUIAutomationTreeWalker.GetFirstChildElement
title: IUIAutomationTreeWalker::GetFirstChildElement (uiautomationclient.h)
description: Retrieves the first child element of the specified UI Automation element.
old-location: winauto\uiauto_IUIAutomationTreeWalker_GetFirstChild.htm
tech.root: WinAuto
ms.assetid: 2f1df27c-664b-451a-8a1f-e4dbc70b1845
ms.date: 12/05/2018
ms.keywords: GetFirstChildElement, GetFirstChildElement method [Windows Accessibility], GetFirstChildElement method [Windows Accessibility],IUIAutomationTreeWalker interface, IUIAutomationTreeWalker interface [Windows Accessibility],GetFirstChildElement method, IUIAutomationTreeWalker.GetFirstChildElement, IUIAutomationTreeWalker::GetFirstChildElement, uiauto.uiauto_IUIAutomationTreeWalker_GetFirstChild, uiauto_IUIAutomationTreeWalker_GetFirstChild, uiautomationclient/IUIAutomationTreeWalker::GetFirstChildElement, winauto.uiauto_IUIAutomationTreeWalker_GetFirstChild
ms.topic: method
f1_keywords:
- uiautomationclient/IUIAutomationTreeWalker.GetFirstChildElement
dev_langs:
- c++
req.header: uiautomationclient.h
req.include-header: UIAutomation.h
req.target-type: Windows
req.target-min-winverclnt: Windows 7, Windows Vista with SP2 and Platform Update for Windows Vista, Windows XP with SP3 and Platform Update for Windows Vista [desktop apps only]
req.target-min-winversvr: Windows Server 2008 R2, Windows Server 2008 with SP2 and Platform Update for Windows Server 2008, Windows Server 2003 with SP2 and Platform Update for Windows Server 2008 [desktop apps only]
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: UIAutomationClient.idl
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
- UIAutomationClient.h
api_name:
- IUIAutomationTreeWalker.GetFirstChildElement
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# IUIAutomationTreeWalker::GetFirstChildElement


## -description


Retrieves the first child element of the specified UI Automation element.


## -parameters




### -param element [in]

Type: <b><a href="https://docs.microsoft.com/windows/desktop/api/uiautomationclient/nn-uiautomationclient-iuiautomationelement">IUIAutomationElement</a>*</b>

A pointer to  the element for which to retrieve the first child.


### -param first [out, retval]

Type: <b><a href="https://docs.microsoft.com/windows/desktop/api/uiautomationclient/nn-uiautomationclient-iuiautomationelement">IUIAutomationElement</a>**</b>

Receives a pointer to the first child element.


## -returns



Type: <b><a href="https://docs.microsoft.com/windows/desktop/WinProg/windows-data-types">HRESULT</a></b>

If this method succeeds, it returns <b xmlns:loc="http://microsoft.com/wdcml/l10n">S_OK</b>. Otherwise, it returns an <b xmlns:loc="http://microsoft.com/wdcml/l10n">HRESULT</b> error code.




## -remarks



An element can have additional child elements that do not match the current view condition and thus are not returned when navigating the element tree.

The structure of the Microsoft UI Automation tree changes as the visible UI elements on the desktop change. It is not guaranteed that an element returned as the first child element will be returned as the first child on subsequent passes.



