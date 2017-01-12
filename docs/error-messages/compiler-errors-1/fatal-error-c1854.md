---
title: Fatal Error C1854 | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: error-reference
f1_keywords:
- C1854
dev_langs:
- C++
helpviewer_keywords:
- C1854
ms.assetid: 8c21a9cc-1737-475c-9e57-8725cd8937c1
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
ms.openlocfilehash: 7c1f3add044c68a749ee01843a6de3a5398f351e

---
# Fatal Error C1854
cannot overwrite information formed during creation of the precompiled header in object file: 'filename'  
  
 You specified the **/Yu** (use precompiled header) option after specifying the **/Yc** (create precompiled header) option for the same file. Certain declarations (such as declarations including `__declspec` `dllexport`) make this invalid.


<!--HONumber=Jan17_HO2-->


