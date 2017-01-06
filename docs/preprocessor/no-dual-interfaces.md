---
title: o_dual_interfaces | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: article
f1_keywords:
- no_dual_interfaces
dev_langs:
- C++
- C
helpviewer_keywords:
- no_dual_interfaces attribute
ms.assetid: 9acd5d9d-4a49-4cdc-9470-73a2c23cf512
caps.latest.revision: 4
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
ms.openlocfilehash: 6a96aba4df0bb5432983ccc83678a0223a4cf24b

---
# no_dual_interfaces
**C++ Specific**  
  
 Changes the way the compiler generates wrapper functions for dual interface methods.  
  
## Syntax  
  
```  
no_dual_interfaces  
```  
  
## Remarks  
 Normally, the wrapper will call the method through the virtual function table for the interface. With `no_dual_interfaces`, the wrapper instead calls **IDispatch::Invoke** to invoke the method.  
  
 **END C++ Specific**  
  
## See Also  
 [#import Attributes](../preprocessor/hash-import-attributes-cpp.md)   
 [#import Directive](../preprocessor/hash-import-directive-cpp.md)


<!--HONumber=Jan17_HO1-->


