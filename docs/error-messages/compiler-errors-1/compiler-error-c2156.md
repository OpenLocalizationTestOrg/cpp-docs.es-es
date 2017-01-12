---
title: Compiler Error C2156 | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-csharp
ms.tgt_pltfrm: 
ms.topic: article
f1_keywords:
- C2156
dev_langs:
- C++
helpviewer_keywords:
- C2156
ms.assetid: 136f9c67-2c27-4f61-b7e6-ccd202eca697
caps.latest.revision: 8
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
ms.openlocfilehash: fb68551c608aa096f288ecc20cf2243b7b36c337

---
# Compiler Error C2156
pragma must be outside function  
  
 A pragma that must be specified at a global level (outside a function body) is within a function.  
  
 The following sample generates C2156:  
  
```  
// C2156.cpp  
#pragma optimize( "l", on )   // OK  
int main() {  
   #pragma optimize( "l", on )   // C2156  
}  
```


<!--HONumber=Jan17_HO2-->


