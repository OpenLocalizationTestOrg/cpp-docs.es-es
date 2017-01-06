---
title: Linker Tools Error LNK1223 | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: error-reference
f1_keywords:
- LNK1223
dev_langs:
- C++
helpviewer_keywords:
- LNK1223
ms.assetid: c4728c36-daee-462f-a1c7-8733dcdec88e
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
ms.openlocfilehash: 066d4768d58b31e75a0b436c84bff019993f35e2

---
# Linker Tools Error LNK1223
invalid or corrupt file: file contains invalid .pdata contributions  
  
 For RISC platforms that use pdata, this error will occur if the compiler emitted a .pdata section with unsorted entries.  
  
 To fix this issue, try compiling without [/GL (Whole Program Optimization)](../../error-messages/tool-errors/linker-tools-error-lnk1223.md) enabled. Empty function bodies can also cause this error in some cases.


<!--HONumber=Jan17_HO1-->


