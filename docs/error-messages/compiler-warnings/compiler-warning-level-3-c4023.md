---
title: Compiler Warning (level 3) C4023 | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-csharp
ms.tgt_pltfrm: 
ms.topic: article
f1_keywords:
- C4023
dev_langs:
- C++
helpviewer_keywords:
- C4023
ms.assetid: 615d5374-d7c1-42eb-acfd-917c053270c8
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
ms.openlocfilehash: f7902af5038880b0b8e0fee0b9fd64a256799fd7

---
# Compiler Warning (level 3) C4023
'symbol' : based pointer passed to unprototyped function : parameter number  
  
 Passing a based pointer to an unprototyped function causes the pointer to be normalized, with unpredictable results.  
  
 This warning may be fixed if you use prototype functions that are passed based pointers.


<!--HONumber=Jan17_HO1-->


