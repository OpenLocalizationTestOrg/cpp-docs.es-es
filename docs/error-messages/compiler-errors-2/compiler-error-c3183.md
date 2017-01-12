---
title: Compiler Error C3183 | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: error-reference
f1_keywords:
- C3183
dev_langs:
- C++
helpviewer_keywords:
- C3183
ms.assetid: dbd0f020-c739-43c9-947e-9ce21537331b
caps.latest.revision: 11
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
ms.sourcegitcommit: c243063a9770542f137d5950e8a269f771960f74
ms.openlocfilehash: 576cdae96028e9a9bc25d02a65cb56db0d0acea2

---
# Compiler Error C3183
cannot define unnamed class, struct or union inside of managed or WinRT type 'type'  
  
A type that is embedded in a managed or WinRT type must be named.  
  
The following sample generates C3183:  
  
```  
// C3183a.cpp  
// compile with: /clr /c  
ref class Test  
{  
   ref class  
   {  // C3183, delete class or name it  
      int a;  
      int b;  
   };  
};  
```  



<!--HONumber=Jan17_HO2-->


