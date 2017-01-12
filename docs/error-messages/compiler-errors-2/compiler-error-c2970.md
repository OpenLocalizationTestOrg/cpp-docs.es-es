---
title: Compiler Error C2970 | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: error-reference
f1_keywords:
- C2970
dev_langs:
- C++
helpviewer_keywords:
- C2970
ms.assetid: 21d90348-20d3-438c-b278-efdbfb93a7d2
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
ms.openlocfilehash: e8118fa6f025be20f3d892ef0c0b1bbcca4b5b55

---
# Compiler Error C2970
'class' : template parameter 'param' : 'arg' : an expression involving objects with internal linkage cannot be used as a non-type argument  
  
 You cannot use the name or address of a static variable as a template argument. The template class expects a const value that can be evaluated at compile time.  
  
 The following sample generates C2970:  
  
```  
// C2970.cpp  
// compile with: /c  
static int si;  
// could declare nonstatic to resolve all errors  
// int si;  
  
template <int i>   
class X {};  
  
template <int *pi>   
class Y {};  
  
X<si> anX;   // C2970 cannot use static variable in templates  
  
// this would also work  
const int i = 10;  
X<i> anX2;  
```


<!--HONumber=Jan17_HO2-->


