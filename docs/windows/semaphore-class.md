---
title: Semaphore Class | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: reference
f1_keywords:
- corewrappers/Microsoft::WRL::Wrappers::Semaphore
dev_langs:
- C++
helpviewer_keywords:
- Semaphore class
ms.assetid: ded53526-17b4-4381-9c60-ea5e77363db6
caps.latest.revision: 5
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
ms.openlocfilehash: ab9a7a1bed2d708a7c2b8d262ac9e075d3164745

---
# Semaphore Class
Represents a synchronization object that controls a shared resource that can support a limited number of users.  
  
## Syntax  
  
```  
  
class Semaphore : public HandleT<HandleTraits::SemaphoreTraits>  
```  
  
## Members  
  
### Public Typedefs  
  
|Name|Description|  
|----------|-----------------|  
|`SyncLock`|A synonym for a class that supports synchronous locks.|  
  
### Public Constructors  
  
|Name|Description|  
|----------|-----------------|  
|[Semaphore::Semaphore Constructor](../windows/semaphore-semaphore-constructor.md)|Initializes a new instance of the Semaphore class.|  
  
### Public Methods  
  
|Name|Description|  
|----------|-----------------|  
|[InvokeHelper::Invoke Method](../windows/invokehelper-invoke-method.md)|Calls the event handler whose signature contains the specified number of arguments.|  
  
### Public Data Members  
  
|Name|Description|  
|----------|-----------------|  
|[Semaphore::Lock Method](../windows/semaphore-lock-method.md)|Waits until the current object, or the object associated with the specified handle, is in the signaled state or the specified time-out interval has elapsed.|  
  
### Public Operators  
  
|Name|Description|  
|----------|-----------------|  
|[Semaphore::operator= Operator](../windows/semaphore-operator-assign-operator.md)|Moves the specified handle from a Semaphore object to the current Semaphore object.|  
  
## Inheritance Hierarchy  
 `Semaphore`  
  
## Requirements  
 **Header:** corewrappers.h  
  
 **Namespace:** Microsoft::WRL::Wrappers  
  
## See Also  
 [Microsoft::WRL::Wrappers Namespace](../windows/microsoft-wrl-wrappers-namespace.md)


<!--HONumber=Jan17_HO2-->


