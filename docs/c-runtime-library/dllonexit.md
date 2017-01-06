---
title: __dllonexit | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: article
apiname:
- __dllonexit
apilocation:
- msvcrt.dll
- msvcr110.dll
- msvcr110_clr0400.dll
- msvcr100.dll
- msvcr80.dll
- msvcr120.dll
- msvcr90.dll
- msvcr120_clr0400.dll
apitype: DLLExport
f1_keywords:
- __dllonexit
dev_langs:
- C++
helpviewer_keywords:
- __dllonexit
ms.assetid: 708f2ceb-f95c-46b0-a58d-d68b3fa36f12
caps.latest.revision: 4
author: corob-msft
ms.author: corob
manager: ghogen
translation.priority.ht:
- de-de
- es-es
- fr-fr
- it-it
- ja-jp
- ko-kr
- ru-ru
- zh-cn
- zh-tw
translation.priority.mt:
- cs-cz
- pl-pl
- pt-br
- tr-tr
translationtype: Human Translation
ms.sourcegitcommit: 3168772cbb7e8127523bc2fc2da5cc9b4f59beb8
ms.openlocfilehash: 71b7a0e79f254c83459c32408ea85e91b3b92e5f

---
# __dllonexit
Registers a routine to be called at exit time.  
  
## Syntax  
  
```  
_onexit_t __dllonexit(   _onexit_t func,  
   _PVFV **  pbegin,   
   _PVFV **  pend   
   )  
```  
  
#### Parameters  
 `func`  
 Pointer to a function to be executed upon exit.  
  
 `pbegin`  
 Pointer to a variable that points to the beginning of a list of functions to execute on detach.  
  
 `pend`  
 Pointer to variable that points to the end of a list of functions to execute on detach.  
  
## Return Value  
 If successful, a pointer to the user’s function. Otherwise, a NULL pointer.  
  
## Remarks  
 The `__dllonexit` function is analogous to the [_onexit](../c-runtime-library/reference/onexit-onexit-m.md) function except that the global variables used by that function are not visible to this routine. Instead of global variables, this function uses the `pbegin` and `pend` parameters.  
  
 The `_onexit` and `atexit` functions in a DLL linked with MSVCRT.LIB must maintain their own atexit/_onexit list. This routine is the worker that gets called by such DLLs.  
  
 The `_PVFV` type is defined as `typedef void (__cdecl *_PVFV)(void)`.  
  
## Requirements  
  
|Routine|Required file|  
|-------------|-------------------|  
|__dllonexit|onexit.c|  
  
## See Also  
 [_onexit, _onexit_m](../c-runtime-library/reference/onexit-onexit-m.md)


<!--HONumber=Jan17_HO1-->


