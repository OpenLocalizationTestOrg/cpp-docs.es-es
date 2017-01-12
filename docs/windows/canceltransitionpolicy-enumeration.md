---
title: CancelTransitionPolicy Enumeration | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: reference
f1_keywords:
- module/Microsoft::WRL::CancelTransitionPolicy::TransitionFromCanceled
- module/Microsoft::WRL::CancelTransitionPolicy::RemainCanceled
- module/Microsoft::WRL::CancelTransitionPolicy
dev_langs:
- C++
helpviewer_keywords:
- CancelTransitionPolicy Enumeration
ms.assetid: 5de49f7d-e5e3-43e9-bbca-666caf226cef
caps.latest.revision: 3
author: mikeblome
ms.author: mblome
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
ms.openlocfilehash: 33ce2b34c05a9ad84bfeffdc4ecd070d883d792b

---
# CancelTransitionPolicy Enumeration
Indicates how an asynchronous operation’s attempt to transition to a terminal state of completed or error should behave with respect to a client-requested canceled state.  
  
## Syntax  
  
```  
enum CancelTransitionPolicy;  
```  
  
## Members  
  
### Values  
  
|Name|Description|  
|----------|-----------------|  
|`RemainCanceled`|If the asynchronous operation is currently in a client-requested canceled state, this indicates that it will stay in the canceled state as opposed to transitioning to a terminal completed or error state.|  
|`TransitionFromCanceled`|If the asynchronous operation is currently in a client-requested canceled state, this indicates that state should transition from that canceled state to the terminal state of completed or error as determined by the call that utilizes this flag.|  
  
## Requirements  
 **Header:** async.h  
  
 **Namespace:** Microsoft::WRL  
  
## See Also  
 [Microsoft::WRL Namespace](../windows/microsoft-wrl-namespace.md)


<!--HONumber=Jan17_HO2-->


