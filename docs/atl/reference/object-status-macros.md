---
title: Object Status Macros | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: reference
dev_langs:
- C++
ms.assetid: 727dbef2-a342-4157-9d64-a421805d9747
caps.latest.revision: 16
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
ms.sourcegitcommit: 5187996fc377bca8633360082d07f7ec8a68ee57
ms.openlocfilehash: fa3ab859e34fa0efda38570e66545955ccd3571a

---
# Object Status Macros
This macro sets flags belonging to ActiveX controls.  
  
|||  
|-|-|  
|[DECLARE_OLEMISC_STATUS](#declare_olemisc_status)|Used in ATL ActiveX controls to set the **OLEMISC** flags.|  
  
##  <a name="declare_olemisc_status"></a>  DECLARE_OLEMISC_STATUS  
 Used in ATL ActiveX controls to set the OLEMISC flags.  
  
```
DECLARE_OLEMISC_STATUS(Â
    miscstatus Â)
```  
  
### Parameters  
 *miscstatus*  
 All applicable OLEMISC flags.  
  
### Remarks  
 This macro is used to set the OLEMISC flags for an ActiveX control. Refer to [IOleObject::GetMiscStatus](http://msdn.microsoft.com/library/windows/desktop/ms678521) for more details.  
  
### Example  
 [!code-cpp[NVC_ATL_Windowing#124](../../atl/codesnippet/cpp/object-status-macros_1.h)]  
  
## See Also  
 [Macros](../../atl/reference/atl-macros.md)



<!--HONumber=Jan17_HO2-->


