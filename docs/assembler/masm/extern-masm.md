---
title: EXTERN (MASM) | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: article
f1_keywords:
- extern
dev_langs:
- C++
helpviewer_keywords:
- EXTERN directive
ms.assetid: 667d703d-3aaf-4139-a586-29bc5dab1aff
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
ms.openlocfilehash: f3dfe8db75572c09e3c16e1cd25dabd427e98c77

---
# EXTERN (MASM)
Defines one or more external variables, labels, or symbols called *name* whose type is `type`.  
  
## Syntax  
  
```  
  
   EXTERN [[langtype]] name [[(altid)]] :  
type [[, [[langtype]] name [[(altid)]] :type]]...  
```  
  
## Remarks  
 The `type` can be [ABS](../../assembler/masm/operator-abs.md), which imports *name* as a constant. Same as [EXTRN](../../assembler/masm/extrn.md).  
  
## See Also  
 [Directives Reference](../../assembler/masm/directives-reference.md)


<!--HONumber=Jan17_HO2-->


