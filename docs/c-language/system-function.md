---
title: system Function | Microsoft Docs
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
- C
helpviewer_keywords:
- system function
ms.assetid: 0786ccdc-20cd-4d96-b3d8-3230507c3066
caps.latest.revision: 7
author: mikeblome
ms.author: mblome
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
ms.openlocfilehash: 59f63ad15e54775f94dea734263b8c906221b7f7

---
# system Function
**ANSI 4.10.4.5** The contents and mode of execution of the string by the **system** function  
  
 The **system** function executes an internal operating system command, or an .EXE, .COM (.CMD in Windows NT) or .BAT file from within a C program rather than from the command line.  
  
 The system function finds the command interpreter, which is typically CMD.EXE in the Windows NT operating system or COMMAND.COM in Windows. The system function then passes the argument string to the command interpreter.  
  
 For more information, see [system, _wsystem](../c-runtime-library/reference/system-wsystem.md).  
  
## See Also  
 [Library Functions](../c-language/library-functions.md)


<!--HONumber=Jan17_HO2-->


