---
title: A.2   Specifying Conditional Compilation | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: article
dev_langs:
- C++
ms.assetid: de4a21b9-f987-4738-9f13-c4795f6f2dff
caps.latest.revision: 8
author: mikeblome
ms.author: mblome
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
ms.openlocfilehash: 2a9b1e42c869cb4e25aa1bbcb6a9034db1990bed

---
# A.2   Specifying Conditional Compilation
The following examples illustrate the use of conditional compilation using the OpenMP macro `_OPENMP` ([Section 2.2](../../parallel/openmp/2-2-conditional-compilation.md) on page 8). With OpenMP compilation, the `_OPENMP` macro becomes defined.  
  
```  
# ifdef _OPENMP   
    printf_s("Compiled by an OpenMP-compliant implementation.\n");  
# endif  
```  
  
 The defined preprocessor operator allows more than one macro to be tested in a single directive.  
  
```  
# if defined(_OPENMP) && defined(VERBOSE)  
    printf_s("Compiled by an OpenMP-compliant implementation.\n");  
# endif  
```


<!--HONumber=Jan17_HO2-->


