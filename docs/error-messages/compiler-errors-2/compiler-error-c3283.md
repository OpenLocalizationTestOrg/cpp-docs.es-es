---
title: Compiler Error C3283 | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-csharp
ms.tgt_pltfrm: 
ms.topic: article
f1_keywords:
- C3283
dev_langs:
- C++
helpviewer_keywords:
- C3283
ms.assetid: c51d912c-cde3-4928-904e-26734c8954ce
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
ms.openlocfilehash: fcb93264f5da2b68f782339109a665867e37b3c0

---
# Compiler Error C3283
'type' : an interface cannot have an instance constructor  
  
 A CLR [interface](../../windows/interface-class-cpp-component-extensions.md) cannot have an instance constructor.  A static constructor is allowed.  
  
 The following sample generates C3283:  
  
```  
// C3283.cpp  
// compile with: /clr  
interface class I {  
   I();   // C3283  
};  
```  
  
 Possible resolution:  
  
```  
// C3283b.cpp  
// compile with: /clr /c  
interface class I {  
   static I(){}  
};  
```


<!--HONumber=Jan17_HO2-->


