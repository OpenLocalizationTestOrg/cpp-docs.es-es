---
title: InterfaceList Structure | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: reference
f1_keywords:
- implements/Microsoft::WRL::Details::InterfaceList
dev_langs:
- C++
helpviewer_keywords:
- InterfaceList structure
ms.assetid: 6ec3228d-eb3e-4b7e-aef1-7dcf17bdf61a
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
ms.openlocfilehash: 864fbef42f18b549e6bfc16be5a6fa2efdc901d2

---
# InterfaceList Structure
Supports the WRL infrastructure and is not intended to be used directly from your code.  
  
## Syntax  
  
```  
template <  
   typename T,  
   typename U  
>  
struct InterfaceList;  
```  
  
#### Parameters  
 `T`  
 An interface name; the first interface in the recursive list.  
  
 `U`  
 An interface name; the remaining interfaces in the recursive list.  
  
## Remarks  
 Used to create a recursive list of interfaces.  
  
## Members  
  
### Public Typedefs  
  
|Name|Description|  
|----------|-----------------|  
|`FirstT`|Synonym for template parameter `T`.|  
|`RestT`|Synonym for template parameter `U`.|  
  
## Inheritance Hierarchy  
 `InterfaceList`  
  
## Requirements  
 **Header:** implements.h  
  
 **Namespace:** Microsoft::WRL::Details  
  
## See Also  
 [Microsoft::WRL::Details Namespace](../windows/microsoft-wrl-details-namespace.md)


<!--HONumber=Jan17_HO2-->


