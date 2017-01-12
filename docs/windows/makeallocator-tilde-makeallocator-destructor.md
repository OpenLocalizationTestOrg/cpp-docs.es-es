---
title: MakeAllocator::~MakeAllocator Destructor | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: reference
f1_keywords:
- implements/Microsoft::WRL::Details::MakeAllocator::~MakeAllocator
dev_langs:
- C++
helpviewer_keywords:
- ~MakeAllocator, destructor
ms.assetid: f1299c5f-cc6b-4d4e-85d4-aee1be0e2b0a
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
ms.openlocfilehash: b434659e6114ec7f48433eae0d1601b9f7f3865d

---
# MakeAllocator::~MakeAllocator Destructor
Supports the WRL infrastructure and is not intended to be used directly from your code.  
  
## Syntax  
  
```  
~MakeAllocator();  
```  
  
## Remarks  
 Deinitializes the current instance of the MakeAllocator class.  
  
 This destructor also deletes the underlying allocated memory if necessary.  
  
## Requirements  
 **Header:** implements.h  
  
 **Namespace:** Microsoft::WRL::Details  
  
## See Also  
 [MakeAllocator Class](../windows/makeallocator-class.md)   
 [Microsoft::WRL::Details Namespace](../windows/microsoft-wrl-details-namespace.md)


<!--HONumber=Jan17_HO2-->


