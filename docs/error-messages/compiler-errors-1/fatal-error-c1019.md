---
title: Fatal Error C1019 | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-csharp
ms.tgt_pltfrm: 
ms.topic: article
f1_keywords:
- C1019
dev_langs:
- C++
helpviewer_keywords:
- C1019
ms.assetid: c4f8968b-bc62-4200-b3ca-69d06c163236
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
ms.openlocfilehash: 787cceeb9a01cb184334c3d89d9cfcfba50c2c92

---
# Fatal Error C1019
unexpected #else  
  
 The `#else` directive appears outside an `#if`, `#ifdef`, or `#ifndef` construct. Use `#else` only within one of these constructs.  
  
 The following sample generates C1019:  
  
```  
// C1019.cpp  
#else   // C1019  
#endif  
  
int main() {}  
```  
  
 Possible resolution:  
  
```  
// C1019b.cpp  
#if 1  
#else  
#endif  
  
int main() {}  
```


<!--HONumber=Jan17_HO2-->


