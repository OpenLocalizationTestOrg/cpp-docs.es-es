---
title: Compiler Error C2333 | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: error-reference
f1_keywords:
- C2333
dev_langs:
- C++
helpviewer_keywords:
- C2333
ms.assetid: 2636fc1e-d3e7-4e68-8628-3c81a99ba813
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
ms.openlocfilehash: 6774fce0e198b9fe842e158483b0247a950a4a18

---
# Compiler Error C2333
'function' : error in function declaration; skipping function body  
  
 This error occurs after another error, for member functions defined inside their class.  
  
 The following sample generates C2333:  
  
```  
// C2333.cpp  
struct s1 {  
   s1(s1) {}   // C2333  
};  
```


<!--HONumber=Jan17_HO2-->


