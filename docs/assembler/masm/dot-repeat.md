---
title: .REPEAT | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: article
f1_keywords:
- .REPEAT
dev_langs:
- C++
helpviewer_keywords:
- .REPEAT directive
ms.assetid: cb8ad8c6-587b-42f9-a0ad-b5316a24918c
caps.latest.revision: 6
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
ms.openlocfilehash: e5ca3be2bd42e9f9afaff8673cbc203768aea53e

---
# .REPEAT
Generates code that repeats execution of the block of *statements* until `condition` becomes true. [.UNTILCXZ](../../assembler/masm/dot-untilcxz.md), which becomes true when CX is zero, may be substituted for [.UNTIL](../../assembler/masm/dot-until.md). The `condition` is optional with **.UNTILCXZ**.  
  
## Syntax  
  
```  
  
   .REPEAT  
statements  
.UNTIL condition  
```  
  
## See Also  
 [Directives Reference](../../assembler/masm/directives-reference.md)


<!--HONumber=Jan17_HO2-->


