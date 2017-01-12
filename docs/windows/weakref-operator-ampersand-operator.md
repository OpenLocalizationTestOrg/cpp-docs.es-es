---
title: WeakRef::operator&amp; Operator | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: reference
f1_keywords:
- client/Microsoft::WRL::WeakRef::operator&
dev_langs:
- C++
helpviewer_keywords:
- operator& operator
ms.assetid: 900afb73-3801-4d08-9b41-2e6a62011ccd
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
ms.openlocfilehash: 5ac85d4d9c2335072f66b25a6753ea4f7f3a69f0

---
# WeakRef::operator&amp; Operator
Returns a ComPtrRef object that represents the current WeakRef object.  
  
## Syntax  
  
```cpp  
Details::ComPtrRef<WeakRef> operator&() throw()  
```  
  
## Return Value  
 A ComPtrRef object that represents the current WeakRef object.  
  
## Remarks  
 This is an internal helper operator that is not meant to be used in your code.  
  
## Requirements  
 **Header:** client.h  
  
 **Namespace:** Microsoft::WRL  
  
## See Also  
 [WeakRef Class](../windows/weakref-class.md)


<!--HONumber=Jan17_HO2-->


