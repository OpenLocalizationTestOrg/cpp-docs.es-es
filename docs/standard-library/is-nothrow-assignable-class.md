---
title: is_nothrow_assignable Class | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- cpp
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: language-reference
f1_keywords:
- is_nothrow_assignable
- std.is_nothrow_assignable
- std::is_nothrow_assignable
- type_traits/std::is_nothrow_assignable
dev_langs:
- C++
- c++
helpviewer_keywords:
- is_nothrow_assignable
ms.assetid: aa3aca92-308b-4b1d-b3f3-c54216c48fe7
caps.latest.revision: 13
author: corob-msft
ms.author: corob
manager: ghogen
translation.priority.mt:
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
translationtype: Machine Translation
ms.sourcegitcommit: 3168772cbb7e8127523bc2fc2da5cc9b4f59beb8
ms.openlocfilehash: 10062f34520098e0ecc3f2fa8cb3ad96b25c252c

---
# is_nothrow_assignable Class
Tests whether a value of `From` type can be assigned to `To` type and the assignment is known not to throw.  
  
## Syntax  
  
```
template <class To, class From>  
struct is_nothrow_assignable;
```  
  
#### Parameters  
 To  
 The type of the object that receives the assignment.  
  
 From  
 The type of the object that provides the value.  
  
## Remarks  
 The expression `declval<To>() = declval<From>()` must be well-formed and must be known to the compiler not to throw. Both `From` and `To` must be complete types, `void`, or arrays of unknown bound.  
  
## Requirements  
 **Header:** <type_traits>  
  
 **Namespace:** std  
  
## See Also  
 [<type_traits>](../standard-library/type-traits.md)






<!--HONumber=Jan17_HO2-->


