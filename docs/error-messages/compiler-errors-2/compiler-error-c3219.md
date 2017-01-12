---
title: Compiler Error C3219 | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-csharp
ms.tgt_pltfrm: 
ms.topic: article
f1_keywords:
- C3219
dev_langs:
- C++
helpviewer_keywords:
- C3219
ms.assetid: 9c9757b0-1256-4cdf-9d8c-a3a72f300ce5
caps.latest.revision: 9
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
ms.openlocfilehash: b5b47177f34af37d033b0d6933bb5b58b3b07106

---
# Compiler Error C3219
'param' : generic parameter cannot be constrained by multiple non-interfaces : 'class'  
  
 It is not valid to constrain a generic parameter by two or more managed classes.  
  
 The following sample generates C3219:  
  
```  
// C3219.cpp  
// compile with: /clr  
ref class A {};  
ref class B {};  
  
generic <class T>  
where T : A, B  
ref class E {};   // C3219  
```  
  
 The following sample demonstrates a possible resolution:  
  
```  
// C3219b.cpp  
// compile with: /clr /c  
ref class A {};  
  
interface struct C {};  
  
generic <class T>  
where T : A  
ref class E {};  
```


<!--HONumber=Jan17_HO2-->


