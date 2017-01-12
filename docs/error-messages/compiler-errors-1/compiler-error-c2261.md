---
title: Compiler Error C2261 | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: error-reference
f1_keywords:
- C2261
dev_langs:
- C++
helpviewer_keywords:
- C2261
ms.assetid: 60969482-9e83-49b5-9631-a04bc844da12
caps.latest.revision: 9
author: corob-msft
ms.author: corob
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
ms.openlocfilehash: 6e3f6dc3ae3c603a090e37451f0bb09f6eece6fd

---
# Compiler Error C2261
'string' : assembly reference is invalid and cannot be resolved  
  
 A value was not valid.  
  
 <xref:System.Runtime.CompilerServices.InternalsVisibleToAttribute> is used to specify a friend assembly. For example, if a.dll wants to specify b.dll as a friend assembly, you would specify (in a.dll): InternalsVisibleTo("b"). The runtime then allows b.dll to access everything in a.dll (except private types).  
  
 For more on the correct syntax when specifying friend assemblies, see [Friend Assemblies (C++)](../../dotnet/friend-assemblies-cpp.md).  
  
## Example  
 The following sample generates C2261.  
  
```  
// C2261.cpp  
// compile with: /clr /c  
using namespace System::Runtime::CompilerServices;  
[assembly: InternalsVisibleTo("a,a,a")];   // C2261  
[assembly: InternalsVisibleTo("a.a")];   // OK  
[assembly: InternalsVisibleTo("a")];   // OK  
```


<!--HONumber=Jan17_HO2-->


