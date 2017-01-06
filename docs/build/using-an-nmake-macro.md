---
title: Using an NMAKE Macro | Microsoft Docs
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
helpviewer_keywords:
- macros, NMAKE
- NMAKE macros, using
ms.assetid: 95c87fbc-76e6-48c0-8536-9bfe179f328e
caps.latest.revision: 7
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
ms.openlocfilehash: e2f108113deff033334d616c4befb9d8cd93dcdd

---
# Using an NMAKE Macro
To use a macro, enclose its name in parentheses preceded by a dollar sign ($) as follows.  
  
## Syntax  
  
```  
$(macroname)  
```  
  
## Remarks  
 No spaces are allowed. The parentheses are optional if *macroname* is a single character. The definition string replaces $(*macroname*); an undefined macro is replaced by a null string.  
  
## What do you want to know more about?  
 [Macro substitution](../build/macro-substitution.md)  
  
## See Also  
 [Macros and NMAKE](../build/macros-and-nmake.md)


<!--HONumber=Jan17_HO1-->


