---
title: IDBCreateCommandImpl::CreateCommand | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: article
f1_keywords:
- IDBCreateCommandImpl.CreateCommand
- CreateCommand
- IDBCreateCommandImpl::CreateCommand
dev_langs:
- C++
helpviewer_keywords:
- CreateCommand method
ms.assetid: 50ffbf8b-2c07-4bcb-96c5-ffce4519c7f7
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
ms.openlocfilehash: 12218a140afc126e7feab78ddc5b88d10d7a1f92

---
# IDBCreateCommandImpl::CreateCommand
Creates a new command and returns the requested interface.  
  
## Syntax  
  
```  
  
      STDMETHOD(CreateCommand)(   
   IUnknown * pUnkOuter,   
   REFIID riid,   
   IUnknown ** ppvCommand    
);  
```  
  
#### Parameters  
 See [IDBCreateCommand::CreateCommand](https://msdn.microsoft.com/en-us/library/ms709772.aspx) in the *OLE DB Programmer's Reference*.  
  
 Some parameters correspond to *OLE DB Programmer's Reference* parameters of different names, which are described in **IDBCreateCommand::CreateCommand**:  
  
|OLE DB Template parameters|*OLE DB Programmer's Reference* parameters|  
|--------------------------------|------------------------------------------------|  
|*ppvCommand*|*ppCommand*|  
  
## Requirements  
 **Header:** atldb.h  
  
## See Also  
 [IDBCreateCommandImpl Class](../../data/oledb/idbcreatecommandimpl-class.md)


<!--HONumber=Jan17_HO2-->


