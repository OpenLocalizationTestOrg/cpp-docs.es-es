---
title: Compiler Error C2528 | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: error-reference
f1_keywords:
- C2528
dev_langs:
- C++
helpviewer_keywords:
- C2528
ms.assetid: 2ea9d583-67a8-4b16-b35f-a50eeffc03c4
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
ms.openlocfilehash: 1ecf5b610b42e84e3103b754eb25a5ac051025ef

---
# Compiler Error C2528
'name' : pointer to reference is illegal  
  
 You cannot declare a pointer to a reference. Dereference the variable before declaring a pointer to it.  
  
 The following sample generates C2528:  
  
```  
// C2528.cpp  
int i;  
int &ir = i;  
int & (*irptr) = ir;    // C2528  
```


<!--HONumber=Jan17_HO2-->


