---
title: Compiler Error C3715 | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: error-reference
f1_keywords:
- C3715
dev_langs:
- C++
helpviewer_keywords:
- C3715
ms.assetid: ee5dce88-ddc4-4bdb-9464-47467ce1674f
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
ms.openlocfilehash: 3b37be48c281f3c3e381abd3ed4c6704c8b5c528

---
# Compiler Error C3715
'pointer': must be a pointer to 'class'  
  
 You specified a pointer in [__hook](../../cpp/hook.md) or [__unhook](../../cpp/unhook.md) that did not point to a valid class. To fix this error, ensure that your `__hook` and `__unhook` calls specify pointers to valid classes.


<!--HONumber=Jan17_HO2-->


