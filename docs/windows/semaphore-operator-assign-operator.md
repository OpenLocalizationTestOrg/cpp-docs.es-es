---
title: Semaphore::operator= Operator | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: reference
f1_keywords:
- corewrappers/Microsoft::WRL::Wrappers::Semaphore::operator=
dev_langs:
- C++
helpviewer_keywords:
- operator= operator
ms.assetid: ea19839f-91f0-4b00-a35b-5728fcba4981
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
ms.openlocfilehash: e1cf69478b158b74157b3a105a1b2c102b2ce91f

---
# Semaphore::operator= Operator
Moves the specified handle from a Semaphore object to the current Semaphore object.  
  
## Syntax  
  
```  
Semaphore& operator=(  
   _Inout_ Semaphore&& h  
);  
```  
  
#### Parameters  
 `h`  
 Rvalue-reference to a Semaphore object.  
  
## Return Value  
 A reference to the current Semaphore object.  
  
## Requirements  
 **Header:** corewrappers.h  
  
 **Namespace:** Microsoft::WRL::Wrappers
 
 ## See Also
 [Semaphore Class](../windows/semaphore-class.md)


<!--HONumber=Jan17_HO2-->


