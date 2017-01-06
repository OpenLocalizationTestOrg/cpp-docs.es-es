---
title: Command-Line Warning D9026 | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: error-reference
f1_keywords:
- D9026
dev_langs:
- C++
helpviewer_keywords:
- D9026
ms.assetid: 149fe5e3-5329-4be8-b871-49dfd423aaba
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
ms.openlocfilehash: 6e6153a85437ddd61047f9eabd0071eca3900c28

---
# Command-Line Warning D9026
options apply to entire command line  
  
 An option was specified on a command after a filename was specified. The option was applied to the file that preceded it.  
  
 For example, in the command  
  
```  
CL verdi.c /G5 puccini.c  
```  
  
 the file VERDI.c will be compiled using the /G5 option, not the /G4 default.  
  
 This behavior is different from that of some previous versions, which applied only the options specified before the filename, resulting in VERDI.c being compiled using /G4 and PUCCINI.c being compiled using /G5.


<!--HONumber=Jan17_HO1-->


