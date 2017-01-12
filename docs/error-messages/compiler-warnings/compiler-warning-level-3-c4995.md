---
title: Compiler Warning (level 3) C4995 | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: error-reference
f1_keywords:
- C4995
dev_langs:
- C++
helpviewer_keywords:
- C4995
ms.assetid: c6b61755-4730-4947-ad4d-d1c2bc82585a
caps.latest.revision: 9
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
ms.openlocfilehash: 253645d6ea22f694e657c3391bdb723b75e086d6

---
# Compiler Warning (level 3) C4995
'function': name was marked as #pragma deprecated  
  
 The compiler encountered a function that was marked with pragma [deprecated](../../preprocessor/deprecated-c-cpp.md). The function may no longer be supported in a future release. You can turn this warning off with the [warning](../../preprocessor/warning.md) pragma (example below).  
  
## Example  
 The following sample generates C4995:  
  
```  
// C4995.cpp  
// compile with: /W3  
#include <stdio.h>  
  
// #pragma warning(disable : 4995)  
void func1(void)  
{  
    printf("\nIn func1");  
}  
  
int main()   
{  
    func1();  
    #pragma deprecated(func1)  
    func1();   // C4995  
}  
```


<!--HONumber=Jan17_HO2-->


