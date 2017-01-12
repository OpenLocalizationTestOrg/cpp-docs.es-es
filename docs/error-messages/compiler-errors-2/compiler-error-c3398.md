---
title: Compiler Error C3398 | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-csharp
ms.tgt_pltfrm: 
ms.topic: article
f1_keywords:
- C3398
dev_langs:
- C++
helpviewer_keywords:
- C3398
ms.assetid: 26f8c8a4-526f-415b-8047-155c5cd4f180
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
ms.openlocfilehash: 799a334cba62ea66b3a9e255df47e201823cfa41

---
# Compiler Error C3398
'operator' : cannot convert from 'function_signature' to 'function_pointer'. Source expression must be a function symbol  
  
 When the [__clrcall](../../cpp/clrcall.md) calling convention is not specified when compiling with **/clr**, the compiler generates two entry points (addresses) for each function, a native entry point and a managed entry point.  
  
 By default the compiler returns the native entry point, but there are some cases where the managed entry point is desired (for instance when assigning the address to a `__clrcall` function pointer). In order for the compiler to reliably choose the managed entry point in an assignment, the right hand side must be a function symbol.


<!--HONumber=Jan17_HO2-->


