---
title: Compiler Error C2800 | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: error-reference
f1_keywords:
- C2800
dev_langs:
- C++
helpviewer_keywords:
- C2800
ms.assetid: a2f1a590-9fe6-44cb-ad09-b4505ef47c6a
caps.latest.revision: 8
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
ms.openlocfilehash: 2624ff8fe06e610a5f8a58c877ae6b87f6ddb6eb

---
# Compiler Error C2800
'operator operator' cannot be overloaded  
  
 The following operators cannot be overloaded: class member access (`.`), pointer to member (`.*`), scope resolution (`::`), conditional expression (`? :`), and `sizeof`.  
  
 The following sample generates C2800:  
  
```  
// C2800.cpp  
// compile with: /c  
class C {  
   operator:: ();   // C2800  
};  
```


<!--HONumber=Jan17_HO2-->


