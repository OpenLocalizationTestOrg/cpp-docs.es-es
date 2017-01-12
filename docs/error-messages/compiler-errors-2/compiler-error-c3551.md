---
title: Compiler Error C3551 | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-csharp
ms.tgt_pltfrm: 
ms.topic: article
f1_keywords:
- C3551
dev_langs:
- C++
helpviewer_keywords:
- C3551
ms.assetid: c8ee23da-6568-40db-93a6-3ddb7ac47712
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
ms.openlocfilehash: 7f46e0de158239c2c2d428de22358d01841ff4a8

---
# Compiler Error C3551
"expected a late specified return type"  
  
 If you use the `auto` keyword as a placeholder for the return type of a function, you must provide a late-specified return type. In the following example, the late-specified return type of function `myFunction` is a pointer to an array of four elements of type `int`.  
  
```  
auto myFunction()->int(*)[4];   
```  
  
## See Also  
 [auto](../../cpp/auto-cpp.md)


<!--HONumber=Jan17_HO2-->


