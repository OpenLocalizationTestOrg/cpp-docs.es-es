---
title: ComPtr::CopyTo Method | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: reference
f1_keywords:
- client/Microsoft::WRL::ComPtr::CopyTo
dev_langs:
- C++
helpviewer_keywords:
- CopyTo method
ms.assetid: 8801bc49-6db4-4393-a55f-a701ae3b8718
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
ms.openlocfilehash: d9e50e9961a98a30d03ce446a5bfc91e75a097c0

---
# ComPtr::CopyTo Method
Copies the current or specified interface associated with this ComPtr to the specified pointer.  
  
## Syntax  
  
```  
HRESULT CopyTo(  
   _Deref_out_ InterfaceType** ptr  
);  
  
HRESULT CopyTo(  
   REFIID riid,  
   _Deref_out_ void** ptr  
) const;  
template<  
   typename U  
>  
  
HRESULT CopyTo(  
   _Deref_out_ U** ptr  
) const;  
```  
  
#### Parameters  
 `U`  
 A type name.  
  
 `ptr`  
 When this operation completes, a pointer to the requested interface.  
  
 `riid`  
 An interface ID.  
  
## Return Value  
 S_OK if successful; otherwise, an HRESULT that indicates why the implicit QueryInterface operation failed.  
  
## Remarks  
 The first function returns a copy of a pointer to the interface associated with this ComPtr. This function always returns S_OK.  
  
 The second function performs a QueryInterface operation on the interface associated with this ComPtr for the interface specified by the `riid` parameter.  
  
 The third function performs a QueryInterface operation on the interface associated with this ComPtr for the underlying interface of the  `U` parameter.  
  
## Requirements  
 **Header:** client.h  
  
 **Namespace:** Microsoft::WRL  
  
## See Also  
 [ComPtr Class](../windows/comptr-class.md)


<!--HONumber=Jan17_HO2-->


