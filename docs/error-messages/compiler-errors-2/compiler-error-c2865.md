---
title: Compiler Error C2865 | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: error-reference
f1_keywords:
- C2865
dev_langs:
- C++
helpviewer_keywords:
- C2865
ms.assetid: 973eb6a0-c99a-4d25-b3e5-fe0539794d77
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
ms.sourcegitcommit: c243063a9770542f137d5950e8a269f771960f74
ms.openlocfilehash: 3bb55d094e00400c57617857aa1ac29677f1b72a

---
# Compiler Error C2865
'function' : illegal comparison for handle_or_pointer  
  
 You can compare references to [Classes and Structs](../../windows/classes-and-structs-cpp-component-extensions.md) or managed reference types only for equality to see if they refer to the same object (==) or to different objects (!=).  
  
 You cannot compare them for ordering because the .NET runtime might move managed objects at any time, changing the outcome of the test.


<!--HONumber=Jan17_HO2-->


