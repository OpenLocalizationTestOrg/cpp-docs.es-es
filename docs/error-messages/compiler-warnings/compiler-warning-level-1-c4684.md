---
title: Compiler Warning (level 1) C4684 | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: error-reference
f1_keywords:
- C4684
dev_langs:
- C++
helpviewer_keywords:
- C4684
ms.assetid: e95f1a83-2784-4b05-ae94-12148e056e26
caps.latest.revision: 6
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
ms.openlocfilehash: 2bbeee14c7acf1e439a474fa5efe8c32a21a062a

---
# Compiler Warning (level 1) C4684
'attribute' : WARNING!! attribute may cause invalid code generation: use with caution  
  
 You used an attribute that should not commonly be used.  
  
 The following sample generates C4684:  
  
```  
// C4684.cpp  
// compile with: /W1 /LD  
 [module(name="xx")]; // C4684 expected  
[no_injected_text];  
```


<!--HONumber=Jan17_HO2-->


