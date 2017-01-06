---
title: Compiler Warning (level 4) C4985 | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-csharp
ms.tgt_pltfrm: 
ms.topic: article
dev_langs:
- C++
helpviewer_keywords:
- C4985
ms.assetid: 832f001c-afe7-403d-a8b4-02334724c79e
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
ms.openlocfilehash: 08b491e0e2278bf827cd986baa64d133d5ea4305

---
# Compiler Warning (level 4) C4985
'symbol name': attributes not present on previous declaration.  
  
 The Microsoft source code annotation language (SAL) annotations on the current method declaration or definition differ from the annotations on an earlier declaration. The same SAL annotations must be used in the definition and declarations of a method.  
  
 The SAL provides a set of annotations that you can use to describe how a function uses its parameters, the assumptions it makes about them, and the guarantees it makes on finishing. The annotations are defined in the sal.h header file.  
  
 Notice that the SAL macros will not expand unless the project has the [/analyze](../../build/reference/analyze-code-analysis.md) flag specified. When you specify **/analyze**, the compiler can throw C4985, even if no warnings or errors appeared without **/analyze**.  
  
### To correct this error  
  
1.  Use the same SAL annotations on the definition of a method and all its declarations.  
  
## See Also  
 [SAL Annotations](../../c-runtime-library/sal-annotations.md)


<!--HONumber=Jan17_HO1-->


