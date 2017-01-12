---
title: __writeeflags | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: article
f1_keywords:
- __writeeflags
dev_langs:
- C++
helpviewer_keywords:
- __writeeflags intrinsics
ms.assetid: a62a522c-d7fa-4f10-a620-a3b32bdf3f17
caps.latest.revision: 5
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
ms.openlocfilehash: 5fa94a862b8f3704f5b771550455c88fc9142dee

---
# __writeeflags
Writes the specified value to the program status and control (EFLAGS) register.  
  
## Syntax  
  
```  
void __writeeflags(unsigned Value);  
void __writeeflags(unsigned __int64 Value);  
```  
  
#### Parameters  
  
|Parameter|Description|  
|---------------|-----------------|  
|[in] `Value`|The value to write to the EFLAGS register. The `Value` parameter is 32 bits long for a 32-bit platform and 64 bits long for a 64-bit platform.|  
  
## Remarks  
 These routines are available only as intrinsics.  
  
## Requirements  
  
|Intrinsic|Architecture|  
|---------------|------------------|  
|`__writeeflags`|x86, [!INCLUDE[vcprx64](../assembler/inline/includes/vcprx64_md.md)]|  
  
 **Header file** \<intrin.h>  
  
## END Microsoft Specific  
  
## See Also  
 [Compiler Intrinsics](../intrinsics/compiler-intrinsics.md)   
 [__readeflags](../intrinsics/readeflags.md)


<!--HONumber=Jan17_HO2-->


