---
title: Compiler Warning (level 1) C4224 | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: error-reference
f1_keywords:
- C4224
dev_langs:
- C++
helpviewer_keywords:
- C4224
ms.assetid: 1531cae0-5040-49fd-b149-005bb5085391
caps.latest.revision: 7
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
ms.openlocfilehash: 85d8a215850ef36460ba8c3da8df0f5786cf2322

---
# Compiler Warning (level 1) C4224
nonstandard extension used : formal parameter 'identifier' was previously defined as a type  
  
 The identifier was previously used as a `typedef`. This causes a warning under ANSI compatibility ([/Za](../../build/reference/za-ze-disable-language-extensions.md)).  
  
## Example  
  
```  
// C4224.cpp  
// compile with: /Za /W1 /LD  
typedef int I;  
void func ( int I );  // C4224  
```


<!--HONumber=Jan17_HO2-->


