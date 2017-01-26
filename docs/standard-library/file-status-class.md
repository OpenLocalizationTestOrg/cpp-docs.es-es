---
title: file_status Class | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: article
f1_keywords:
- filesystem/std::experimental::filesystemfile_status
- filesystem/std::experimental::filesystemfile_status::perms
- filesystem/std::experimental::filesystemfile_status::type
dev_langs:
- C++
ms.assetid: 9781840e-ad22-44dd-ad79-0fabaa94bac4
caps.latest.revision: 15
author: corob-msft
ms.author: corob
manager: ghogen
translation.priority.mt:
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
translationtype: Machine Translation
ms.sourcegitcommit: 85c900f2263ae1c1089478badc85388e3b5e8548
ms.openlocfilehash: b6418446418b16233cea45440510cafb372dc2fd

---
# <a name="filestatus-class"></a>file_status Class
Wraps a [file_type](../standard-library/filesystem-enumerations.md#filesystem__file_type) and file [perms](../standard-library/filesystem-enumerations.md#filesystem__perms).  
  
## <a name="syntax"></a>Syntax  
  
```cpp  
class file_status;  
```  
  
## <a name="filestatusfilestatus"></a>file_status::file_status  
  
```cpp  
explicit file_status(file_type ftype = file_type::none, perms mask = perms::unknown) noexcept;
file_status(const file_status&) noexcept = default;
file_status(file_status&&) noexcept = default;  
```  
  
## <a name="filestatusoperator"></a>file_status::operator=  
  
```cpp  
file_status& operator=(const file_status&) noexcept = default;  
file_status& operator=(file_status&&) nexcept = default;  
```  
  
 The defaulted member assignment operators behave as expected.  
  
## <a name="type"></a>type  
  
```cpp  
file_type type() const noexcept  
void type(file_type _Ftype) noexcept  
```  
  
 Gets or sets the file_type.  
  
## <a name="permissions"></a>permissions  
  
``cpp  
perms permissions() const noexcept  
void permissions(perms_Prms) noexcept   
```  
  
 Gets or sets the file permissions.  
  
 Use the setter to make a file readonly or remove the readonly attribute.  
  
## Requirements  
 **Header:** filesystem  
  
 **Namespace:** std::experimental::filesystem  
  
## See Also  
 [Header Files Reference](../standard-library/cpp-standard-library-header-files.md)   
 [path Class](../standard-library/path-class.md)   
 [\<filesystem>](../standard-library/filesystem.md)




<!--HONumber=Jan17_HO4-->


