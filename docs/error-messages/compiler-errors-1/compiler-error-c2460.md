---
title: Compiler Error C2460 | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: error-reference
f1_keywords:
- C2460
dev_langs:
- C++
helpviewer_keywords:
- C2460
ms.assetid: d969fca9-3ac5-4e4e-88fc-df05510e2093
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
ms.openlocfilehash: b7ca5a715feca737635c9feb538de7348eb0feb9

---
# Compiler Error C2460
'identifier1' : uses 'identifier2', which is being defined  
  
 A class or structure (`identifier2`) is declared as a member of itself (`identifier1`). Recursive definitions of classes and structures are not allowed.  
  
 The following sample generates C2460:  
  
```  
// C2460.cpp  
class C {  
   C aC;    // C2460  
};  
```  
  
 Instead, use a pointer reference in the class.  
  
```  
// C2460.cpp  
class C {  
   C * aC;    // OK  
};  
```


<!--HONumber=Jan17_HO1-->


