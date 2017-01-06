---
title: '&lt;system_error&gt; functions | Microsoft Docs'
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.tgt_pltfrm: 
ms.topic: article
ms.assetid: 57d6f15f-f0b7-4e2f-80fe-31d3c320ee33
caps.latest.revision: 11
manager: ghogen
translationtype: Human Translation
ms.sourcegitcommit: 3168772cbb7e8127523bc2fc2da5cc9b4f59beb8
ms.openlocfilehash: 43098f6f9276c9a66aaa7a30c95a6696e33f8429

---
# &lt;system_error&gt; functions
||||  
|-|-|-|  
|[generic_category](#generic_category)|[make_error_code](#make_error_code)|[make_error_condition](#make_error_condition)|  
|[system_category](#system_category)|  
  
##  <a name="generic_category"></a>  generic_category  
 Represents the category for generic errors.  
  
```
extern const error_category& generic_category();
```  
  
### Remarks  
 The `generic_categor`y object is an implementation of [error_category](../standard-library/error-category-class.md).  
  
##  <a name="make_error_code"></a>  make_error_code  
 Creates an error code object.  
  
```
error_code make_error_code(generic_errno _Errno);
```  
  
### Parameters  
  
|Parameter|Description|  
|---------------|-----------------|  
|`_Errno`|The enumeration value to store in the error code object.|  
  
### Return Value  
 The error code object.  
  
### Remarks  
  
##  <a name="make_error_condition"></a>  make_error_condition  
 Creates an error condition object.  
  
```
error_condition make_error_condition(generic_errno _Errno);
```  
  
### Parameters  
  
|Parameter|Description|  
|---------------|-----------------|  
|`_Errno`|The enumeration value to store in the error condition object.|  
  
### Return Value  
 The error condition object.  
  
### Remarks  
  
##  <a name="system_category"></a>  system_category  
 Represents the category for errors caused by low-level system overflows.  
  
```
extern const error_category& system_category();
```  
  
### Remarks  
 The `system_categor`y object is an implementation of [error_category](../standard-library/error-category-class.md).  
  
## See Also  
 [<system_error>](../standard-library/system-error.md)






<!--HONumber=Jan17_HO1-->


