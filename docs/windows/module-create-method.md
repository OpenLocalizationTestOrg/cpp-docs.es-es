---
title: Module::Create Method | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: reference
f1_keywords:
- module/Microsoft::WRL::Module::Create
dev_langs:
- C++
helpviewer_keywords:
- Create method
ms.assetid: bfa97fd7-5226-4604-92a5-3b9697053e64
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
ms.openlocfilehash: cde932f17a30b2c87d30b8dc41e1c31b34a5c57e

---
# Module::Create Method
Creates an instance of a module.  
  
## Syntax  
  
```  
WRL_NOTHROW static Module& Create();  
template<  
   typename T  
>  
WRL_NOTHROW static Module& Create(  
   T callback  
);  
template<  
   typename T  
>  
WRL_NOTHROW static Module& Create(  
   _In_ T* object,  
   _In_ void (T::* method)()  
);  
```  
  
#### Parameters  
 `T`  
 Module type.  
  
 `callback`  
 Called when the last instance object of the module is released.  
  
 `object`  
 The `object` and `method` parameters are used in combination. Points to the last instance object when the last instance object in the module is released.  
  
 `method`  
 The `object` and `method` parameters are used in combination. Points to the method of the last instance object when the last instance object in the module is released.  
  
## Return Value  
 Reference to the module.  
  
## Requirements  
 **Header:** module.h  
  
 **Namespace:** Microsoft::WRL  
  
## See Also  
[Module Class](../windows/module-class.md)

 


<!--HONumber=Jan17_HO2-->


