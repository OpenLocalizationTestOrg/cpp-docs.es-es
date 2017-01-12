---
title: Compiler Error C2561 | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: error-reference
f1_keywords:
- C2561
dev_langs:
- C++
helpviewer_keywords:
- C2561
ms.assetid: 0abe955b-53a6-4a3c-8362-b1a8eb40e8d1
caps.latest.revision: 9
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
ms.openlocfilehash: 9f6a436024bcb48c67f4ef28c4ca94baaf5375d4

---
# Compiler Error C2561
'identifier' : function must return a value  
  
 The function was declared as returning a value, but the function definition does not contain a `return` statement.  
  
 This error can be caused by an incorrect function prototype:  
  
1.  If the function does not return a value, declare the function with return type [void](../../cpp/void-cpp.md).  
  
2.  Check that all possible branches of the function return a value of the type declared in the prototype.  
  
3.  C++ functions containing inline assembly routines that store the return value in the `AX` register may need a return statement. Copy the value in `AX` to a temporary variable and return that variable from the function.  
  
 The following sample generates C2561:  
  
```  
// C2561.cpp  
int Test(int x) {  
   if (x) {  
      return;   // C2561  
      // try the following line instead  
      // return 1;  
   }  
   return 0;  
}  
  
int main() {  
   Test(1);  
}  
```


<!--HONumber=Jan17_HO2-->


