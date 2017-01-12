---
title: EventSource::targets_ Data Member | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: reference
f1_keywords:
- event/Microsoft::WRL::EventSource::targets_
dev_langs:
- C++
helpviewer_keywords:
- targets_ data member
ms.assetid: 5d5cee05-3315-4514-bce2-19173c923c7d
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
ms.openlocfilehash: f6fdfc2d383df5a8fa39bfa4b3ac690ac2fe2ddf

---
# EventSource::targets_ Data Member
An array of one or more event handlers.  
  
## Syntax  
  
```  
ComPtr<Details::EventTargetArray> targets_;  
```  
  
## Remarks  
 When the event that is represented by the current EventSource object occurs, the event handlers are called.  
  
## Requirements  
 **Header:** event.h  
  
 **Namespace:** Microsoft::WRL
 
 ## See Also
 [EventSource Class](../windows/eventsource-class.md)


<!--HONumber=Jan17_HO2-->


