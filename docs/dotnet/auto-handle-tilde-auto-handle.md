---
title: auto_handle::~auto_handle | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: reference
f1_keywords:
- auto_handle.~auto_handle
- msclr.auto_handle.~auto_handle
- auto_handle::~auto_handle
- ~auto_handle
- msclr::auto_handle::~auto_handle
dev_langs:
- C++
helpviewer_keywords:
- auto_handle::~auto_handle
ms.assetid: e83e95a8-015b-4f27-ad63-70efb3690726
caps.latest.revision: 9
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
ms.openlocfilehash: 7bdcb7604d1310cbef0c9b3dd8f4c4504af722b0

---
# auto_handle::~auto_handle
The `auto_handle` destructor.  
  
## Syntax  
  
```  
~auto_handle();  
```  
  
## Remarks  
 The destructor also destructs the owned object.  
  
## Example  
  
```  
// msl_auto_handle_dtor.cpp  
// compile with: /clr  
#include "msclr\auto_handle.h"  
  
using namespace System;  
using namespace msclr;  
  
ref class ClassA {  
public:  
   ClassA() { Console::WriteLine( "ClassA constructor" ); }  
   ~ClassA() { Console::WriteLine( "ClassA destructor" ); }  
};  
  
int main()  
{  
   // create a new scope for a:  
   {  
      auto_handle<ClassA> a = gcnew ClassA;  
   }  
   // a goes out of scope here, invoking its destructor  
   // which in turns destructs the ClassA object.  
  
   Console::WriteLine( "done" );  
}  
```  
  
```Output  
ClassA constructor  
ClassA destructor  
done  
```  
  
## Requirements  
 **Header file** \<msclr\auto_handle.h>  
  
 **Namespace** msclr  
  
## See Also  
 [auto_handle Members](../dotnet/auto-handle-members.md)   
 [auto_handle::release](../dotnet/auto-handle-release.md)   
 [auto_handle::auto_handle](../dotnet/auto-handle-auto-handle.md)


<!--HONumber=Jan17_HO2-->


