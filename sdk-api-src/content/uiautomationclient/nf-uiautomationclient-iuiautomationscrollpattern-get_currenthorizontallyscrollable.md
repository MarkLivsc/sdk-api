---
UID: NF:uiautomationclient.IUIAutomationScrollPattern.get_CurrentHorizontallyScrollable
title: IUIAutomationScrollPattern::get_CurrentHorizontallyScrollable (uiautomationclient.h)
description: Indicates whether the element can scroll horizontally.
old-location: winauto\uiauto_IUIAutomationScrollPattern_CurrentHorizontallyScrollable.htm
tech.root: WinAuto
ms.assetid: 4107440a-4bfc-42df-87b0-47b9eb3ce2e6
ms.date: 12/05/2018
ms.keywords: CurrentHorizontallyScrollable property [Windows Accessibility], CurrentHorizontallyScrollable property [Windows Accessibility],IUIAutomationScrollPattern interface, IUIAutomationScrollPattern interface [Windows Accessibility],CurrentHorizontallyScrollable property, IUIAutomationScrollPattern.CurrentHorizontallyScrollable, IUIAutomationScrollPattern.get_CurrentHorizontallyScrollable, IUIAutomationScrollPattern::CurrentHorizontallyScrollable, IUIAutomationScrollPattern::get_CurrentHorizontallyScrollable, get_CurrentHorizontallyScrollable, uiauto.uiauto_IUIAutomationScrollPattern_CurrentHorizontallyScrollable, uiauto_IUIAutomationScrollPattern_CurrentHorizontallyScrollable, uiautomationclient/IUIAutomationScrollPattern::CurrentHorizontallyScrollable, uiautomationclient/IUIAutomationScrollPattern::get_CurrentHorizontallyScrollable, winauto.uiauto_IUIAutomationScrollPattern_CurrentHorizontallyScrollable
ms.topic: method
f1_keywords:
- uiautomationclient/IUIAutomationScrollPattern.CurrentHorizontallyScrollable
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
- IUIAutomationScrollPattern.CurrentHorizontallyScrollable
- IUIAutomationScrollPattern.get_CurrentHorizontallyScrollable
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# IUIAutomationScrollPattern::get_CurrentHorizontallyScrollable


## -description


Indicates whether the element can scroll horizontally.

This property is read-only.


## -parameters


## -remarks



This property can be dynamic. For example, the content area of the element might not be larger than the current viewable area, meaning that the property is <b>FALSE</b>. However, resizing the element or adding child items can increase the bounds of the content area beyond the viewable area, making the property <b>TRUE</b>.




## -see-also




<a href="https://docs.microsoft.com/windows/desktop/api/uiautomationclient/nn-uiautomationclient-iuiautomationscrollpattern">IUIAutomationScrollPattern</a>



<a href="https://docs.microsoft.com/windows/desktop/api/uiautomationclient/nf-uiautomationclient-iuiautomationscrollpattern-get_currentverticallyscrollable">IUIAutomationScrollPattern::CurrentVerticallyScrollable</a>
 

 

