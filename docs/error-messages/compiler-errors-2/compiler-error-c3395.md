---
title: Compiler Error C3395 | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: error-reference
f1_keywords:
- C3395
dev_langs:
- C++
helpviewer_keywords:
- C3395
ms.assetid: 26a9ebc9-ed97-47ce-b436-19aa2bcf6e50
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
ms.openlocfilehash: 319926d7a0ea76751e185ac132c247a5fa2b4af1

---
# Compiler Error C3395
'function' : __declspec(dllexport) cannot be applied to a function with the \__clrcall calling convention  
  
 `__declspec(dllexport)` and [__clrcall](../../cpp/clrcall.md) are not compatible.  For more information, see [dllexport, dllimport](../../cpp/dllexport-dllimport.md).  
  
 The following sample generates C3395:  
  
```  
// C3395.cpp  
// compile with: /clr /c  
  
__declspec(dllexport) void __clrcall Test(){}   // C3395  
void __clrcall Test2(){}   // OK  
__declspec(dllexport) void Test3(){}   // OK  
```


<!--HONumber=Jan17_HO2-->


