---
title: Point of declaration in C++ | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: language-reference
dev_langs:
- C++
helpviewer_keywords:
- point of declaration
ms.assetid: 92ea8707-80cb-497c-b479-f907b8401859
caps.latest.revision: 7
author: mikeblome
ms.author: mblome
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
ms.openlocfilehash: 995e0982e5083b63e01f9c41bd8fb65462c39f99

---
# Point of declaration in C++
A name is considered to be declared immediately after its declarator but before its (optional) initializer. (For more information on declarators, see [Declarators](http://msdn.microsoft.com/en-us/8a7b9b51-92bd-4ac0-b3fe-0c4abe771838).)  
  
 Consider this example:  
  
```  
// point_of_declaration1.cpp  
// compile with: /W1   
double dVar = 7.0;  
int main()  
{  
   double dVar = dVar;   // C4700  
}  
```  
  
 If the point of declaration were *after* the initialization, then the local `dVar` would be initialized to 7.0, the value of the global variable `dVar`. However, since that is not the case, `dVar` is initialized to an undefined value.  
  
## See Also  
 [Scope](../cpp/scope-visual-cpp.md)


<!--HONumber=Jan17_HO2-->


