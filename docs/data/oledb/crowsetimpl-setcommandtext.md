---
title: CRowsetImpl::SetCommandText | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: article
f1_keywords:
- CRowsetImpl.SetCommandText
- CRowsetImpl::SetCommandText
dev_langs:
- C++
helpviewer_keywords:
- SetCommandText method
ms.assetid: e016d7df-c1a0-4dee-b19b-c876680221fd
caps.latest.revision: 9
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
ms.openlocfilehash: 997f49901ea632e7161a4a69cc674d2d981639b9

---
# CRowsetImpl::SetCommandText
Validates and stores the **DBID**s in the two strings ([m_strCommandText](../../data/oledb/crowsetimpl-m-strcommandtext.md) and [m_strIndexText](../../data/oledb/crowsetimpl-m-strindextext.md)).  
  
## Syntax  
  
```  
  
      HRESULT CRowsetBaseImpl::SetCommandText(  
   DBID* pTableID,  
   DBID* pIndexID   
);  
```  
  
#### Parameters  
 `pTableID`  
 [in] A pointer to the **DBID** representing the table ID.  
  
 `pIndexID`  
 [in] A pointer to the **DBID** representing the index ID.  
  
## Return Value  
 A standard `HRESULT`.  
  
## Remarks  
 The **SetCommentText** method is called by `CreateRowset`, a static templatized method of `IOpenRowsetImpl`.  
  
 This method delegates its work by calling [ValidateCommandID](../../data/oledb/crowsetimpl-validatecommandid.md) and [GetCommandFromID](../../data/oledb/crowsetimpl-getcommandfromid.md) through an upcasted pointer.  
  
## Requirements  
 **Header:** atldb.h  
  
## See Also  
 [CRowsetImpl Class](../../data/oledb/crowsetimpl-class.md)


<!--HONumber=Jan17_HO2-->


