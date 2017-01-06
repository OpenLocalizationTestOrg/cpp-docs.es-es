---
title: Compiler Error C2588 | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: error-reference
f1_keywords:
- C2588
dev_langs:
- C++
helpviewer_keywords:
- C2588
ms.assetid: 19a0cabd-ca13-44a5-9be3-ee676abf9bc4
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
ms.openlocfilehash: fb584343099adf3edb8463bfac75a0d1a5ab2943

---
# Compiler Error C2588
'::~identifier' : illegal global destructor  
  
 The destructor is defined for something other than a class, structure, or union. This is not allowed.  
  
 This error can be caused by a missing class, structure, or union name on the left side of the scope resolution (`::`) operator.  
  
 The following sample generates C2588:  
  
```  
// C2588.cpp  
~F();   // C2588  
```


<!--HONumber=Jan17_HO1-->


