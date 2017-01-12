---
title: SyncLockT::IsLocked Method | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: reference
f1_keywords:
- corewrappers/Microsoft::WRL::Wrappers::Details::SyncLockT::IsLocked
dev_langs:
- C++
helpviewer_keywords:
- IsLocked method
ms.assetid: a81fea43-f99a-4708-812a-7fd6af500d3d
caps.latest.revision: 4
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
ms.openlocfilehash: 7c0a6ddc2dd8c6f0a00c1f4e668619da20d14be6

---
# SyncLockT::IsLocked Method
Supports the WRL infrastructure and is not intended to be used directly from your code.  
  
## Syntax  
  
```  
bool IsLocked() const;  
```  
  
## Return Value  
 **true** if the SyncLockT object is locked; otherwise, **false**.  
  
## Remarks  
 Indicates whether the current SyncLockT object owns a resource; that is, the SyncLockT object is *locked*.  
  
## Requirements  
 **Header:** corewrappers.h  
  
 **Namespace:** Microsoft::WRL::Wrappers::Details  
  
## See Also  
 [SyncLockT Class](../windows/synclockt-class.md)


<!--HONumber=Jan17_HO2-->


