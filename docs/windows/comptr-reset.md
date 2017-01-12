---
title: ComPtr::Reset | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: reference
dev_langs:
- C++
ms.assetid: aa6a46f7-f56b-4fd5-add0-7cea55f7abda
caps.latest.revision: 4
author: mikeblome
ms.author: mblome
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
ms.openlocfilehash: bdec7c80abe125ad086fa436fdcff6885a8dbe94

---
# ComPtr::Reset
Releases all references for the pointer to the interface that is associated with this ComPtr.  
  
## Syntax  
  
```  
unsigned long Reset();  
```  
  
## Return Value  
 The number of references released, if any.  
  
## Requirements  
 **Header:** client.h  
  
 **Namespace:** Microsoft::WRL  
  
## See Also  
 [ComPtr Class](../windows/comptr-class.md)


<!--HONumber=Jan17_HO2-->


