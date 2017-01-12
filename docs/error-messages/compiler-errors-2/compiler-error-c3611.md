---
title: Compiler Error C3611 | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: error-reference
f1_keywords:
- C3611
dev_langs:
- C++
helpviewer_keywords:
- C3611
ms.assetid: 42f3e320-41de-420a-bd05-8924cab765aa
caps.latest.revision: 5
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
ms.openlocfilehash: cf6cf19124cf4c08cc5df8ce7852ec4bcccc33a9

---
# Compiler Error C3611
'function': a sealed function cannot have a pure-specifier  
  
 A sealed function was declared incorrectly.  For more information, see [sealed](../../windows/sealed-cpp-component-extensions.md).  
  
## Example  
 The following sample generates C3611.  
  
```  
// C3611.cpp  
// compile with: /clr /c  
  
ref struct V {  
   virtual void Test() sealed = 0;   // C3611  
   virtual void Test2() sealed;   // OK  
   virtual void Test3() = 0;   // OK  
};  
```


<!--HONumber=Jan17_HO2-->


