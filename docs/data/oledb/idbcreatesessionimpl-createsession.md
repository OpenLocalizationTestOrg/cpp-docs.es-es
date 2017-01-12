---
title: IDBCreateSessionImpl::CreateSession | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: article
f1_keywords:
- IDBCreateSessionImpl::CreateSession
- IDBCreateSessionImpl.CreateSession
- CreateSession
dev_langs:
- C++
helpviewer_keywords:
- CreateSession method
ms.assetid: 035e5ddb-56e6-43b1-874d-89c0e40b103b
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
ms.openlocfilehash: 2ea485ed605529647b6b396b57881ca1eb3122b9

---
# IDBCreateSessionImpl::CreateSession
Creates a new session from the data source object and returns the requested interface on the newly created session.  
  
## Syntax  
  
```  
  
      STDMETHOD(CreateSession)(   
   IUnknown * pUnkOuter,   
   REFIID riid,   
   IUnknown ** ppDBSession    
);  
```  
  
#### Parameters  
 See [IDBCreateSession::CreateSession](https://msdn.microsoft.com/en-us/library/ms714942.aspx) in the *OLE DB Programmer's Reference*.  
  
## Requirements  
 **Header:** atldb.h  
  
## See Also  
 [IDBCreateSessionImpl Class](../../data/oledb/idbcreatesessionimpl-class.md)


<!--HONumber=Jan17_HO2-->


