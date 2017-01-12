---
title: Compiler Error C2862 | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: error-reference
f1_keywords:
- C2862
dev_langs:
- C++
helpviewer_keywords:
- C2862
ms.assetid: c04d8499-b799-48a1-9fb4-7902a0b0ac8e
caps.latest.revision: 8
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
ms.openlocfilehash: 53515121e59f663985e7b0340fcac195c580915d

---
# Compiler Error C2862
'interface' : an interface can only have public members  
  
 Protected and private members may be accessed only from other member functions. Such members are no use in an interface, since it may not provide implementations for any of its members.  
  
 The following sample will generate C2862:  
  
```  
// C2862.cpp  
// compile with: /c  
#include <unknwn.h>  
  
[object, uuid="60719E20-EF37-11D1-978D-0000F805D73B"]  
__interface IMyInterface {  
   HRESULT mf1(void);   // OK  
protected:  
   HRESULT mf2(int *b);   // C2862  
private:  
   HRESULT mf3(int *c);   // C2862  
};  
```


<!--HONumber=Jan17_HO2-->


