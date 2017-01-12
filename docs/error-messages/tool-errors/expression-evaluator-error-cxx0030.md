---
title: Expression Evaluator Error CXX0030 | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: error-reference
f1_keywords:
- CXX0030
dev_langs:
- C++
helpviewer_keywords:
- CAN0030
- CXX0030
ms.assetid: ada8b48c-09c8-49bf-ae23-313ed663c4fe
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
ms.openlocfilehash: 4a4e82e51943db988805f1ba76495218e8188d2e

---
# Expression Evaluator Error CXX0030
expression not evaluatable  
  
 The debugger's expression evaluator could not obtain a value for the expression as written. One likely cause is that the expression refers to memory that is outside the program's address space (dereferencing a null pointer is one example). Windows does not allow access to memory that is outside of the program's address space.  
  
 You may want to rewrite your expression using parentheses to control the order of evaluation.  
  
 This error is identical to CAN0030.


<!--HONumber=Jan17_HO2-->


