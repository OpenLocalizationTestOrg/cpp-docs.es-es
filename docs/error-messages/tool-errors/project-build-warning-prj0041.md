---
title: Project Build Warning PRJ0041 | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: error-reference
f1_keywords:
- PRJ0041
dev_langs:
- C++
helpviewer_keywords:
- PRJ0041
ms.assetid: dc9f4cf9-6bd5-4222-89e8-7802a59bb96b
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
ms.openlocfilehash: d2654c0daa81a9b7cd8e0920aad35a902dc84a5f

---
# Project Build Warning PRJ0041
Cannot find missing dependency 'dependency' for file 'file'. Your project may still build, but may continue to appear out of date until this file is found.  
  
 A file (resource file or .idl/.odl file, for example, contained an include statement that the project system could not resolve.  
  
 Because the project system does not process preprocessor statements (#if, for example), the offending statement may not actually be part of the build.  
  
 To resolve this warning, delete all unnecessary code in .rc files or add placeholder files of the appropriate name.


<!--HONumber=Jan17_HO1-->


