---
title: CDBPropSet::SetGUID | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: article
f1_keywords:
- ATL.CDBPropSet.SetGUID
- CDBPropSet.SetGUID
- ATL::CDBPropSet::SetGUID
- SetGUID
- CDBPropSet::SetGUID
dev_langs:
- C++
helpviewer_keywords:
- SetGUID method
- AddProperty method
ms.assetid: a4cce036-cf1f-4897-9712-7b01eaf887ff
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
ms.openlocfilehash: a59a281cb02504210d99c93f3019756375133174

---
# CDBPropSet::SetGUID
Sets the **guidPropertySet** field in the **DBPROPSET** structure.  
  
## Syntax  
  
```  
  
      void SetGUID(   
   const GUID& guid    
) throw( );  
```  
  
#### Parameters  
 `guid`  
 [in] A GUID used to set the **guidPropertySet** field of the [DBPROPSET](https://msdn.microsoft.com/en-us/library/ms714367.aspx) structure.  
  
## Remarks  
 This field can be set by the [constructor](../../data/oledb/cdbpropset-cdbpropset.md) as well.  
  
## Requirements  
 **Header:** atldbcli.h  
  
## See Also  
 [CDBPropSet Class](../../data/oledb/cdbpropset-class.md)


<!--HONumber=Jan17_HO2-->


