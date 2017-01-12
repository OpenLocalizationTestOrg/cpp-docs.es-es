---
title: ComPtrRef::GetAddressOf Method | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: reference
f1_keywords:
- client/Microsoft::WRL::Details::ComPtrRef::GetAddressOf
dev_langs:
- C++
helpviewer_keywords:
- GetAddressOf method
ms.assetid: 797df323-a2fa-412b-ab60-32cce3721096
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
ms.openlocfilehash: d53acb8749896ed1633e7c7bd8b8773a01efefe3

---
# ComPtrRef::GetAddressOf Method
Supports the WRL infrastructure and is not intended to be used directly from your code.  
  
## Syntax  
  
```  
InterfaceType* const * GetAddressOf() const;  
```  
  
## Return Value  
 Address of a pointer to the interface represented by the current ComPtrRef object.  
  
## Remarks  
 Retrieves the address of a pointer to the interface represented by the current ComPtrRef object.  
  
## Requirements  
 **Header:** client.h  
  
 **Namespace:** Microsoft::WRL::Details  
  
## See Also  
 [ComPtrRef Class](../windows/comptrref-class.md)   
 [Microsoft::WRL::Details Namespace](../windows/microsoft-wrl-details-namespace.md)


<!--HONumber=Jan17_HO2-->


