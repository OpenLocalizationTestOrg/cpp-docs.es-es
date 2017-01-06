---
title: Reading Ranges | Microsoft Docs
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
ms.assetid: 99de29ce-ab14-46f4-97e1-2081fd996b53
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
ms.openlocfilehash: 818c5535e7f7fb92fda1f97691a03578f4cd4e83

---
# Reading Ranges
**ANSI 4.9.6.2** The interpretation of a dash (–) character that is neither the first nor the last character in the scanlist for % [ conversion in the `fscanf` function  
  
 The following line  
  
```  
fscanf( fileptr, "%[A-Z]", strptr);  
```  
  
 reads any number of characters in the range A–Z into the string to which `strptr` points.  
  
## See Also  
 [Library Functions](../c-language/library-functions.md)


<!--HONumber=Jan17_HO1-->


