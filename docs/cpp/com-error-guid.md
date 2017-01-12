---
title: _com_error::GUID | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: language-reference
f1_keywords:
- GUID
- _com_error.GUID
- _com_error::GUID
dev_langs:
- C++
helpviewer_keywords:
- GUID method
ms.assetid: e84c2c23-d02e-48f8-b776-9bd6937296d2
caps.latest.revision: 6
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
ms.openlocfilehash: e10f49ecf43322dad93a03b524a3d8b664514475

---
# _com_error::GUID
**Microsoft Specific**  
  
 Calls **IErrorInfo::GetGUID** function.  
  
## Syntax  
  
```  
  
GUID GUID( ) const throw( );  
  
```  
  
## Return Value  
 Returns the result of **IErrorInfo::GetGUID** for the **IErrorInfo** object recorded within the `_com_error` object. If no **IErrorInfo** object is recorded, it returns `GUID_NULL`.  
  
## Remarks  
 Any failure while calling the **IErrorInfo::GetGUID** method is ignored.  
  
 **END Microsoft Specific**  
  
## See Also  
 [_com_error Class](../cpp/com-error-class.md)


<!--HONumber=Jan17_HO2-->


