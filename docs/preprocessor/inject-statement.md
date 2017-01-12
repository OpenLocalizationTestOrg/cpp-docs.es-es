---
title: inject_statement | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: article
f1_keywords:
- inject_statement
dev_langs:
- C++
- C
helpviewer_keywords:
- inject_statement attribute
ms.assetid: 07d6f0f4-d9fb-4e18-aa62-f235f142ff5e
caps.latest.revision: 5
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
ms.openlocfilehash: b13279a204fba6c2a48139d4ac58ee81177a9daf

---
# inject_statement
**C++ Specific**  
  
 Inserts its argument as source text into the type-library header.  
  
## Syntax  
  
```  
inject_statement("source_text")  
```  
  
#### Parameters  
 `source_text`  
 Source text to be inserted into the type library header file.  
  
## Remarks  
 The text is placed at the beginning of the namespace declaration that wraps the type-library contents in the header file.  
  
 **END C++ Specific**  
  
## See Also  
 [#import Attributes](../preprocessor/hash-import-attributes-cpp.md)   
 [#import Directive](../preprocessor/hash-import-directive-cpp.md)


<!--HONumber=Jan17_HO2-->


