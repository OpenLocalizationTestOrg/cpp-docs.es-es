---
title: Compiler Error C3533 | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: error-reference
f1_keywords:
- C3533
dev_langs:
- C++
helpviewer_keywords:
- C3533
ms.assetid: a68b1ba5-466e-4190-a1a4-505ccfe548b7
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
ms.openlocfilehash: 73a9efca8245d4d83e8e9cda05c54a502607ea51

---
# Compiler Error C3533
'type': a parameter cannot have a type that contains 'auto'  
  
 A method or template parameter cannot be declared with the `auto` keyword if the default [/Zc:auto](../../build/reference/zc-auto-deduce-variable-type.md) compiler option is in effect.  
  
### To correct this error  
  
1.  Remove the `auto` keyword from the parameter declaration.  
  
## Example  
 The following example yields C3535 because it declares a function parameter with the `auto` keyword and it is compiled with **/Zc:auto**.  
  
```  
// C3533a.cpp  
// Compile with /Zc:auto  
void f(auto j){} // C3533  
```  
  
## Example  
 The following example yields C3535 because it declares a template parameter with the `auto` keyword and it is compiled with **/Zc:auto**.  
  
```  
// C3533b.cpp  
// Compile with /Zc:auto  
template<auto T> class C{}; // C3533  
```  
  
## See Also  
 [auto Keyword](../../cpp/auto-keyword.md)   
 [/Zc:auto (Deduce Variable Type)](../../build/reference/zc-auto-deduce-variable-type.md)


<!--HONumber=Jan17_HO2-->


