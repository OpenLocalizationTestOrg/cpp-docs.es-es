---
title: Microsoft Extensions | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: language-reference
dev_langs:
- C++
helpviewer_keywords:
- Microsoft extensions to C/C++
ms.assetid: 68654516-24ef-4f33-aae2-175f86cc1979
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
ms.sourcegitcommit: 5187996fc377bca8633360082d07f7ec8a68ee57
ms.openlocfilehash: a1b49b921ff296a1ba0117b3e02eb5ef4fa857f1

---
# Microsoft Extensions
*asm-statement*:  
 **__asm**  *assembly-instruction* **;**opt  
  
 **__asm {**  *assembly-instruction-list*  **};**opt  
  
 *assembly-instruction-list*:  
 *assembly-instruction* **;**opt  
  
 *assembly-instruction* **;** *assembly-instruction-list* **;**opt  
  
 *ms-modifier-list*:  
 *ms-modifier ms-modifier-list*opt  
  
 *ms-modifier*:  
 **__cdecl**  
  
 **__fastcall**  
  
 **__stdcall**  
  
 **__syscall** (reserved for future implementations)  
  
 **__oldcall** (reserved for future implementations)  
  
 **__unaligned** (reserved for future implementations)  
  
 *based-modifier*  
  
 *based-modifier*:  
 **__based (** *based-type* **)**  
  
 *based-type*:  
 *name*  



<!--HONumber=Jan17_HO1-->


