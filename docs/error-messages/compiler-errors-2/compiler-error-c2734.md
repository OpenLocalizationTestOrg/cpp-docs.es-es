---
title: Compiler Error C2734 | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: error-reference
f1_keywords:
- C2734
dev_langs:
- C++
helpviewer_keywords:
- C2734
ms.assetid: e53a77b7-825c-42d1-a655-90e1c93b833e
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
ms.openlocfilehash: 32fd980c9cf77ab449bd9ed9d4849ccdce70e343

---
# Compiler Error C2734
'identifier' : const object must be initialized if not extern  
  
 The identifier is declared `const` but not initialized or `extern`.  
  
 The following sample generates C2734:  
  
```  
// C2734.cpp  
const int j;   // C2734  
extern const int i;   // OK, declared as extern  
```


<!--HONumber=Jan17_HO2-->


