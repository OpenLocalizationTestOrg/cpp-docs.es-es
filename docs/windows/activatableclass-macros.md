---
title: ActivatableClass Macros | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: reference
f1_keywords:
- ActivatableClass
- ActivatableClassWithFactory
- ActivatableClassWithFactoryEx
dev_langs:
- C++
helpviewer_keywords:
- ActivatableClassWithFactory
- ActivatableClass
- ActivatableClassWithFactoryEx
ms.assetid: 9bd64709-ec2c-4678-8c96-ea5982622bdd
caps.latest.revision: 6
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
ms.openlocfilehash: c86a132f4fc2e5148f808ba5f30719650a8f987f

---
# ActivatableClass Macros
Populates an internal cache that contains a factory that can create an instance of the specified class.  
  
## Syntax  
  
```cpp  
ActivatableClass(  
   className  
);  
  
ActivatableClassWithFactory(  
   className,   
   factory  
);  
  
ActivatableClassWithFactoryEx(  
   className,   
   factory,   
   serverName  
);  
  
```  
  
#### Parameters  
 `className`  
 Name of the class to create.  
  
 `factory`  
 Factory that will create an instance of the specified class.  
  
 `serverName`  
 A name that specifies a subset of factories in the module.  
  
## Remarks  
 Do not use these macros with classic COM unless you use the `#undef` directive to ensure that the **__WRL_WINRT_STRICT\_\_** macro definition is removed.  
  
## Requirements  
 **Header:** module.h  
  
 **Namespace:** Microsoft::WRL
 
 ## See Also
 [Module Class](../windows/module-class.md)


<!--HONumber=Jan17_HO2-->


