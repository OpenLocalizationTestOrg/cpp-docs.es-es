---
title: Fatal Error C1016 | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-csharp
ms.tgt_pltfrm: 
ms.topic: article
f1_keywords:
- C1016
dev_langs:
- C++
helpviewer_keywords:
- C1016
ms.assetid: 33f45c3e-2d8f-43ad-a445-c412d1d54ce1
caps.latest.revision: 9
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
ms.openlocfilehash: 33913f85858ee6f02c52e20e164c4fa006301b38

---
# Fatal Error C1016
\#ifdef expected an identifier#ifndef expected an identifier  
  
 The conditional compilation directive ([#ifdef](../../preprocessor/hash-ifdef-and-hash-ifndef-directives-c-cpp.md) or `#ifndef`) has no identifier to evaluate. To resolve the error, specify an identifier.  
  
 The following sample generates C1016:  
  
```  
// C1016.cpp  
#ifdef   // C1016  
#define FC1016  
#endif  
  
int main() {}  
```  
  
 Possible resolution:  
  
```  
// C1016b.cpp  
#ifdef X  
#define FC1016  
#endif  
  
int main() {}  
```


<!--HONumber=Jan17_HO2-->


