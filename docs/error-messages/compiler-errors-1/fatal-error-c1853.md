---
title: Fatal Error C1853 | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: error-reference
f1_keywords:
- C1853
dev_langs:
- C++
helpviewer_keywords:
- C1853
ms.assetid: ceb9b4a5-92bf-4573-8a9f-3109cc7743ce
caps.latest.revision: 10
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
ms.openlocfilehash: d312a819b5e91386d805635fdd588b72ee842cfe

---
# Fatal Error C1853
'filename' precompiled header file is from a previous version of the compiler, or the precompiled header is C++ and you are using it from C (or vice versa)  
  
 Possible causes:  
  
-   The precompiled header was compiled with a previous compiler version. Try recompiling the header with the current compiler.  
  
-   The precompiled header is C++ and you are using it from C. Try recompiling the header for use with C by specifying one of the [/Tc](../../build/reference/tc-tp-tc-tp-specify-source-file-type.md) compiler options, or changing the suffix of the source file to "c". For more information, see [Two Choices for Precompiling Code](../../build/reference/two-choices-for-precompiling-code.md).


<!--HONumber=Jan17_HO1-->


