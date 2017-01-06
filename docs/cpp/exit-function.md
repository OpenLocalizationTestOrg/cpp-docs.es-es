---
title: exit Function | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: language-reference
f1_keywords:
- Exit
dev_langs:
- C++
helpviewer_keywords:
- exit function
ms.assetid: 26ce439f-81e2-431c-9ff8-a09a96f32127
caps.latest.revision: 6
author: mikeblome
ms.author: mblome
manager: ghogen
translation.priority.ht:
- cs-cz
- de-de
- es-es
- fr-fr
- it-it
- ja-jp
- ko-kr
- pl-pl
- pt-br
- ru-ru
- tr-tr
- zh-cn
- zh-tw
translationtype: Human Translation
ms.sourcegitcommit: 3168772cbb7e8127523bc2fc2da5cc9b4f59beb8
ms.openlocfilehash: a1cf92f44747ed8c0818bec28346ceb153dc547b

---
# exit Function
The **exit** function, declared in the standard include file STDLIB.H, terminates a C++ program.  
  
 The value supplied as an argument to **exit** is returned to the operating system as the program's return code or exit code. By convention, a return code of zero means that the program completed successfully.  
  
> [!NOTE]
>  You can use the constants `EXIT_FAILURE` and `EXIT_SUCCESS`, defined in STDLIB.H, to indicate success or failure of your program.  
  
 Issuing a `return` statement from the **main** function is equivalent to calling the **exit** function with the return value as its argument.  
  
 For more information, see [exit](../c-runtime-library/reference/exit-exit-exit.md) in the *Run-Time Library Reference*.  
  
## See Also  
 [Program Termination](../cpp/program-termination.md)


<!--HONumber=Jan17_HO1-->


