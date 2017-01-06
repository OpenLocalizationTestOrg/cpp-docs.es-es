---
title: Fatal Error C1852 | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-csharp
ms.tgt_pltfrm: 
ms.topic: article
f1_keywords:
- C1852
dev_langs:
- C++
helpviewer_keywords:
- C1852
ms.assetid: fa011004-b8d6-46f1-ba80-4785e4ce137f
caps.latest.revision: 6
author: corob-msft
ms.author: corob
manager: ghogen
translation.priority.ht:
- de-de
- es-es
- fr-fr
- it-it
- ja-jp
- ko-kr
- ru-ru
- zh-cn
- zh-tw
translation.priority.mt:
- cs-cz
- pl-pl
- pt-br
- tr-tr
translationtype: Human Translation
ms.sourcegitcommit: 3168772cbb7e8127523bc2fc2da5cc9b4f59beb8
ms.openlocfilehash: 9f74717ee3f129869428efc7082a0d922fc6090b

---
# Fatal Error C1852
'filename' is not a valid precompiled header file  
  
 The file is not a precompiled header.  
  
### To fix by checking the following possible causes  
  
1.  Invalid file specified with **/Yu** or **#pragma hdrstop**.  
  
2.  The compiler assumes a file extension of .pch if you do not specify otherwise.


<!--HONumber=Jan17_HO1-->


