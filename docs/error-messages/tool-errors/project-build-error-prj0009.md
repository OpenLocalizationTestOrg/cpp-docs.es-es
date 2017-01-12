---
title: Project Build Error PRJ0009 | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: error-reference
f1_keywords:
- PRJ0009
dev_langs:
- C++
helpviewer_keywords:
- PRJ0009
ms.assetid: 89291778-cda4-495d-983f-ddcc06dfc98b
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
ms.openlocfilehash: 3e3d36b814bee46c799c63778fb8cb152eb0dcbf

---
# Project Build Error PRJ0009
Build log could not be opened for writing.  
  
 **Make sure that the file is not open by another process and is not write-protected.**  
  
 After setting the **Build Logging** property to **Yes** and performing a build or rebuild, Visual C++ was unable to open the build log in exclusive mode.  
  
 Inspect the **Build Logging** setting by opening the **Options** dialog box (on the **Tools** menu, click **Options** command) and then selecting **VC++ Build** in the **Projects** folder. The build file is called BuildLog.htm and is written to the intermediate directory $(IntDir).  
  
 Possible reasons for this error:  
  
-   You are running two processes of Visual C++ and trying to build the same configuration of the same project in both simultaneously.  
  
-   The build log file is opened in a process that locks the file.  
  
-   The user does not have permission to create a file.  
  
-   The current user does not have write access to the file BuildLog.htm.


<!--HONumber=Jan17_HO2-->


