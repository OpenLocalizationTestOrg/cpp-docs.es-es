---
title: Compiler Error C3268 | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-csharp
ms.tgt_pltfrm: 
ms.topic: article
f1_keywords:
- C3268
dev_langs:
- C++
helpviewer_keywords:
- C3268
ms.assetid: d74a630c-daea-4e29-9759-83efef7fb184
caps.latest.revision: 5
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
ms.openlocfilehash: 6c7f8e5bff69303be0075895276349c685f046cc

---
# Compiler Error C3268
'function' : a generic function or a member-function of a generic class cannot have a variable parameter list  
  
 See [Generics](../../windows/generics-cpp-component-extensions.md) for more information.  
  
## Example  
 The following sample generates C3268.  
  
```  
// C3268.cpp  
// compile with: /clr:pure /c  
generic <class ItemType>  
void Test(ItemType item, ...) {}   // C3268  
// try the following line instead  
// void Test(ItemType item) {}  
  
generic <class ItemType2>  
ref struct MyStruct { void Test(...){} };   // C3268  
// try the following line instead  
// ref struct MyStruct { void Test2(){} };   // OK  
```


<!--HONumber=Jan17_HO2-->


