---
title: FactoryCache::cookie Data Member | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: reference
f1_keywords:
- module/Microsoft::WRL::Details::FactoryCache::cookie
dev_langs:
- C++
helpviewer_keywords:
- cookie data member
ms.assetid: b1bc79af-a896-4e3b-8afa-64733022eddf
caps.latest.revision: 7
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
ms.openlocfilehash: 940baff3d3a2c8e6a554c60c1f1c9d1c5f8a26c4

---
# FactoryCache::cookie Data Member
Supports the [!INCLUDE[cppwrl](../windows/includes/cppwrl_md.md)] infrastructure and is not intended to be used directly from your code.  
  
## Syntax  
  
```  
union {   
   WINRT_REGISTRATION_COOKIE winrt;  
   DWORD com;   
} cookie;  
```  
  
## Remarks  
 Contains a value that identifies a registered [!INCLUDE[wrt](../atl/reference/includes/wrt_md.md)] or COM class object, and is later used to unregister the object.  
  
## Requirements  
 **Header:** module.h  
  
 **Namespace:** Microsoft::WRL::Details  
  
## See Also  
 [FactoryCache Structure](../windows/factorycache-structure.md)   
 [Microsoft::WRL::Details Namespace](../windows/microsoft-wrl-details-namespace.md)


<!--HONumber=Jan17_HO2-->


