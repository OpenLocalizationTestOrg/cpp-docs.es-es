---
title: 3.1.5 omp_get_num_procs Function | Microsoft Docs
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
ms.assetid: bbfbf17b-0c68-4ba6-a25d-07c36ecb551f
caps.latest.revision: 5
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
ms.openlocfilehash: cdd442548d99a190913b9258a83b4c001d580692

---
# 3.1.5 omp_get_num_procs Function
The `omp_get_num_procs` function returns the number of processors that are available to the program at the time the function is called. The format is as follows:  
  
```  
#include <omp.h>  
int omp_get_num_procs(void);  
```


<!--HONumber=Jan17_HO2-->


