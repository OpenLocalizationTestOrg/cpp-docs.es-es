---
title: Compiler Warning (level 3) C4018 | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: error-reference
f1_keywords:
- C4018
dev_langs:
- C++
helpviewer_keywords:
- C4018
ms.assetid: 6e8cbb04-d914-4319-b431-cbc2fbe40eb1
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
ms.openlocfilehash: d34475e0be7ef98d7b31d41aeccaed193da7672b

---
# Compiler Warning (level 3) C4018
'expression' : signed/unsigned mismatch  
  
 Comparing a signed and unsigned number required the compiler to convert the signed value to unsigned.  
  
 This warning may be fixed if you cast one of the two types when testing signed and unsigned types.  
  
 The following sample generates C4018:  
  
```  
// C4018.cpp  
// compile with: /W3  
int main() {  
   unsigned int uc = 0;  
   int c = 0;  
   unsigned int c2 = 0;  
  
   if (uc < c) uc = 0;   // C4018  
  
   // OK  
   if (uc == c2) uc = 0;  
}  
```


<!--HONumber=Jan17_HO2-->


