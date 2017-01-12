---
title: o_smart_pointers | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: article
f1_keywords:
- no_search_pointers
dev_langs:
- C++
- C
helpviewer_keywords:
- no_smart_pointers attribute
ms.assetid: d69dd71e-08a8-4446-a3d0-a062dc29cb17
caps.latest.revision: 5
author: corob-msft
ms.author: corob
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
ms.openlocfilehash: 06fc1f38468a219320c6dff2f40d145cee6fed41

---
# no_smart_pointers
**C++ Specific**  
  
 Suppresses the creation of smart pointers for all interfaces in the type library.  
  
## Syntax  
  
```  
no_smart_pointers  
```  
  
## Remarks  
 By default, when you use `#import`, you get a smart pointer declaration for all interfaces in the type library. These smart pointers are of type [_com_ptr_t Class](../cpp/com-ptr-t-class.md).  
  
 **END C++ Specific**  
  
## See Also  
 [#import Attributes](../preprocessor/hash-import-attributes-cpp.md)   
 [#import Directive](../preprocessor/hash-import-directive-cpp.md)


<!--HONumber=Jan17_HO2-->


