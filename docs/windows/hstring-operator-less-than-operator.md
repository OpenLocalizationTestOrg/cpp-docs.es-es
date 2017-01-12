---
title: HString::Operator&lt; Operator | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: reference
f1_keywords:
- corewrappers/Microsoft::WRL::Wrappers::HString::operator<
dev_langs:
- C++
ms.assetid: 48a051cb-4609-42be-b48c-d35fc99d1eab
caps.latest.revision: 2
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
ms.openlocfilehash: a76ae2ed7aa0be85672307d73680f07f7f4cd243

---
# HString::Operator&lt; Operator
Indicates whether the first parameter is less than the second parameter.  
  
## Syntax  
  
```cpp  
  
inline bool operator<(  
    const HString& lhs,   
    const HString& rhs) throw()  
  
```  
  
#### Parameters  
 `lhs`  
 The first parameter to compare. `lhs` can be a reference to an HString.  
  
 `rhs`  
 The second parameter to compare. `rhs` can be a reference to an HString.  
  
## Return Value  
 `true` if the `lhs` parameter is less than the `rhs` parameter; otherwise, `false`.  
  
## Requirements  
 **Header:** corewrappers.h  
  
 **Namespace:** Microsoft::WRL::Wrappers  
  
## See Also  
 [HString Class](../windows/hstring-class.md)


<!--HONumber=Jan17_HO2-->


