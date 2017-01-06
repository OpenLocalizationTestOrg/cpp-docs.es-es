---
title: Linker Tools Error LNK2023 | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: error-reference
f1_keywords:
- LNK2023
dev_langs:
- C++
helpviewer_keywords:
- LNK2023
ms.assetid: c99e35a8-739a-4a20-a715-29b8c3744703
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
ms.openlocfilehash: cc7dab6643696dd2b4f9dc2be7689f819832084b

---
# Linker Tools Error LNK2023
bad dll or entry point \<dll or entry point>  
  
 The linker is loading an incorrect version of msobj90.dll. Ensure that link.exe and msobj90.dll in your path have the same version.  
  
 A dependency of msobj90.dll may not be present. The dependency list for msobj90.dll is:  
  
-   Msvcr90.dll  
  
-   Kernel32.dll  
  
 Check your machine for any other copies of msobj90.dll that may be out of date.


<!--HONumber=Jan17_HO1-->


