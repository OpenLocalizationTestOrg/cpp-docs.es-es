---
title: Compiler Warning (level 2) C4308 | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: error-reference
f1_keywords:
- C4308
dev_langs:
- C++
helpviewer_keywords:
- C4308
ms.assetid: d4e5c53c-71b2-4bbc-8a7c-3a2a3180d9d9
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
ms.openlocfilehash: 7c3239927696587e21065c6daed2c554076f1c86

---
# Compiler Warning (level 2) C4308
negative integral constant converted to unsigned type  
  
 An expression converts a negative integer constant to an unsigned type. The result of the expression is probably meaningless.  
  
## Example  
  
```  
// C4308.cpp  
// compile with: /W2  
unsigned int u = (-5 + 3U);   // C4308  
  
int main()  
{  
}  
```


<!--HONumber=Jan17_HO2-->


