---
title: ComPtr::Swap Method | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: reference
f1_keywords:
- client/Microsoft::WRL::ComPtr::Swap
dev_langs:
- C++
helpviewer_keywords:
- Swap method
ms.assetid: 74275f00-b24e-4b4c-b8b6-ac2aa2dd7ae9
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
ms.openlocfilehash: bc49ba60e09bea2a0f02adba830d8ed9d787db96

---
# ComPtr::Swap Method
Exchanges the interface managed by the current ComPtr with the interface managed by the specified ComPtr.  
  
## Syntax  
  
```  
void Swap(  
   _Inout_ ComPtr&& r  
);  
  
void Swap(  
   _Inout_ ComPtr& r  
);  
```  
  
#### Parameters  
 `r`  
 A ComPtr.  
  
## Requirements  
 **Header:** client.h  
  
 **Namespace:** Microsoft::WRL  
  
## See Also  
 [ComPtr Class](../windows/comptr-class.md)


<!--HONumber=Jan17_HO2-->


