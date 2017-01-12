---
title: Fatal Error C1352 | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-csharp
ms.tgt_pltfrm: 
ms.topic: article
f1_keywords:
- C1352
dev_langs:
- C++
helpviewer_keywords:
- C1352
ms.assetid: d044e8b0-b6ef-4d57-8eb5-6254071be707
caps.latest.revision: 7
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
ms.openlocfilehash: db8e3be196283a64e58f050918dd951332fb9546

---
# Fatal Error C1352
Invalid or corrupt MSIL in function 'function' from module 'file'  
  
 A .netmodule was passed to the compiler, but the compiler detected corruption in the file.  Ask the person who produced the .netmodule to investigate.  
  
 The compiler does not check .netmodule files for all types of corruption.  It does, however, check that all control paths in a function contain a return statement.  
  
 For more information, see [.netmodule Files as Linker Input](../../build/reference/netmodule-files-as-linker-input.md).


<!--HONumber=Jan17_HO2-->


