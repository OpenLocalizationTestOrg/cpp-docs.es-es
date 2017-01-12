---
title: Compiler Error C2332 | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: error-reference
f1_keywords:
- C2332
dev_langs:
- C++
helpviewer_keywords:
- C2332
ms.assetid: fb05cd68-e271-4bea-9fb7-ef4edb0a26ac
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
ms.openlocfilehash: 0f37cf89e8ff7192680b3c3c85f59b708c4b74f5

---
# Compiler Error C2332
'typedef' : missing tag name  
  
 The compiler found an incomplete type definition.  
  
 The following sample generates C2332:  
  
```  
// C2332.cpp  
// compile with: /c  
struct S {  
   int i;  
};  
  
typedef struct * pS;   // C2332  
typedef struct S* pS;   // OK  
  
int get_S_i(pS p) {  
   return p->i;  
}  
```


<!--HONumber=Jan17_HO2-->


