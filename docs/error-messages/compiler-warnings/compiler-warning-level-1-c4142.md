---
title: Compiler Warning (level 1) C4142 | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: error-reference
f1_keywords:
- C4142
dev_langs:
- C++
helpviewer_keywords:
- C4142
ms.assetid: 1fdfc3dc-60a2-4f00-b133-20e400f9b7a6
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
ms.openlocfilehash: 81fbb15b9589d5ddfdcc949dce24aec2a3c1716e

---
# Compiler Warning (level 1) C4142
benign redefinition of type  
  
 A type is redefined in a manner that has no effect on the generated code.  
  
 To fix by checking the following possible causes:  
  
-   A member function of a derived class has a different return type from the corresponding member function of the base class.  
  
-   A type defined with the `typedef` command is redefined using different syntax.  
  
 The following sample generates C4142:  
  
```  
// C4142.c  
// compile with: /W1  
float X2;  
X2 = 2.0 + 1.0;   // C4142  
  
int main() {  
   float X2;  
   X2 = 2.0 + 1.0;   // OK  
}  
```


<!--HONumber=Jan17_HO1-->


