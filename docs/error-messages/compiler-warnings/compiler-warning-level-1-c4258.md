---
title: Compiler Warning (level 1) C4258 | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: error-reference
f1_keywords:
- C4258
dev_langs:
- C++
helpviewer_keywords:
- C4258
ms.assetid: bbb75e6d-6693-4e62-8ed3-b006a0ec55e3
caps.latest.revision: 7
author: corob-msft
ms.author: corob
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
ms.openlocfilehash: 0f3da4315033fe33282526c6a67de6b6666c8604

---
# Compiler Warning (level 1) C4258
'variable' : definition from the for loop is ignored; the definition from the enclosing scope is used"  
  
 Under [/Ze](../../build/reference/za-ze-disable-language-extensions.md) and [/Zc:forScope](../../build/reference/zc-forscope-force-conformance-in-for-loop-scope.md), variables defined in a [for](../../cpp/for-statement-cpp.md) loop go out of scope after the **for** loop ends. This warning occurs if a variable with the same name as the loop variable, but defined in the enclosing loop, is used again in the scope containing the **for** loop. For example:  
  
```  
// C4258.cpp  
// compile with: /Zc:forScope /W1  
int main()  
{  
   int i;  
   {  
      for (int i =0; i < 1; i++)  
         ;  
      i = 20;   // C4258 i (in for loop) has gone out of scope  
   }  
}  
```


<!--HONumber=Jan17_HO1-->


