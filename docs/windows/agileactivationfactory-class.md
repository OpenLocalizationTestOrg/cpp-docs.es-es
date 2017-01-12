---
title: AgileActivationFactory Class | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: reference
f1_keywords:
- module/Microsoft::WRL::AgileActivationFactory
dev_langs:
- C++
ms.assetid: fab98f32-bb93-4c0f-badb-49fbddb194b0
caps.latest.revision: 2
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
ms.openlocfilehash: 87b0e858cc218d9ebd47efd33a95d47b68ad3cfb

---
# AgileActivationFactory Class
Represents an apartment-friendly activation factory that implements [FtmBase](../windows/ftmbase-class.md).  
  
## Syntax  
  
```cpp  
template <  
   typename I0 = Details::Nil,   
   typename I1 = Details::Nil,   
   typename I2 = Details::Nil,   
FactoryCacheFlags cacheFlagValue = FactoryCacheDefault>  
class AgileActivationFactory :   
   public ActivationFactory<Implements<FtmBase, I0>, I1, I2, cacheFlagValue>{};  
```  
  
## Requirements  
 **Header:** module.h  
  
 **Namespace:** Microsoft::WRL  
  
## See Also  
 [Microsoft::WRL Namespace](../windows/microsoft-wrl-namespace.md)   
 [ActivationFactory Class](../windows/activationfactory-class.md)


<!--HONumber=Jan17_HO2-->


