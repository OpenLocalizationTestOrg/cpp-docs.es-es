---
title: Compiler Error C2998 | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-csharp
ms.tgt_pltfrm: 
ms.topic: article
f1_keywords:
- C2998
dev_langs:
- C++
helpviewer_keywords:
- C2998
ms.assetid: 8193d491-b5d9-4477-acb1-cf166889c070
caps.latest.revision: 7
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
ms.openlocfilehash: 985156d027c711b90c21de6fe958d82f166279a9

---
# Compiler Error C2998
'identifier' : cannot be a template definition  
  
 The compiler could not process the syntax used in the template definition.  
  
 The following sample generates C2998:  
  
```  
// C2998.cpp  
// compile with: /c  
template <class T> int x = 1018; // C2998  
```


<!--HONumber=Jan17_HO2-->


