---
UID: NF:processthreadsapi.GetProcessPriorityBoost
title: GetProcessPriorityBoost function (processthreadsapi.h)
description: Retrieves the priority boost control state of the specified process.
old-location: base\getprocesspriorityboost.htm
tech.root: ProcThread
ms.assetid: b47944f2-b724-4eec-9dcf-2d14a7b77456
ms.date: 12/05/2018
ms.keywords: GetProcessPriorityBoost, GetProcessPriorityBoost function, _win32_getprocesspriorityboost, base.getprocesspriorityboost, processthreadsapi/GetProcessPriorityBoost
ms.topic: function
f1_keywords:
- processthreadsapi/GetProcessPriorityBoost
dev_langs:
- c++
req.header: processthreadsapi.h
req.include-header: Windows.h
req.target-type: Windows
req.target-min-winverclnt: Windows XP [desktop apps \| UWP apps]
req.target-min-winversvr: Windows Server 2003 [desktop apps \| UWP apps]
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: Kernel32.lib
req.dll: Kernel32.dll
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- DllExport
api_location:
- Kernel32.dll
- API-MS-Win-Core-ProcessThreads-l1-1-2.dll
- KernelBase.dll
- MinKernelBase.dll
- api-ms-win-downlevel-kernel32-l1-1-0.dll
- API-MS-Win-Core-ProcessThreads-L1-1-3.dll
api_name:
- GetProcessPriorityBoost
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# GetProcessPriorityBoost function


## -description


Retrieves the priority boost control state of the specified process.


## -parameters




### -param hProcess [in]

A handle to the process. This handle must have the <b>PROCESS_QUERY_INFORMATION</b> or <b>PROCESS_QUERY_LIMITED_INFORMATION</b> access right. For more information, see 
<a href="https://docs.microsoft.com/windows/desktop/ProcThread/process-security-and-access-rights">Process Security and Access Rights</a>.

<b>Windows Server 2003 and Windows XP:  </b>The handle must have the <b>PROCESS_QUERY_INFORMATION</b> access right.


### -param pDisablePriorityBoost [out]

A pointer to a variable that receives the priority boost control state. A value of TRUE indicates that dynamic boosting is disabled. A value of FALSE indicates normal behavior.


## -returns



If the function succeeds, the return value is nonzero. In that case, the variable pointed to by the <i>pDisablePriorityBoost</i> parameter receives the priority boost control state.

If the function fails, the return value is zero. To get extended error information, call 
<a href="https://docs.microsoft.com/windows/desktop/api/errhandlingapi/nf-errhandlingapi-getlasterror">GetLastError</a>.




## -see-also




<a href="https://docs.microsoft.com/windows/desktop/ProcThread/priority-boosts">Priority Boosts</a>



<a href="https://docs.microsoft.com/windows/desktop/ProcThread/process-and-thread-functions">Process and Thread Functions</a>



<a href="https://docs.microsoft.com/windows/desktop/ProcThread/child-processes">Processes</a>



<a href="https://docs.microsoft.com/windows/desktop/ProcThread/scheduling-priorities">Scheduling Priorities</a>



<a href="https://docs.microsoft.com/windows/desktop/api/processthreadsapi/nf-processthreadsapi-setprocesspriorityboost">SetProcessPriorityBoost</a>
 

 

