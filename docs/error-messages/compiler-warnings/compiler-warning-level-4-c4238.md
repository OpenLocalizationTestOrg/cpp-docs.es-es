---
title: Compiler Warning (level 4) C4238 | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: error-reference
f1_keywords:
- C4238
dev_langs:
- C++
helpviewer_keywords:
- C4238
ms.assetid: 5d4051d3-7b0f-43ea-8c8d-d194bfdceb71
caps.latest.revision: 8
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
ms.openlocfilehash: b5b6c2a2a040f419edee39e10c54362771d9ad65

---
# Compiler Warning (level 4) C4238
nonstandard extension used : class rvalue used as lvalue  
  
 For compatibility with previous versions of Visual C++, Microsoft extensions (**/Ze**) allow you to use a class type as an rvalue in a context that implicitly or explicitly takes its address. In some cases, such as the example below, this can be dangerous.  
  
## Example  
  
```  
// C4238.cpp  
// compile with: /W4 /c  
struct C {  
   C() {}  
};  
  
C * pC = &C();   // C4238  
```  
  
 This usage causes an error under ANSI compatibility ([/Za](../../build/reference/za-ze-disable-language-extensions.md)).


<!--HONumber=Jan17_HO2-->


