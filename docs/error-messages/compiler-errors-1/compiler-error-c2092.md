---
title: Compiler Error C2092 | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: error-reference
f1_keywords:
- C2092
dev_langs:
- C++
helpviewer_keywords:
- C2092
ms.assetid: 037e44ae-16c8-489a-a512-dcdf7f7795a6
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
ms.openlocfilehash: 52d25b7f33b5e78f0d169bfce5f401cf8d3bf2ee

---
# Compiler Error C2092
'array name' array element type cannot be function  
  
 Arrays of functions are not allowed. Use an array of pointers to functions.  
  
## Example  
 The following sample generates C2092:  
  
```  
// C2092.cpp  
typedef void (F) ();  
typedef F AT[10];   // C2092  
```  
  
## Example  
 Possible resolution:  
  
```  
// C2092b.cpp  
// compile with: /c  
typedef void (F) ();  
typedef F * AT[10];  
```


<!--HONumber=Jan17_HO2-->


