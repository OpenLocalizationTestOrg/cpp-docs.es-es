---
title: ComPtrRef::ComPtrRef Constructor | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: reference
f1_keywords:
- client/Microsoft::WRL::Details::ComPtrRef::ComPtrRef
dev_langs:
- C++
helpviewer_keywords:
- ComPtrRef, constructor
ms.assetid: ce2d2533-fef6-4b2d-b088-6f3db01df5a5
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
ms.openlocfilehash: d38cd5317cb0e321d6be38523e8ac1672a5f2f2c

---
# ComPtrRef::ComPtrRef Constructor
Supports the WRL infrastructure and is not intended to be used directly from your code.  
  
## Syntax  
  
```  
ComPtrRef(  
   _In_opt_ T* ptr  
);  
```  
  
#### Parameters  
 `ptr`  
 The underlying value of another ComPtrRef object.  
  
## Remarks  
 Initializes a new instance of the ComPtrRef class from the specified pointer to another ComPtrRef object.  
  
## Requirements  
 **Header:** client.h  
  
 **Namespace:** Microsoft::WRL::Details  
  
## See Also  
 [ComPtrRef Class](../windows/comptrref-class.md)   
 [Microsoft::WRL::Details Namespace](../windows/microsoft-wrl-details-namespace.md)


<!--HONumber=Jan17_HO2-->


