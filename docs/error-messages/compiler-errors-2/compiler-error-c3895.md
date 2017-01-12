---
title: Compiler Error C3895 | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: error-reference
f1_keywords:
- C3895
dev_langs:
- C++
helpviewer_keywords:
- C3895
ms.assetid: 771b9fe5-d6d4-4297-bf57-e2f857722155
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
ms.openlocfilehash: b7c5412579a6e9e0cb32282525cab1168fb6009d

---
# Compiler Error C3895
'var' : type data members cannot be 'volatile'  
  
 Certain kinds of data members, for example [literal](../../windows/literal-cpp-component-extensions.md) or [initonly](../../dotnet/initonly-cpp-cli.md), cannot be [volatile](../../cpp/volatile-cpp.md).  
  
 The following sample generates C3895:  
  
```  
// C3895.cpp  
// compile with: /clr  
ref struct Y1 {  
   initonly  
   volatile int data_var2;   // C3895  
};  
```


<!--HONumber=Jan17_HO2-->


