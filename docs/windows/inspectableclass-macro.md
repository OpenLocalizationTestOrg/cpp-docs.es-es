---
title: InspectableClass Macro | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: reference
f1_keywords:
- implements/Microsoft::WRL::InspectableClass
dev_langs:
- C++
ms.assetid: ff390b26-58cc-424f-87ac-1fe3cc692b59
caps.latest.revision: 4
author: mikeblome
ms.author: mblome
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
ms.openlocfilehash: 591fdc4aebd670724258246dbdbc6f06c478b4d0

---
# InspectableClass Macro
Sets the runtime class name and trust level.  
  
## Syntax  
  
```cpp  
  
InspectableClass(  
   runtimeClassName,   
   trustLevel)  
```  
  
#### Parameters  
 `runtimeClassName`  
 The full textual name of the runtime class.  
  
 `trustLevel`  
 One of the [TrustLevel](http://msdn.microsoft.com/library/br224625.aspx) enumerated values.  
  
## Remarks  
 The `InspectableClass` macro can be used only with [!INCLUDE[wrt](../atl/reference/includes/wrt_md.md)] types.  
  
## Requirements  
 **Header:** implements.h  
  
 **Namespace:** Microsoft::WRL  
  
## See Also  
 [RuntimeClass Class](../windows/runtimeclass-class.md)


<!--HONumber=Jan17_HO2-->


