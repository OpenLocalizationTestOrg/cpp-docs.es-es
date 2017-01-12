---
title: IErrorRecordsImpl::GetErrorHelpFile | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: article
f1_keywords:
- IErrorRecordsImpl::GetErrorHelpFile
- GetErrorHelpFile
- IErrorRecordsImpl.GetErrorHelpFile
dev_langs:
- C++
helpviewer_keywords:
- GetErrorHelpFile method
ms.assetid: ad198f76-5bdf-4b8d-9f1a-3d38f72f31ad
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
ms.openlocfilehash: 496e4961c730fbd212ddd2d3097773d7c17d723f

---
# IErrorRecordsImpl::GetErrorHelpFile
Gets the path name of the help file from an error record.  
  
## Syntax  
  
```  
  
      LPOLESTR GetErrorHelpFile(  
   ERRORINFO& rCurError   
);  
```  
  
#### Parameters  
 `rCurError`  
 An `ERRORINFO` record in an **IErrorInfo** interface.  
  
## Return Value  
 Pointer to a string that contains the path name of the help file for the error.  
  
## Requirements  
 **Header:** atldb.h  
  
## See Also  
 [IErrorRecordsImpl Class](../../data/oledb/ierrorrecordsimpl-class.md)


<!--HONumber=Jan17_HO2-->


