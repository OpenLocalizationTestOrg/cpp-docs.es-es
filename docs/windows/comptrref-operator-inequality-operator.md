---
title: ComPtrRef::operator!= Operator | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: reference
f1_keywords:
- client/Microsoft::WRL::Details::ComPtrRef::operator!=
dev_langs:
- C++
ms.assetid: ab3093cc-6fbd-4039-890a-6df1cde992b6
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
ms.openlocfilehash: 2a8d69ec9a19b8a29fb34d694e50dbd851c19e30

---
# ComPtrRef::operator!= Operator
Supports the WRL infrastructure and is not intended to be used directly from your code.  
  
## Syntax  
  
```cpp  
  
bool operator!=(  
   const Details::ComPtrRef<ComPtr<T>>& a,  
   const Details::ComPtrRef<ComPtr<U>>& b  
);  
  
bool operator!=(  
   const Details::ComPtrRef<ComPtr<T>>& a,  
   decltype(__nullptr)  
);  
  
bool operator!=(  
   decltype(__nullptr),  
   const Details::ComPtrRef<ComPtr<T>>& a  
);  
  
bool operator!=(  
   const Details::ComPtrRef<ComPtr<T>>& a,  
   void* b  
);  
  
bool operator!=(  
   void* b,  
   const Details::ComPtrRef<ComPtr<T>>& a  
);  
```  
  
#### Parameters  
 `a`  
 A reference to a ComPtrRef object.  
  
 `b`  
 A reference to another ComPtrRef object, or a pointer to an anonymous object (`void*`).  
  
## Return Value  
 The first operator yields `true` if object `a` is not equal to object `b`; otherwise, `false`.  
  
 The second and third operators yield `true` if object `a` is not equal to `nullptr`; otherwise, `false`.  
  
 The fourth and fifth operators yield `true` if object `a` is not equal to object `b`; otherwise, `false`.  
  
## Remarks  
 Indicates whether two ComPtrRef objects are not equal.  
  
## Requirements  
 **Header:** client.h  
  
 **Namespace:** Microsoft::WRL  
  
## See Also  
 [Microsoft::WRL::Details Namespace](../windows/microsoft-wrl-details-namespace.md)   
 [ComPtrRef Class](../windows/comptrref-class.md)


<!--HONumber=Jan17_HO2-->


