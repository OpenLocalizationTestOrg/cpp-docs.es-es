---
title: typeof Goes to T::typeid | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: article
dev_langs:
- C++
helpviewer_keywords:
- typeid operator
- __typeof keyword
- typeid keyword [C++]
ms.assetid: 6a0d35a7-7a1a-4070-b187-cff37cfdc205
caps.latest.revision: 8
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
ms.openlocfilehash: 18d403003a183108289a2e7a73f64bc293b9fc53

---
# typeof Goes to T::typeid
The `typeof` operator used in Managed Extensions for C++ has been supplanted by the `typeid` keyword in [!INCLUDE[cpp_current_long](../dotnet/includes/cpp_current_long_md.md)].  
  
 In Managed Extensions, the `__typeof()` operator returns the associated `Type*` object when passed the name of a managed type. For example:  
  
```  
// Creates and initializes a new Array instance.  
Array* myIntArray =   
   Array::CreateInstance( __typeof(Int32), 5 );  
```  
  
 In the new syntax, `__typeof` has been replaced by an additional form of `typeid` that returns a `Type^` when a managed type is specified.  
  
```  
// Creates and initializes a new Array instance.  
Array^ myIntArray =   
   Array::CreateInstance( Int32::typeid, 5 );  
```  
  
## See Also  
 [General Language Changes (C++/CLI)](../dotnet/general-language-changes-cpp-cli.md)   
 [typeid](../windows/typeid-cpp-component-extensions.md)


<!--HONumber=Jan17_HO2-->


