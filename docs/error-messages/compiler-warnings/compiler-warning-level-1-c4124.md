---
title: Compiler Warning (level 1) C4124 | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: error-reference
f1_keywords:
- C4124
dev_langs:
- C++
helpviewer_keywords:
- C4124
ms.assetid: c08c3a65-9584-47a1-a147-44f00c4b230e
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
ms.openlocfilehash: 8f367d8ec2360939d499c9f4e53ee690f860cc18

---
# Compiler Warning (level 1) C4124
__fastcall with stack checking is inefficient  
  
 The `__fastcall` keyword was used with stack checking enabled.  
  
 The `__fastcall` convention generates faster code, but stack checking causes slower code. When using `__fastcall`, turn off stack checking with the **check_stack** pragma or /Gs.  
  
 This warning is issued only for the first function declared under these conditions.


<!--HONumber=Jan17_HO2-->


