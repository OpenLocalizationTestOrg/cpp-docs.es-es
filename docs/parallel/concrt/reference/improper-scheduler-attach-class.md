---
title: improper_scheduler_attach Class | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: article
f1_keywords:
- concrt/concurrency::improper_scheduler_attach
dev_langs:
- C++
helpviewer_keywords:
- improper_scheduler_attach class
ms.assetid: 5a76da0a-091b-4748-8f62-b3a28f674f9e
caps.latest.revision: 19
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
ms.sourcegitcommit: fa774c7f025b581d65c28d65d83e22ff2d798230
ms.openlocfilehash: 06e7b04d0c5a938e1e7faac2a1ee43804f5040bf

---
# improper_scheduler_attach Class
This class describes an exception thrown when the `Attach` method is called on a `Scheduler` object which is already attached to the current context.  
  
## Syntax  
  
```
class improper_scheduler_attach : public std::exception;
```  
  
## Members  
  
### Public Constructors  
  
|Name|Description|  
|----------|-----------------|  
|[improper_scheduler_attach::improper_scheduler_attach Constructor](#ctor)|Overloaded. Constructs an `improper_scheduler_attach` object.|  
  
## Inheritance Hierarchy  
 `exception`  
  
 `improper_scheduler_attach`  
  
## Requirements  
 **Header:** concrt.h  
  
 **Namespace:** concurrency  
  
##  <a name="ctor"></a>  improper_scheduler_attach::improper_scheduler_attach Constructor  
 Constructs an `improper_scheduler_attach` object.  
  
```
explicit _CRTIMP improper_scheduler_attach(_In_z_ const char* _Message) throw();

improper_scheduler_attach() throw();
```  
  
### Parameters  
 `_Message`  
 A descriptive message of the error.  
  
## See Also  
 [concurrency Namespace](concurrency-namespace.md)   
 [Scheduler Class](scheduler-class.md)



<!--HONumber=Jan17_HO2-->


