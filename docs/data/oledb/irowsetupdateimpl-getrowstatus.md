---
title: IRowsetUpdateImpl::GetRowStatus | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: article
f1_keywords:
- ATL.IRowsetUpdateImpl.GetRowStatus
- IRowsetUpdateImpl::GetRowStatus
- IRowsetUpdateImpl.GetRowStatus
- ATL::IRowsetUpdateImpl::GetRowStatus
- GetRowStatus
dev_langs:
- C++
helpviewer_keywords:
- GetRowStatus method
ms.assetid: ce57e8be-5891-44d9-b3c5-59ffd3913678
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
ms.openlocfilehash: e1c67c9b9ac9cdba5ffe9a11410425375f50af3f

---
# IRowsetUpdateImpl::GetRowStatus
Returns the status of specified rows.  
  
## Syntax  
  
```  
  
      STDMETHOD ( GetRowStatus )(  
   HCHAPTER /* hReserved */,  
   DBCOUNTITEM cRows,  
   const HROW rghRows[],  
   DBPENDINGSTATUS rgPendingStatus[]   
);  
```  
  
#### Parameters  
 `hReserved`  
 [in] Corresponds to the `hChapter` parameter in [IRowsetUpdate::GetRowStatus](https://msdn.microsoft.com/en-us/library/ms724377.aspx).  
  
 For other parameters, see [IRowsetUpdate::GetRowStatus](https://msdn.microsoft.com/en-us/library/ms724377.aspx) in the *OLE DB Programmer's Reference*.  
  
## Requirements  
 **Header:** atldb.h  
  
## See Also  
 [IRowsetUpdateImpl Class](../../data/oledb/irowsetupdateimpl-class.md)


<!--HONumber=Jan17_HO2-->


