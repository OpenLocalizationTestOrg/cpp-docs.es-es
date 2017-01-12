---
title: A.21   Scoping Variables with the private Clause | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: article
dev_langs:
- C++
ms.assetid: 7cdb4a7f-af24-44ac-9d33-e43840bc8f3d
caps.latest.revision: 7
author: mikeblome
ms.author: mblome
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
ms.openlocfilehash: fc11cec21e8c1bb747df03e24bc70489b055b925

---
# A.21   Scoping Variables with the private Clause
The values of `i` and `j` in the following example are undefined on exit from the parallel region:  
  
```  
int i, j;  
i = 1;  
j = 2;  
#pragma omp parallel private(i) firstprivate(j)  
{  
  i = 3;  
  j = j + 2;  
}  
printf_s("%d %d\n", i, j);  
```  
  
 For more information on the `private` clause, see [Section 2.7.2.1](../../parallel/openmp/2-7-2-1-private.md) on page 25.


<!--HONumber=Jan17_HO2-->


