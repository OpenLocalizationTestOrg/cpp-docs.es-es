---
title: adjacent_difference (STL-CLR) | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: reference
f1_keywords:
- cliext::adjacent_difference
dev_langs:
- C++
helpviewer_keywords:
- adjacent_difference function
ms.assetid: 2b462e2e-b8f2-4b2e-9b87-5f688d8da9f4
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
ms.sourcegitcommit: 765f73bea7d87c5b6027f98370a4772192b44618
ms.openlocfilehash: d287ddb26dd3554ed774b09c596dbaa07bbac632

---
# adjacent_difference (STL/CLR)
Computes the successive differences between each element and its predecessor in an input range and outputs the results to a destination range or computes the result of a generalized procedure where the difference operation is replaced by another, specified binary operation.  
  
## Syntax  
  
```  
template<class _InIt, class _OutIt> inline  
    _OutIt adjacent_difference(_InIt _First, _InIt _Last,  
        _OutIt _Dest);  
template<class _InIt, class _OutIt, class _Fn2> inline  
    _OutIt adjacent_difference(_InIt _First, _InIt _Last,  
        _OutIt _Dest, _Fn2 _Func);  
```  
  
## Remarks  
 This function behaves the same as the STL numeric function `adjacent_difference`. For more information, see [adjacent_difference](../standard-library/numeric-functions.md#adjacent_difference).  
  
## Requirements  
 **Header:** \<cliext/numeric>  
  
 **Namespace:** cliext  
  
## See Also  
 [numeric (STL/CLR)](../dotnet/numeric-stl-clr.md)


<!--HONumber=Jan17_HO2-->


