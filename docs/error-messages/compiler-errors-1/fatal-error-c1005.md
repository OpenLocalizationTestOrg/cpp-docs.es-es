---
title: Fatal Error C1005 | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: error-reference
f1_keywords:
- C1005
dev_langs:
- C++
helpviewer_keywords:
- C1005
ms.assetid: 150daf8e-a38a-4669-9c1a-a05b5a1f65ef
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
ms.openlocfilehash: 0766e60fb51a5f983e5617b5e470ac97a5b8e51a

---
# Fatal Error C1005
string too big for buffer  
  
 A string in a compiler intermediate file overflowed a buffer.  
  
 You could get this error when the parameter that you pass to either the [/Fd](../../build/reference/fd-program-database-file-name.md) or [/Yl](../../build/reference/yl-inject-pch-reference-for-debug-library.md) compiler options is greater than 256 bytes.


<!--HONumber=Jan17_HO2-->


