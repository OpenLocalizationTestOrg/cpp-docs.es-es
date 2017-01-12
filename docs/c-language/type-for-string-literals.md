---
title: Type for String Literals | Microsoft Docs
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
- C
helpviewer_keywords:
- string literals, type
- types [C], string literals
ms.assetid: f50a28af-20c1-4440-bdc6-564c86a309c8
caps.latest.revision: 7
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
ms.openlocfilehash: 99e8a59ac8235df8e0ba6df3adad54f62a7eaedf

---
# Type for String Literals
String literals have type array of `char` (that is, **char[ ]**). (Wide-character strings have type array of `wchar_t` (that is, **wchar_t[ ]**).) This means that a string is an array with elements of type `char`. The number of elements in the array is equal to the number of characters in the string plus one for the terminating null character.  
  
## See Also  
 [C String Literals](../c-language/c-string-literals.md)


<!--HONumber=Jan17_HO2-->


