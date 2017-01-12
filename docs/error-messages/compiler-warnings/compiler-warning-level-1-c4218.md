---
title: Compiler Warning (level 1) C4218 | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: error-reference
f1_keywords:
- C4218
dev_langs:
- C++
helpviewer_keywords:
- C4218
ms.assetid: d6c3cd90-4518-49e9-ae86-4ba9e2761d98
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
ms.openlocfilehash: 6f657da21a7756973b9f9febe823003ebfd68fd1

---
# Compiler Warning (level 1) C4218
nonstandard extension used : must specify at least a storage class or a type  
  
 With the default Microsoft extensions (/Ze), you can declare a variable without specifying a type or storage class. The default type is `int`.  
  
## Example  
  
```  
// C4218.c  
// compile with: /W4  
i;  // C4218  
  
int main()  
{  
}  
```  
  
 Such declarations are invalid under ANSI compatibility ([/Za](../../build/reference/za-ze-disable-language-extensions.md)).


<!--HONumber=Jan17_HO2-->


