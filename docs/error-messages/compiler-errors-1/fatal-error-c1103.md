---
title: Fatal Error C1103 | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-csharp
ms.tgt_pltfrm: 
ms.topic: article
f1_keywords:
- C1103
dev_langs:
- C++
helpviewer_keywords:
- C1103
ms.assetid: 9d276939-9c47-4235-9d20-76b8434f9731
caps.latest.revision: 6
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
ms.openlocfilehash: 041552288d508fc6c2bcf79fa62746ba4d081123

---
# Fatal Error C1103
fatal error importing progid: 'message'  
  
 The compiler detected a problem importing a type library.  For example, you cannot specify a type library with progid and also specify `no_registry`.  
  
 For more information, see [#import Directive](../../preprocessor/hash-import-directive-cpp.md).  
  
 The following sample will generate C1103:  
  
```  
// C1103.cpp  
#import "progid:a.b.id.1.5" no_registry auto_search   // C1103  
```


<!--HONumber=Jan17_HO2-->


