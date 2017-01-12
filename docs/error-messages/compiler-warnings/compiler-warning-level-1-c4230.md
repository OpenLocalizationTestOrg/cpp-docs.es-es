---
title: Compiler Warning (level 1) C4230 | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: error-reference
f1_keywords:
- C4230
dev_langs:
- C++
helpviewer_keywords:
- C4230
ms.assetid: a4be8729-74b6-44df-a5ea-e3f45aad0f8f
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
ms.openlocfilehash: 7ff7145a5d8f96c4173bc292e356ae9fd6a91e53

---
# Compiler Warning (level 1) C4230
anachronism used : modifiers/qualifiers interspersed; qualifier ignored  
  
 Using a qualifier before a Microsoft modifier such as `__cdecl` is an outdated practice.  
  
## Example  
  
```  
// C4230.cpp  
// compile with: /W1 /LD  
int __cdecl const function1();   // C4230 const ignored  
```


<!--HONumber=Jan17_HO2-->


