---
title: Compiler Warning (level 1) C4086 | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-csharp
ms.tgt_pltfrm: 
ms.topic: article
f1_keywords:
- C4086
dev_langs:
- C++
helpviewer_keywords:
- C4086
ms.assetid: 9248831b-22bf-47af-8684-bfadb17e94fc
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
ms.openlocfilehash: 67d67b9ff4e03684b621ea2cd6415ebd0da071a5

---
# Compiler Warning (level 1) C4086
expected pragma parameter to be '1', '2', '4', '8', or '16'  
  
 The pragma parameter does not have the required value (1, 2, 4, 8, or 16).  
  
## Example  
  
```  
// C4086.cpp  
// compile with: /W1 /LD  
#pragma pack( 3 ) // C4086  
```


<!--HONumber=Jan17_HO2-->


