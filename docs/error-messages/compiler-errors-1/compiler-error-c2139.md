---
title: Compiler Error C2139 | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: error-reference
f1_keywords:
- C2139
dev_langs:
- C++
helpviewer_keywords:
- C2139
ms.assetid: 31e047c0-5bf9-46c2-b6de-b627ea6a5768
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
ms.openlocfilehash: c6ca3ee058eb5eea42407b9e5f7900b65671b8a0

---
# Compiler Error C2139
'type' : an undefined class is not allowed as an argument to compiler intrinsic type trait 'trait'  
  
 An invalid argument was passed to a type trait.  
  
 For more information, see [Compiler Support for Type Traits](../../windows/compiler-support-for-type-traits-cpp-component-extensions.md).  
  
## Example  
 The following sample generates C2139.  
  
```  
// C2139.cpp  
// compile with: /EHsc  
#include <iostream>  
using namespace std;  
  
template <class T>  
struct is_polymorphic {  
   static const bool value = __is_polymorphic(T);  
};  
  
class C;  
class D {};  
  
class E {  
public:  
   virtual void Test() {}  
};  
  
int main() {  
   cout << is_polymorphic<C>::value << endl;   // C2139  
   cout << is_polymorphic<D>::value << endl;   // OK  
   cout << is_polymorphic<E>::value << endl;   // OK  
}  
```


<!--HONumber=Jan17_HO2-->


