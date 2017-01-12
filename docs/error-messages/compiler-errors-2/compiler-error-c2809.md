---
title: Compiler Error C2809 | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: error-reference
f1_keywords:
- C2809
dev_langs:
- C++
helpviewer_keywords:
- C2809
ms.assetid: ce796b8e-1a8c-4074-995d-1ad09afd0e93
caps.latest.revision: 8
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
ms.openlocfilehash: 1b5dc107872dc35ebf1e6f956fb89a3e401928b7

---
# Compiler Error C2809
'operator operator' has no formal parameters  
  
 The operator lacks required parameters.  
  
 The following sample generates C2809:  
  
```  
// C2809.cpp  
// compile with: /c  
class A{};  
int operator+ ();   // C2809  
int operator+ (A);   // OK  
```


<!--HONumber=Jan17_HO2-->


