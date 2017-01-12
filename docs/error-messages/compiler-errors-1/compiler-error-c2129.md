---
title: Compiler Error C2129 | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: error-reference
f1_keywords:
- C2129
dev_langs:
- C++
helpviewer_keywords:
- C2129
ms.assetid: 21a8223e-1d22-4baa-9ca1-922b7f751dd0
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
ms.openlocfilehash: a84dacca59a1cb93d91ffe0a561196df8c6b3975

---
# Compiler Error C2129
static function 'function' declared but not defined  
  
 A forward reference is made to a `static` function that is never defined.  
  
 A `static` function must be defined within file scope. If the function is defined in another file, it must be declared `extern`.


<!--HONumber=Jan17_HO2-->


