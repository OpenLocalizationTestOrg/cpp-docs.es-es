---
title: __func__ | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: language-reference
f1_keywords:
- __func__
- __func___cpp
dev_langs:
- C++
ms.assetid: a5299b8d-f0ee-4af2-91dd-8fb165e68798
caps.latest.revision: 3
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
ms.sourcegitcommit: 5187996fc377bca8633360082d07f7ec8a68ee57
ms.openlocfilehash: ebb8097abda11fe52374177d6e77d34c277d08bb

---
# __func__
**(C++11)** The predefined identifier __func\_\_ is implicitly defined as a string that contains the unqualified and unadorned name of the enclosing function. \__func\_\_ is mandated by the C++ standard and is not a Microsoft extension.  
  
## Syntax  
  
```cpp  
__func__  
```  
  
## Return Value  
 Returns a null-terminated const char array of characters that constains the function name.  
  
## Example  
  
```  
  
#include <string>  
#include <iostream>  
  
namespace Test  
{  
    struct Foo  
    {  
        static void DoSomething(int i, std::string s)  
        {  
           std::cout << __func__ << std::endl; // Output: DoSomething  
        }  
    };  
}  
int main()  
{  
    Test::Foo::DoSomething(42, "Hello");  
  
    return 0;  
}  
  
```  
  
## Requirements  
 C++11


<!--HONumber=Jan17_HO2-->


