---
title: MAKE Fatal Error U1087 | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: error-reference
f1_keywords:
- U1087
dev_langs:
- C++
helpviewer_keywords:
- U1087
ms.assetid: 5236ab54-e117-484d-99c3-852b061fd3d0
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
ms.openlocfilehash: 5ee2e692e4240a9d7e380a553008a192e75d53db

---
# NMAKE Fatal Error U1087
cannot have : and :: dependents for same target  
  
 A target cannot be specified in both a single-colon (**:**) and a double-colon (`::`) dependency.  
  
 To specify a target in multiple description blocks, use `::` in each dependency line.


<!--HONumber=Jan17_HO1-->


