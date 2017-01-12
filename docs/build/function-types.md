---
title: Function Types | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: article
dev_langs:
- C++
ms.assetid: 7e33d5f4-dabb-406d-afb3-13777b995028
caps.latest.revision: 7
author: corob-msft
ms.author: corob
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
ms.openlocfilehash: f537c763e0579d534b65188cc98e31abccf1ea26

---
# Function Types
There are basically two types of functions. A function that requires a stack frame is called a frame function. A function that does not require a stack frame is called a leaf function.  
  
 A frame function is a function that allocates stack space, calls other functions, saves nonvolatile registers, or uses exception handling. It also requires a function table entry. A frame function requires a prolog and an epilog. A frame function can dynamically allocate stack space and can employ a frame pointer. A frame function has the full capabilities of this calling standard at its disposal.  
  
 If a frame function does not call another function then it is not required to align the stack (referenced in Section [Stack Allocation](../build/stack-allocation.md)).  
  
 A leaf function is one that does not require a function table entry. It cannot call any functions, allocate space, or save any nonvolatile registers. It is allowed to leave the stack unaligned while it executes.  
  
## See Also  
 [Stack Usage](../build/stack-usage.md)


<!--HONumber=Jan17_HO2-->


