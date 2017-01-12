---
title: Compiler Error C2203 | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: error-reference
f1_keywords:
- C2203
dev_langs:
- C++
helpviewer_keywords:
- C2203
ms.assetid: 5497df43-86f6-43d5-b6cb-723c4c589b10
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
ms.openlocfilehash: 50dc129eb55c992dcc150366354c56274c9425dd

---
# Compiler Error C2203
delete operator cannot specify bounds for an array  
  
 With the **/Za** (ANSI) option, the `delete` operator can delete an entire array but not parts or specific members of the array.  
  
 The following sample generates C2203:  
  
```  
// C2203.cpp  
// compile with: /Za  
int main() {  
   int *ar = new int[10];  
   delete [4] ar;   // C2203  
   // try the following line instead  
   // delete [] ar;  
}  
```


<!--HONumber=Jan17_HO2-->


