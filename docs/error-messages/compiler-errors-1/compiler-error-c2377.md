---
title: Compiler Error C2377 | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-csharp
ms.tgt_pltfrm: 
ms.topic: article
f1_keywords:
- C2377
dev_langs:
- C++
helpviewer_keywords:
- C2377
ms.assetid: f7660965-bf4c-4cd9-8307-1bd7016678a1
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
ms.openlocfilehash: e00ee6b58cd55a1f9daf270905d2bf3b79dd0182

---
# Compiler Error C2377
'identifier' : redefinition; typedef cannot be overloaded with any other symbol  
  
 A `typedef` identifier is redefined.  
  
 The following sample generates C2377:  
  
```  
// C2377.cpp  
// compile with: /c  
typedef int i;  
int i;   // C2377  
int j;   // OK  
```


<!--HONumber=Jan17_HO2-->


