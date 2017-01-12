---
title: Compiler Error C3539 | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: error-reference
f1_keywords:
- C3539
dev_langs:
- C++
helpviewer_keywords:
- C3539
ms.assetid: 34a33a0f-d1b6-498f-b312-ffad2d4799b3
caps.latest.revision: 6
author: corob-msft
ms.author: corob
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
ms.sourcegitcommit: 3168772cbb7e8127523bc2fc2da5cc9b4f59beb8
ms.openlocfilehash: f7e9f8d260d17d7561077aabb0dfc26bf20f8c07

---
# Compiler Error C3539
'type': a template-argument cannot be a type that contains 'auto'  
  
 The indicated template argument type cannot contain a usage of the `auto` keyword.  
  
### To correct this error  
  
1.  Do not specify the template argument with the `auto` keyword.  
  
## Example  
 The following example yields C3539.  
  
```  
// C3539.cpp  
// Compile with /Zc:auto  
template<class T> class C{};  
int main()  
{  
   C<auto> c;   // C3539  
   return 0;  
}  
```  
  
## See Also  
 [auto Keyword](../../cpp/auto-keyword.md)


<!--HONumber=Jan17_HO2-->


