---
title: Compiler Error C2097 | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: error-reference
f1_keywords:
- C2097
dev_langs:
- C++
helpviewer_keywords:
- C2097
ms.assetid: 7e5b2fd4-f61c-4b8a-b265-93e987a04bd3
caps.latest.revision: 6
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
ms.openlocfilehash: 0f983b1e5786ed820874209984fa3d4dc3760dbf

---
# Compiler Error C2097
illegal initialization  
  
### To fix by checking the following possible causes  
  
1.  Initialization of a variable using a nonconstant value.  
  
2.  Initialization of a short address with a long address.  
  
3.  Initialization of a local structure, union, or array with a nonconstant expression when compiling with **/Za**.  
  
4.  Initialization with an expression containing a comma operator.  
  
5.  Initialization with an expression that is neither constant nor symbolic.


<!--HONumber=Jan17_HO2-->


