---
title: Module::ReleaseNotifier::ReleaseNotifier Constructor | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: reference
f1_keywords:
- module/Microsoft::WRL::Module::ReleaseNotifier::ReleaseNotifier
dev_langs:
- C++
helpviewer_keywords:
- ReleaseNotifier, constructor
ms.assetid: 889a3c9a-2366-44a1-ba7d-a59c1885e7f3
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
ms.openlocfilehash: f97b2d7cdc7db9abb0fd44552a2ff88ea4d2222f

---
# Module::ReleaseNotifier::ReleaseNotifier Constructor
Initializes a new instance of the Module::ReleaseNotifier class.  
  
## Syntax  
  
```cpp  
ReleaseNotifier(bool release) throw();  
```  
  
#### Parameters  
 `release`  
 `true` to delete this instance when the Release method is called; `false` to not delete this instance.  
  
## Exceptions  
  
## Requirements  
 **Header:** module.h  
  
 **Namespace:** Microsoft::WRL  
  
## See Also  
 [Module::ReleaseNotifier Class](../windows/module-releasenotifier-class.md)


<!--HONumber=Jan17_HO1-->


