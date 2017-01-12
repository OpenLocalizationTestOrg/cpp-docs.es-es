---
title: 3.1.10 omp_get_nested Function | Microsoft Docs
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
ms.assetid: 48736a25-5c6e-4e2d-aad0-421087663a3c
caps.latest.revision: 6
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
ms.openlocfilehash: 88f141d52a97d11e867a5d31584438575282ae7c

---
# 3.1.10 omp_get_nested Function
The `omp_get_nested` function returns a nonzero value if nested parallelism is enabled and 0 if it is disabled. For more information on nested parallelism, see Section 3.1.9 on page 40. The format is as follows:  
  
```  
#include <omp.h>  
int omp_get_nested(void);  
```  
  
 If an implementation does not implement nested parallelism, this function always returns 0.


<!--HONumber=Jan17_HO2-->


