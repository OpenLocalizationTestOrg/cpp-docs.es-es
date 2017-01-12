---
title: Compiler Error C3384 | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-csharp
ms.tgt_pltfrm: 
ms.topic: article
f1_keywords:
- C3384
dev_langs:
- C++
helpviewer_keywords:
- C3384
ms.assetid: c9f92c6a-62a9-4333-b2b1-bc55c7f288b6
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
ms.openlocfilehash: 50ebdb6f446ddde88ea0c6ef043e4eaea4b47c45

---
# Compiler Error C3384
'type_parameter' : the value constraint and the ref constraint are mutually exclusive  
  
 You cannot constrain a generic type to both `value class` and `ref class`.  
  
 See [Constraints on Generic Type Parameters (C++/CLI)](../../windows/constraints-on-generic-type-parameters-cpp-cli.md) for more information.  
  
## Example  
 The following sample generates C3384.  
  
```  
// C3384.cpp  
// compile with: /c /clr  
generic <typename T>  
where T : ref class  
where T : value class   // C3384  
ref class List {};  
```


<!--HONumber=Jan17_HO2-->


