---
title: ModuleType Enumeration | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: reference
f1_keywords:
- module/Microsoft::WRL::ModuleType
dev_langs:
- C++
helpviewer_keywords:
- ModuleType enumeration
ms.assetid: 61a763af-a5a4-451d-8b40-815af507fcde
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
ms.openlocfilehash: 6d0b2df66b795f03d36070a80fd510fa61b24c7e

---
# ModuleType Enumeration
Specifies whether a module should support an in-process server or an out-of-process server.  
  
## Syntax  
  
```  
enum ModuleType;  
```  
  
## Members  
  
### Values  
  
|Name|Description|  
|----------|-----------------|  
|`InProc`|An in-process server.|  
|`OutOfProc`|An out-of-process server.|  
|`DisableCaching`|Disable caching mechanism on Module.|  
|`InProcDisableCaching`|Combination of `InProc` and `DisableCaching`.|  
|`OutOfProcDisableCaching`|Combination of `OutOfProc` and `DisableCaching`.|  
  
## Requirements  
 **Header:** module.h  
  
 **Namespace:** Microsoft::WRL  
  
## See Also  
 [Microsoft::WRL Namespace](../windows/microsoft-wrl-namespace.md)


<!--HONumber=Jan17_HO2-->


