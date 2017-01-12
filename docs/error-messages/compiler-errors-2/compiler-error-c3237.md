---
title: Compiler Error C3237 | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-csharp
ms.tgt_pltfrm: 
ms.topic: article
f1_keywords:
- C3237
dev_langs:
- C++
helpviewer_keywords:
- C3237
ms.assetid: 690970c8-e13b-4ff3-96e3-5fd93c4d356b
caps.latest.revision: 10
author: corob-msft
ms.author: corob
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
ms.openlocfilehash: 815ec110664bab1c5a1a1672a6333c881c06435d

---
# Compiler Error C3237
'generic_class' : a generic class cannot be a custom attribute  
  
 Generic classes cannot be user-defined attributes.  
  
## Example  
 The following sample generates C3237.  
  
```  
// C3237.cpp  
// compile with: /clr /c  
// C3237 expected  
using namespace System;  
  
generic <class T>  
// Delete the following line to resolve.  
[attribute(AttributeTargets::All, AllowMultiple=true)]  
public ref class GR {};  
```


<!--HONumber=Jan17_HO2-->


