---
title: Compiler Error C2389 | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-csharp
ms.tgt_pltfrm: 
ms.topic: article
f1_keywords:
- C2389
dev_langs:
- C++
helpviewer_keywords:
- C2389
ms.assetid: 6122dc81-4ee3-49a5-a67d-d867808c9bac
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
ms.openlocfilehash: 2df952e6bd21beaffa6f457d54ad07ce526893a8

---
# Compiler Error C2389
'operator' : illegal operand 'nullptr'  
  
 `nullptr` cannot be an operand.  
  
 The following sample generates C2389:  
  
```  
// C2389.cpp  
// compile with: /clr  
int main() {  
   throw nullptr;   // C2389  
}  
```


<!--HONumber=Jan17_HO2-->


