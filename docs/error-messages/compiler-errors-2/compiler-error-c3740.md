---
title: Compiler Error C3740 | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: error-reference
f1_keywords:
- C3740
dev_langs:
- C++
helpviewer_keywords:
- C3740
ms.assetid: edb17a90-2307-4df6-943d-580460d26d2b
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
ms.openlocfilehash: e4e541d996d9daa7458fb61df10e69a5d9101364

---
# Compiler Error C3740
templates cannot source or receive events  
  
 A templated class or struct cannot contain [events](../../cpp/event-handling.md).  
  
 The following sample generates C3740:  
  
```  
// C3740.cpp  
template <typename T>   // Delete the template specification  
struct E {  
   __event void f();   // C3740  
};  
  
int main() {  
}  
```


<!--HONumber=Jan17_HO2-->


