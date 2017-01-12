---
title: Compiler Error C3156 | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: error-reference
f1_keywords:
- C3156
dev_langs:
- C++
helpviewer_keywords:
- C3156
ms.assetid: 1876da78-b94e-4af7-9795-28f72b209b3e
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
ms.openlocfilehash: 170a76ba617396d716243e215d13c264f48cf5bf

---
# Compiler Error C3156
'class' : you cannot have a local definition of a managed or WinRT type  
  
 A function cannot contain the definition, or declaration, of a managed or WinRT class, struct, or interface.  
  
## Example  
 The following sample generates C3156.  
  
```  
// C3156.cpp  
// compile with: /clr /c  
void f() {  
   ref class X {};   // C3156  
   ref class Y;   // C3156  
}  
```  



<!--HONumber=Jan17_HO2-->


