---
title: Compiler Warning C4694 | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-csharp
ms.tgt_pltfrm: 
ms.topic: article
f1_keywords:
- C4694
dev_langs:
- C++
helpviewer_keywords:
- C4694
ms.assetid: 5ca122bb-34f3-43ee-a21f-95802cd515f7
caps.latest.revision: 3
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
ms.openlocfilehash: ae91c5b8af97d02223e1d7154d1cf029493cdc7c

---
# Compiler Warning C4694
'class_1': a sealed abstract class cannot have a base-class 'base_class'  
  
 An abstract and sealed class cannot inherit from a reference type; a sealed and abstract class can neither implement the base class functions nor allow itself to be used as a base class.  
  
 For more information, see [abstract](../../windows/abstract-cpp-component-extensions.md), [sealed](../../windows/sealed-cpp-component-extensions.md), and [Classes and Structs](../../windows/classes-and-structs-cpp-component-extensions.md).  
  
## Example  
 The following sample generates C4694.  
  
```  
// C4694.cpp  
// compile with: /c /clr  
ref struct A {};  
ref struct B sealed abstract : A {};   // C4694  
```


<!--HONumber=Jan17_HO2-->


