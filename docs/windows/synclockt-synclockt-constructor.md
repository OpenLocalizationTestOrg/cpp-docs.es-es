---
title: SyncLockT::SyncLockT Constructor | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: reference
f1_keywords:
- corewrappers/Microsoft::WRL::Wrappers::Details::SyncLockT::SyncLockT
dev_langs:
- C++
helpviewer_keywords:
- SyncLockT, constructor
ms.assetid: 713dfd9f-7369-4d86-b4a0-8b32c184d89b
caps.latest.revision: 4
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
ms.openlocfilehash: 09e462f6a734b7131911e40add6b92d8543d4446

---
# SyncLockT::SyncLockT Constructor
Supports the WRL infrastructure and is not intended to be used directly from your code.  
  
## Syntax  
  
```  
SyncLockT(  
   _Inout_ SyncLockT&& other  
);  
  
explicit SyncLockT(  
   typename SyncTraits::Type sync = SyncTraits::GetInvalidValue()  
);  
```  
  
#### Parameters  
 `other`  
 An rvalue-reference to another SyncLockT object.  
  
 `sync`  
 A reference to another SyncLockWithStatusT object.  
  
## Remarks  
 Initializes a new instance of the SyncLockT class.  
  
 The first constructor initializes the current SyncLockT object from another SyncLockT object specified by parameter `other`, and then invalidates the other SyncLockT object. The second constructor is `protected`, and initializes the current SyncLockT object to an invalid state.  
  
## Requirements  
 **Header:** corewrappers.h  
  
 **Namespace:** Microsoft::WRL::Wrappers::Details  
  
## See Also  
 [SyncLockT Class](../windows/synclockt-class.md)


<!--HONumber=Jan17_HO2-->


