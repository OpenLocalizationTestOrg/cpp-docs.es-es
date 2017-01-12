---
title: Compiler Warning (level 3) C4570 | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: error-reference
f1_keywords:
- C4570
dev_langs:
- C++
helpviewer_keywords:
- C4570
ms.assetid: feec1225-e6ad-4995-8d96-c22e864a77bd
caps.latest.revision: 6
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
ms.openlocfilehash: 32bcc68e077ec97ee566627d3120e893dcd0d262

---
# Compiler Warning (level 3) C4570
'type' : is not explicitly declared as abstract but has abstract functions  
  
 A type that contains [abstract](../../windows/abstract-cpp-component-extensions.md) functions should itself be marked as abstract.  
  
## Example  
 The following sample generates C4570.  
  
```  
// C4570.cpp  
// compile with: /clr /W3 /c  
ref struct X {   // C4570  
// try the following line instead  
// ref class X abstract {  
   virtual void f() abstract;  
};  
```


<!--HONumber=Jan17_HO2-->


