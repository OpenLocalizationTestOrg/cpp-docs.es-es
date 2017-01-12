---
title: IRowsetInfoImpl::GetSpecification | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: article
f1_keywords:
- IRowsetInfoImpl::GetSpecification
- ATL.IRowsetInfoImpl.GetSpecification
- IRowsetInfoImpl.GetSpecification
- GetSpecification
- ATL::IRowsetInfoImpl::GetSpecification
dev_langs:
- C++
helpviewer_keywords:
- GetSpecification method
ms.assetid: 8e14289d-9cca-4df7-a9e0-f4ef03c61e30
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
ms.openlocfilehash: ed4948ccb635d48dd41e112c7598221088c239c2

---
# IRowsetInfoImpl::GetSpecification
Returns an interface pointer on the object (command or session) that created this rowset.  
  
## Syntax  
  
```  
  
      STDMETHOD ( GetSpecification )(  
   REFIID riid,  
   IUnknown** ppSpecification   
);  
```  
  
#### Parameters  
 See [IRowsetInfo::GetSpecification](https://msdn.microsoft.com/en-us/library/ms716746.aspx) in the *OLE DB Programmer's Reference*.  
  
## Remarks  
 Use this method with [IGetDataSourceImpl](../../data/oledb/igetdatasourceimpl-class.md) to retrieve properties from the data source object.  
  
## Requirements  
 **Header:** atldb.h  
  
## See Also  
 [IRowsetInfoImpl Class](../../data/oledb/irowsetinfoimpl-class.md)   
 [IRowsetInfoImpl::GetReferencedRowset](../../data/oledb/irowsetinfoimpl-getreferencedrowset.md)   
 [IRowsetInfoImpl::GetProperties](../../data/oledb/irowsetinfoimpl-getproperties.md)


<!--HONumber=Jan17_HO2-->


