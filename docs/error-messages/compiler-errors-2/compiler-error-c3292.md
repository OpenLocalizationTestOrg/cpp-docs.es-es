---
title: Compiler Error C3292 | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-csharp
ms.tgt_pltfrm: 
ms.topic: article
f1_keywords:
- C3292
dev_langs:
- C++
helpviewer_keywords:
- C3292
ms.assetid: ead485cc-5471-4e10-b361-300589ff5b70
caps.latest.revision: 5
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
ms.openlocfilehash: 873f0a2e57aff09435763a5091cc8a384294690a

---
# Compiler Error C3292
the cli namespace cannot be reopened  
  
 The cli namespace cannot be declared in your code.  For more information, see [Platform, default, and cli Namespaces](../../windows/platform-default-and-cli-namespaces-cpp-component-extensions.md).  
  
## Example  
 The following sample generates C3292.  
  
```  
// C3292.cpp  
// compile with: /clr /c  
namespace cli {};   // C3292  
```


<!--HONumber=Jan17_HO2-->


