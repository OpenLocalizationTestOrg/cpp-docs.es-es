---
title: Linker Tools Warning LNK4219 | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: error-reference
f1_keywords:
- LNK4219
dev_langs:
- C++
helpviewer_keywords:
- LNK4219
ms.assetid: 363fedf4-b10c-4985-811a-55a9fba688d6
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
ms.openlocfilehash: ab241e13f266158fa0a7bd09036ab2131718f554

---
# Linker Tools Warning LNK4219
fixup name fixup overflow. Target 'target symbol name' is out of range, inserting thunk  
  
 The linker inserted a thunk in a situation where the address or offset was unable to fit in the given instruction because the target symbol is too far away from the instruction's location.  
  
 You may want to reorder the image (using the [/ORDER](../../build/reference/order-put-functions-in-order.md) option, for example) to avoid the extra level of indirection.


<!--HONumber=Jan17_HO2-->


