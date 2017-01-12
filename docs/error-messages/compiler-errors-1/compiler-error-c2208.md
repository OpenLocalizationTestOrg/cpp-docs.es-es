---
title: Compiler Error C2208 | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: error-reference
f1_keywords:
- C2208
dev_langs:
- C++
helpviewer_keywords:
- C2208
ms.assetid: 9ae704bc-bf70-45f1-8e47-0470f21edd4e
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
ms.openlocfilehash: ff16ff8f0a44b3ce8b4b521828ced56c4f3d0769

---
# Compiler Error C2208
'type' : no members defined using this type  
  
 An identifier resolving to a type name is in an aggregate declaration, but the compiler cannot declare a member.  
  
 The following sample generates C2208:  
  
```  
// C2208.cpp  
class C {  
   C;   // C2208  
   C(){}   // OK  
};  
```


<!--HONumber=Jan17_HO2-->


