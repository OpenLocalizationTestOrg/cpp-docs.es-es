---
title: A.1   Executing a Simple Loop in Parallel | Microsoft Docs
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
ms.assetid: b8aaacae-b20d-4b16-a540-54ccbf09582b
caps.latest.revision: 8
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
ms.openlocfilehash: f5f7b99d181541aaca02c6e0ede879a511f55324

---
# A.1   Executing a Simple Loop in Parallel
The following example demonstrates how to parallelize a simple loop using the `parallel for` directive ([Section 2.5.1](../../parallel/openmp/2-5-1-parallel-for-construct.md) on page 16). The loop iteration variable is private by default, so it is not necessary to specify it explicitly in a private clause.  
  
```  
#pragma omp parallel for  
    for (i=1; i<n; i++)  
        b[i] = (a[i] + a[i-1]) / 2.0;  
```


<!--HONumber=Jan17_HO2-->


