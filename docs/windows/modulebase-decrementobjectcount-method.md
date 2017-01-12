---
title: ModuleBase::DecrementObjectCount Method | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: reference
f1_keywords:
- implements/Microsoft::WRL::Details::ModuleBase::DecrementObjectCount
dev_langs:
- C++
helpviewer_keywords:
- DecrementObjectCount method
ms.assetid: a016fb07-a36e-40cd-bc7b-8f6e85e256e7
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
ms.openlocfilehash: 4d90ee2ece6c22bc83dc49214180c7e90a3f95ab

---
# ModuleBase::DecrementObjectCount Method
Supports the WRL infrastructure and is not intended to be used directly from your code.  
  
## Syntax  
  
```  
virtual long DecrementObjectCount() = 0;  
```  
  
## Return Value  
 The count before the decrement operation.  
  
## Remarks  
 When implemented, decrements the number of objects tracked by the module.  
  
## Requirements  
 **Header:** implements.h  
  
 **Namespace:** Microsoft::WRL::Details  
  
## See Also  
 [ModuleBase Class](../windows/modulebase-class.md)   
 [Microsoft::WRL::Details Namespace](../windows/microsoft-wrl-details-namespace.md)


<!--HONumber=Jan17_HO2-->


