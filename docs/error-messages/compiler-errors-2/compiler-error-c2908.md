---
title: Compiler Error C2908 | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: error-reference
f1_keywords:
- C2908
dev_langs:
- C++
helpviewer_keywords:
- C2908
ms.assetid: 49cd2a21-cad8-4ba0-9a0b-3a0190d9344c
caps.latest.revision: 7
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
ms.openlocfilehash: 3a8e33864741503d8238f00545d140d907d2a07b

---
# Compiler Error C2908
explicit specialization; 'template' has already been instantiated  
  
 A specialization of the primary template occurs before the explicit specialization.  
  
 The following sample generates C2908:  
  
```  
// C2908.cpp  
// compile with: /c  
template<class T> class X {};  
  
void f() {  
X<int> x;   //specialization and instantiation  
            //of X<int>  
}  
  
template<> class X<int> {}  // C2908, explicit specialization  
```


<!--HONumber=Jan17_HO2-->


