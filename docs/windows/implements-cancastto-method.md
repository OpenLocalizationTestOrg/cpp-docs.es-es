---
title: Implements::CanCastTo Method | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: reference
f1_keywords:
- implements/Microsoft::WRL::Implements::CanCastTo
dev_langs:
- C++
helpviewer_keywords:
- CanCastTo method
ms.assetid: a8e85c7d-4dcd-446d-bebc-a97da46ce44a
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
ms.openlocfilehash: 8d45dbe80cc2e33d78c4ec60b8ae57d809b0ae17

---
# Implements::CanCastTo Method
Gets a pointer to the specified interface.  
  
## Syntax  
  
```  
__forceinline HRESULT CanCastTo(  
   REFIID riid,  
   _Deref_out_ void **ppv  
);  
```  
  
#### Parameters  
 `riid`  
 A reference to an interface ID.  
  
 `ppv`  
 If successful, a pointer to the interface specified by `riid`.  
  
## Return Value  
 S_OK if successful; otherwise, an HRESULT that indicates the error, such as E_NOINTERFACE.  
  
## Remarks  
 This is an internal helper function that performs a QueryInterface operation.  
  
## Requirements  
 **Header:** implements.h  
  
 **Namespace:** Microsoft::WRL  
  
## See Also  
 [Implements Structure](../windows/implements-structure.md)


<!--HONumber=Jan17_HO2-->


