---
title: CDynamicAccessor::Close | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: article
f1_keywords:
- ATL::CDynamicAccessor::Close
- ATL.CDynamicAccessor.Close
- CDynamicAccessor.Close
- CDynamicAccessor::Close
dev_langs:
- C++
helpviewer_keywords:
- Close method
ms.assetid: 2a28ded2-d7ed-4e80-90bf-143133c93feb
caps.latest.revision: 8
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
ms.openlocfilehash: 811e7eb167d2a8a63a235e192faf4103cfe98d97

---
# CDynamicAccessor::Close
Unbinds all the columns, releases the allocated memory, and releases the [IAccessor](https://msdn.microsoft.com/en-us/library/ms719672.aspx) interface pointer in the class.  
  
## Syntax  
  
```  
  
void Close( ) throw( );  
  
```  
  
## Requirements  
 **Header:** atldbcli.h  
  
## See Also  
 [CDynamicAccessor Class](../../data/oledb/cdynamicaccessor-class.md)


<!--HONumber=Jan17_HO2-->


