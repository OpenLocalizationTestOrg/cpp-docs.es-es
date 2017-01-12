---
title: -TLS | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: article
f1_keywords:
- /TLS
dev_langs:
- C++
helpviewer_keywords:
- /TLS dumpbin option
- -TLS dumpbin option
ms.assetid: 2b3f48f9-cac4-4351-b15c-2833b43bc709
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
ms.openlocfilehash: b37cb3f374233e7780ecdc1d2b02e6a5ee29e3f3

---
# /TLS
Displays the IMAGE_TLS_DIRECTORY structure from an executable.  
  
## Remarks  
 /TLS displays the fields of the TLS structure as well as the addresses of the TLS callback functions.  
  
 If a program does not use thread local storage, its image will not contain a TLS structure.  See [thread](../../cpp/thread.md) for more information.  
  
 IMAGE_TLS_DIRECTORY is defined in winnt.h.  
  
## See Also  
 [DUMPBIN Options](../../build/reference/dumpbin-options.md)


<!--HONumber=Jan17_HO2-->


