---
title: Compiler Error C2567 | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: error-reference
f1_keywords:
- C2567
dev_langs:
- C++
helpviewer_keywords:
- C2567
ms.assetid: 9c140ac9-7059-47e6-9ba1-e7939c8c0dc3
caps.latest.revision: 4
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
ms.openlocfilehash: 6cd355d7654f931196acc324f7d58b99c6f25f29

---
# Compiler Error C2567
unable to open metadata in 'file', file may have been deleted or moved  
  
 A metadata file that was referenced in source (with `#using`) was not found in the same directory by the compiler back end process as it was by the compiler front end process. See [#using Directive](../../preprocessor/hash-using-directive-cpp.md) for more information.  
  
 C2567 could be caused if you compile with **/c** on one machine and then attempt a link-time code generation on another machine. For more information, see [/LTCG (Link-time Code Generation)](../../build/reference/ltcg-link-time-code-generation.md)).  
  
 It might also indicate that your computer had no  more memory.  
  
 To correct this error, make sure that the metadata file is in the same directory location for all phases of the build process.


<!--HONumber=Jan17_HO2-->


