---
title: FtmBase::CreateGlobalInterfaceTable Method | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: reference
f1_keywords:
- ftm/Microsoft::WRL::FtmBase::CreateGlobalInterfaceTable
dev_langs:
- C++
helpviewer_keywords:
- CreateGlobalInterfaceTable method
ms.assetid: bb82a0c5-22b9-4844-9204-7922033d8b07
caps.latest.revision: 3
author: mikeblome
ms.author: mblome
manager: ghogen
translation.priority.ht:
- de-de
- es-es
- fr-fr
- it-it
- ja-jp
- ko-kr
- ru-ru
- zh-cn
- zh-tw
translation.priority.mt:
- cs-cz
- pl-pl
- pt-br
- tr-tr
translationtype: Human Translation
ms.sourcegitcommit: 3168772cbb7e8127523bc2fc2da5cc9b4f59beb8
ms.openlocfilehash: 34489c0a93de574c38b2a172b3d8cfa4ffa5faac

---
# FtmBase::CreateGlobalInterfaceTable Method
Creates a global interface table (GIT).  
  
## Syntax  
  
```  
static HRESULT CreateGlobalInterfaceTable(  
   __out IGlobalInterfaceTable **git  
);  
```  
  
#### Parameters  
 `git`  
 When this operation completes, a pointer to a global interface table.  
  
## Return Value  
 S_OK if successful; otherwise, an HRESULT that indicates the error.  
  
## Remarks  
 For more information, see the "IGlobalInterfaceTable" topic in the "COM Interfaces" subtopic of the "COM Reference" topic in the MSDN Library.  
  
## Requirements  
 **Header:** ftm.h  
  
 **Namespace:** Microsoft::WRL  
  
## See Also  
 [FtmBase Class](../windows/ftmbase-class.md)


<!--HONumber=Jan17_HO2-->


