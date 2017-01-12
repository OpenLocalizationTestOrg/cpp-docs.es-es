---
title: ModuleBase::IncrementObjectCount Method | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: reference
f1_keywords:
- implements/Microsoft::WRL::Details::ModuleBase::IncrementObjectCount
dev_langs:
- C++
helpviewer_keywords:
- IncrementObjectCount method
ms.assetid: 2d70b472-684c-4bb7-8bab-09505cfcaf28
caps.latest.revision: 5
author: mikeblome
ms.author: mblome
manager: ghogen
translation.priority.ht:
- de-de
- es-es
- fr-fr
- it-it
- ja-jp
- ko-kr
- ru-ru
- zh-cn
- zh-tw
translation.priority.mt:
- cs-cz
- pl-pl
- pt-br
- tr-tr
translationtype: Human Translation
ms.sourcegitcommit: 3168772cbb7e8127523bc2fc2da5cc9b4f59beb8
ms.openlocfilehash: da4e02a860c91192bdab8dede60357d85d0cc582

---
# ModuleBase::IncrementObjectCount Method
Supports the WRL infrastructure and is not intended to be used directly from your code.  
  
## Syntax  
  
```  
virtual long IncrementObjectCount() = 0;  
```  
  
## Return Value  
 The count before the increment operation.  
  
## Remarks  
 When implemented, increments the number of objects tracked by the module.  
  
## Requirements  
 **Header:** implements.h  
  
 **Namespace:** Microsoft::WRL::Details  
  
## See Also  
 [ModuleBase Class](../windows/modulebase-class.md)   
 [Microsoft::WRL::Details Namespace](../windows/microsoft-wrl-details-namespace.md)


<!--HONumber=Jan17_HO2-->


