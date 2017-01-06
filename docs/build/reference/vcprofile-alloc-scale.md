---
title: VCPROFILE_ALLOC_SCALE | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: article
f1_keywords:
- VCPROFILE_ALLOC_SCALE
dev_langs:
- C++
helpviewer_keywords:
- VCPROFILE_ALLOC_SCALE environment variable
ms.assetid: 5cb5ce27-f9b8-489b-b46c-d6e9bcab2d34
caps.latest.revision: 4
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
ms.openlocfilehash: 227a61aae98e356250aa5b8fc8717eb2d793dfd8

---
# VCPROFILE_ALLOC_SCALE
Modify the amount of memory allocated to hold the profile data.  
  
## Syntax  
  
```  
VCPROFILE_ALLOC_SCALE=scale_value  
```  
  
#### Parameters  
 `scale_value`  
 The scale value for the amount of memory you want for running test scenarios.  The default is 1.  
  
## Remarks  
 In rare cases, there will not be enough memory available to support gathering profile data when running test scenarios.  In those cases, you can increase the amount of memory with `VCPROFILE_ALLOC_SCALE`.  
  
 If you receive an error message during a test run that indicates that you have insufficient memory, assign a larger value to `VCPROFILE_ALLOC_SCALE`, until the test runs complete with no out-of-memory errors.  
  
## Example  
  
```  
set VCPROFILE_ALLOC_SCALE=2  
```  
  
## See Also  
 [Environment Variables for Profile-Guided Optimizations](../../build/reference/environment-variables-for-profile-guided-optimizations.md)


<!--HONumber=Jan17_HO1-->


