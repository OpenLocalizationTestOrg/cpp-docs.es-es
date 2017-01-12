---
title: Compiler Error C2388 | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-csharp
ms.tgt_pltfrm: 
ms.topic: article
f1_keywords:
- C2388
dev_langs:
- C++
helpviewer_keywords:
- C2388
ms.assetid: 764ad2d7-cb04-425f-ba30-70989488c4a4
caps.latest.revision: 12
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
ms.openlocfilehash: a11001dfa401b89c604e685524befd2c7a3c89d2

---
# Compiler Error C2388
'symbol' : a symbol cannot be declared with both __declspec(appdomain) and \__declspec(process)  
  
 The `appdomain` and `process``__declspec` modifiers cannot be used on the same symbol. The storage for a variable exists per process or per application domain.  
  
 For more information, see [appdomain](../../cpp/appdomain.md) and [process](../../cpp/process.md).  
  
 The following sample generates C2388:  
  
```  
// C2388.cpp  
// compile with: /clr /c  
__declspec(process) __declspec(appdomain) int i;   // C2388  
__declspec(appdomain) int i;   // OK  
```


<!--HONumber=Jan17_HO2-->


