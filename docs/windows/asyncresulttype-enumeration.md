---
title: AsyncResultType Enumeration | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: reference
f1_keywords:
- async/Microsoft::WRL::AsyncResultType
dev_langs:
- C++
helpviewer_keywords:
- AsyncResultType enumeration
ms.assetid: 4195d234-3f3f-4363-9118-6ad2a7551cf2
caps.latest.revision: 3
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
ms.openlocfilehash: ab94fee065a7d33556f2324d1437ad4dfb257711

---
# AsyncResultType Enumeration
Specifies the type of result returned by the GetResults() method.  
  
## Syntax  
  
```  
enum AsyncResultType;  
```  
  
## Members  
  
### Values  
  
|Name|Description|  
|----------|-----------------|  
|`MultipleResults`|A set of multiple results, which are presented progressively between Start state and before Close() is called.|  
|`SingleResult`|A single result, which is presented after the Complete event occurs.|  
  
## Requirements  
 **Header:** async.h  
  
 **Namespace:** Microsoft::WRL  
  
## See Also  
 [Microsoft::WRL Namespace](../windows/microsoft-wrl-namespace.md)


<!--HONumber=Jan17_HO2-->


