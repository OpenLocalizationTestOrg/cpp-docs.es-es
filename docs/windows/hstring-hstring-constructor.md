---
title: HString::HString Constructor | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: reference
f1_keywords:
- corewrappers/Microsoft::WRL::Wrappers::HString::HString
dev_langs:
- C++
ms.assetid: 6da12785-ed01-4720-a004-667db60298f1
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
ms.openlocfilehash: cf65de539a2907c49538594fd23e3860b6df4c94

---
# HString::HString Constructor
Initializes a new instance of the HString class.  
  
## Syntax  
  
```cpp  
  
HString(HSTRING hstr = nullptr) throw();  
HString(HString&& other) throw();  
```  
  
#### Parameters  
 `hstr`  
 An HSTRING handle.  
  
 `other`  
 An existing HString object.  
  
## Remarks  
 The first constructor initializes a new HString object that is empty.  
  
 The second constructor initializes a new HString object to the value of the existing `other` parameter, and then destroys the `other` parameter.  
  
## Requirements  
 **Header:** corewrappers.h  
  
 **Namespace:** Microsoft::WRL::Wrappers  
  
## See Also  
 [HString Class](../windows/hstring-class.md)


<!--HONumber=Jan17_HO2-->


