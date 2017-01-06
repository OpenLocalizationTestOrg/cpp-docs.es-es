---
title: Exit Codes from NMAKE | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: article
dev_langs:
- C++
helpviewer_keywords:
- NMAKE program, exit codes
- exit codes
ms.assetid: 75f6913c-1da5-4572-a2d3-8a4e058bed15
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
ms.openlocfilehash: d29d857ba6520a3f3165ec1e950196e147a727c1

---
# Exit Codes from NMAKE
NMAKE returns the following exit codes:  
  
|Code|Meaning|  
|----------|-------------|  
|0|No error (possibly a warning)|  
|1|Incomplete build (issued only when /K is used)|  
|2|Program error, possibly due to one of the following:|  
||-   A syntax error in the makefile|  
||-   An error or exit code from a command|  
||-   An interruption by the user|  
|4|System error — out of memory|  
|255|Target is not up-to-date (issued only when /Q is used)|  
  
## See Also  
 [Running NMAKE](../build/running-nmake.md)


<!--HONumber=Jan17_HO1-->


