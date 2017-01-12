---
title: Compiler Error C2159 | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-csharp
ms.tgt_pltfrm: 
ms.topic: article
f1_keywords:
- C2159
dev_langs:
- C++
helpviewer_keywords:
- C2159
ms.assetid: 925a2cbd-43c9-45ee-a373-84004350b380
caps.latest.revision: 8
author: corob-msft
ms.author: corob
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
ms.openlocfilehash: 166a4295171190176ebbe30e5fab3bd4761ffd3b

---
# Compiler Error C2159
more than one storage class specified  
  
 A declaration contains more than one storage class.  
  
 The following sample generates C2159:  
  
```  
// C2159.cpp  
// compile with: /c  
static int i;   // OK  
extern static int i;   // C2159  
```


<!--HONumber=Jan17_HO2-->


