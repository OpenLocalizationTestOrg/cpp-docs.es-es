---
title: Compiler Error C2671 | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: error-reference
f1_keywords:
- C2671
dev_langs:
- C++
helpviewer_keywords:
- C2671
ms.assetid: fc0ee40f-c8f3-408f-b89d-745d149c4169
caps.latest.revision: 8
author: corob-msft
ms.author: corob
manager: ghogen
translation.priority.ht:
- de-de
- es-es
- fr-fr
- it-it
- ja-jp
- ko-kr
- ru-ru
- zh-cn
- zh-tw
translation.priority.mt:
- cs-cz
- pl-pl
- pt-br
- tr-tr
translationtype: Human Translation
ms.sourcegitcommit: 3168772cbb7e8127523bc2fc2da5cc9b4f59beb8
ms.openlocfilehash: cb7651b8ddb8eb67d5caa7b4dddd3dffdf4d416d

---
# Compiler Error C2671
'function' : static member functions do not have 'this' pointers  
  
 A `static` member function tried to access `this`.  
  
 The following sample generates C2671:  
  
```  
// C2671.cpp  
struct S {  
   static S* const func() { return this; }  // C2671  
};  
```


<!--HONumber=Jan17_HO2-->


