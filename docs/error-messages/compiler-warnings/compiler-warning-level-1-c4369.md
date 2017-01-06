---
title: Compiler Warning (level 1) C4369 | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: error-reference
f1_keywords:
- C4369
dev_langs:
- C++
helpviewer_keywords:
- C4369
ms.assetid: ade87e84-36be-4e00-be99-2930af848feb
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
ms.openlocfilehash: c7ceb295d8f79634b022e5ef8dd4a3e4229b397f

---
# Compiler Warning (level 1) C4369
'enumerator' :  enumerator value 'value' cannot be represented as 'type', value is 'new_value'  
  
 An enumerator was calculated to be greater than the greatest value for the specified underlying type.  This caused an overflow and the compiler wrapped the enumerator value to the lowest possible value for the type.  
  
## Example  
 The following sample generates C4369.  
  
```  
// C4369.cpp  
// compile with: /W1  
int main() {  
   enum Color: char { red = 0x7e, green, blue };   // C4369  
   enum Color2: char { red2 = 0x7d, green2, blue2};   // OK  
}  
```


<!--HONumber=Jan17_HO1-->


