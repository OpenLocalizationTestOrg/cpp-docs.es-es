---
title: Compiler Error C3648 | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: error-reference
f1_keywords:
- C3648
dev_langs:
- C++
helpviewer_keywords:
- C3648
ms.assetid: 5d042989-41cb-4cd0-aa50-976b70146aaf
caps.latest.revision: 10
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
ms.sourcegitcommit: c243063a9770542f137d5950e8a269f771960f74
ms.openlocfilehash: bbc097048600700592d2ebb30d939ba216434d84

---
# Compiler Error C3648
this explicit override syntax requires /clr:oldSyntax  
  
When compiling for the latest managed syntax, the compiler found explicit override syntax for previous versions that is no longer supported.  
  
For more information, see [Explicit Overrides](../../windows/explicit-overrides-cpp-component-extensions.md).  
  
## Example  
 The following sample generates C3648:  
  
```  
// C3648.cpp  
// compile with: /clr  
public interface struct I {  
   void f();  
};  
  
public ref struct R : I {  
   virtual void I::f() {}   // C3648  
   // try the following line instead  
   // virtual void f() = I::f{}  
};  
```


<!--HONumber=Jan17_HO2-->


