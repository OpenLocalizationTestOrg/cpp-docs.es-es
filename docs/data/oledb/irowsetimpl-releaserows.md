---
title: IRowsetImpl::ReleaseRows | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: article
f1_keywords:
- ATL.IRowsetImpl.ReleaseRows
- ReleaseRows
- IRowsetImpl::ReleaseRows
- ATL::IRowsetImpl::ReleaseRows
- IRowsetImpl.ReleaseRows
dev_langs:
- C++
helpviewer_keywords:
- ReleaseRows method
ms.assetid: e4d47be8-8ebf-485b-b1e9-df13e4c8ee8d
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
ms.openlocfilehash: 31b1e2095381f517cbd83977ac0c2f8cbe770de7

---
# IRowsetImpl::ReleaseRows
Releases rows.  
  
## Syntax  
  
```  
  
      STDMETHOD( ReleaseRows )(  
   DBCOUNTITEM cRows,  
   const HROW rghRows[],  
   DBROWOPTIONS rgRowOptions[],  
   DBREFCOUNT rgRefCounts[],  
   DBROWSTATUS rgRowStatus[]   
);  
```  
  
#### Parameters  
 See [IRowset::ReleaseRows](https://msdn.microsoft.com/en-us/library/ms719771.aspx) in the *OLE DB Programmer's Reference*.  
  
## Requirements  
 **Header:** atldb.h  
  
## See Also  
 [IRowsetImpl Class](../../data/oledb/irowsetimpl-class.md)   
 [IRowsetImpl::AddRefRows](../../data/oledb/irowsetimpl-addrefrows.md)   
 [IRowsetImpl::RefRows](../../data/oledb/irowsetimpl-refrows.md)


<!--HONumber=Jan17_HO2-->


