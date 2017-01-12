---
title: CBulkRowset::ReleaseRows | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: article
f1_keywords:
- ReleaseRows
- ATL.CBulkRowset<TAccessor>.ReleaseRows
- ATL::CBulkRowset<TAccessor>::ReleaseRows
- ATL.CBulkRowset.ReleaseRows
- CBulkRowset<TAccessor>::ReleaseRows
- ATL::CBulkRowset::ReleaseRows
- CBulkRowset::ReleaseRows
- CBulkRowset.ReleaseRows
dev_langs:
- C++
helpviewer_keywords:
- ReleaseRows method
ms.assetid: ba48aff3-0887-47ba-aed7-7ff28fa1c4a8
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
ms.openlocfilehash: 2f3a1c5797e7780646bb7abebb5713218444f53c

---
# CBulkRowset::ReleaseRows
Calls [IRowset::ReleaseRows](https://msdn.microsoft.com/en-us/library/ms719771.aspx) to decrement the reference count for all rows currently retrieved from the bulk rowset.  
  
## Syntax  
  
```  
  
HRESULT ReleaseRows( ) throw( );  
  
```  
  
## Return Value  
 A standard `HRESULT`.  
  
## Requirements  
 **Header:** atldbcli.h  
  
## See Also  
 [CBulkRowset Class](../../data/oledb/cbulkrowset-class.md)   
 [CBulkRowset::AddRefRows](../../data/oledb/cbulkrowset-addrefrows.md)


<!--HONumber=Jan17_HO2-->


