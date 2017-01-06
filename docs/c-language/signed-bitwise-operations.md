---
title: Signed Bitwise Operations | Microsoft Docs
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
- bitwise operations
- signed bitwise operations
ms.assetid: 1e5cf65b-ee32-41a0-a5c2-82c1854091f6
caps.latest.revision: 6
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
ms.openlocfilehash: 78b83e99a1827abf6bd8be0364fb4e1e78f5be0a

---
# Signed Bitwise Operations
**ANSI 3.3** The results of bitwise operations on signed integers  
  
 Bitwise operations on signed integers work the same as bitwise operations on unsigned integers. For example, `–16 & 99` can be expressed in binary as  
  
```  
  11111111 11110000  
& 00000000 01100011  
  _________________  
  00000000 01100000  
```  
  
 The result of the bitwise AND is 96.  
  
## See Also  
 [Integers](../c-language/integers.md)


<!--HONumber=Jan17_HO1-->


