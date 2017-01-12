---
title: ML Nonfatal Error A2008 | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: article
f1_keywords:
- A2008
dev_langs:
- C++
helpviewer_keywords:
- A2008
ms.assetid: ca24157f-c88a-4678-ae06-3bc3cd956001
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
ms.openlocfilehash: c260a9ff0e59eefd9e326a2a1add431c8444db14

---
# ML Nonfatal Error A2008
**syntax error :**  
  
 A token at the current location caused a syntax error.  
  
 One of the following may have occurred:  
  
-   A dot prefix was added to or omitted from a directive.  
  
-   A reserved word (such as **C** or **SIZE**) was used as an identifier.  
  
-   An instruction was used that was not available with the current processor or coprocessor selection.  
  
-   A comparison run-time operator (such as `==`) was used in a conditional assembly statement instead of a relational operator (such as [EQ](../../assembler/masm/operator-eq.md)).  
  
-   An instruction or directive was given too few operands.  
  
-   An obsolete directive was used.  
  
## See Also  
 [ML Error Messages](../../assembler/masm/ml-error-messages.md)


<!--HONumber=Jan17_HO2-->


