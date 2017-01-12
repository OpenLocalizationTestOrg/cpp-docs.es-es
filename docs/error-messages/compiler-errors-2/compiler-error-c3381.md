---
title: Compiler Error C3381 | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: error-reference
f1_keywords:
- C3381
dev_langs:
- C++
helpviewer_keywords:
- C3381
ms.assetid: d276c89f-8377-4cb6-a8d4-7770885f06c4
caps.latest.revision: 9
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
ms.openlocfilehash: 25d41ac2445fe8ec93385d4cf4f159e0149ae7b6

---
# Compiler Error C3381
'assembly' : assembly access specifiers are only available in code compiled with a /clr option  
  
 Native types can be visible outside the assembly, but you can only specify assembly access for native types in a **/clr** compilation.  
  
 For more information, see [Type visibility](../../dotnet/how-to-define-and-consume-classes-and-structs-cpp-cli.md#BKMK_Type_visibility) and [/clr (Common Language Runtime Compilation)](../../build/reference/clr-common-language-runtime-compilation.md).  
  
## Example  
 The following sample generates C3381.  
  
```  
// C3381.cpp  
// compile with: /c  
public class A {};   // C3381  
```


<!--HONumber=Jan17_HO2-->


