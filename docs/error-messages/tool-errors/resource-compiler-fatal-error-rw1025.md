---
title: Resource Compiler Fatal Error RW1025 | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: error-reference
f1_keywords:
- RW1025
dev_langs:
- C++
helpviewer_keywords:
- RW1025
ms.assetid: 561a02af-e7e0-442a-8ad3-a00b2ca1b62e
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
ms.openlocfilehash: 4029f07c4025720f92e7ca95cadcd915c542dc6e

---
# Resource Compiler Fatal Error RW1025
Out of far heap memory  
  
 Check for memory-resident software that might be taking up too much space. Use the CHKDSK program to find out how much memory you have.  
  
 If you are creating a large resource file, split the resource script into two files. After creating two .res files, use the MS-DOS command line to join them together:  
  
```  
copy first.res /b + second.res /b full.res  
```


<!--HONumber=Jan17_HO2-->


