---
title: Compiler Error C3540 | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: error-reference
f1_keywords:
- C3540
dev_langs:
- C++
helpviewer_keywords:
- C3540
ms.assetid: 3c0c959c-e3b7-40eb-b922-ccac44bd9d85
caps.latest.revision: 8
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
ms.openlocfilehash: a211e81418dc6354f9e61b2df4b0077b0b6986ba

---
# Compiler Error C3540
'type': sizeof cannot be applied to a type that contains 'auto'  
  
 The [sizeof](../../cpp/sizeof-operator.md) operator cannot be applied to the indicated type because it contains the `auto` specifier.  
  
## Example  
 The following example yields C3540.  
  
```  
// C3540.cpp  
// Compile with /Zc:auto  
int main() {  
    auto x = 123;  
    sizeof(x);    // OK  
    sizeof(auto); // C3540  
    return 0;  
}  
```  
  
## See Also  
 [auto Keyword](../../cpp/auto-keyword.md)   
 [/Zc:auto (Deduce Variable Type)](../../build/reference/zc-auto-deduce-variable-type.md)   
 [sizeof Operator](../../cpp/sizeof-operator.md)


<!--HONumber=Jan17_HO2-->


