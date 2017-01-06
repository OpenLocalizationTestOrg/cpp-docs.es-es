---
title: Math Error M6111 | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: error-reference
f1_keywords:
- M6111
dev_langs:
- C++
helpviewer_keywords:
- M6111
ms.assetid: c0fc13f8-33c8-4e3f-a440-126cc623441b
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
ms.openlocfilehash: 906072bdd8fe674d69604ddc6f8ddd66ebad712d

---
# Math Error M6111
stack underflow  
  
 A floating-point operation resulted in a stack underflow on the 8087/287/387 coprocessor or the emulator.  
  
 This error is often caused by a call to a `long double` function that does not return a value. For example, the following generates this error when compiled and run:  
  
```  
long double ld() {};  
main ()  
{  
  ld();  
}  
```  
  
 Program terminates with exit code 139.


<!--HONumber=Jan17_HO1-->


