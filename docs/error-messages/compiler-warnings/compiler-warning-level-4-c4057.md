---
title: Compiler Warning (level 4) C4057 | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-csharp
ms.tgt_pltfrm: 
ms.topic: article
f1_keywords:
- C4057
dev_langs:
- C++
helpviewer_keywords:
- C4057
ms.assetid: e75d0645-84c9-4bef-a812-942ed9879aa3
caps.latest.revision: 6
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
ms.openlocfilehash: ad1013a90b2b3d6ad1f7148ea62c05ae505348d4

---
# Compiler Warning (level 4) C4057
'operator' : 'identifier1' indirection to slightly different base types from 'identifier2'  
  
 Two pointer expressions refer to different base types. The expressions are used without conversion.  
  
### To fix by checking the following possible causes  
  
1.  Mixing signed and unsigned types.  
  
2.  Mixing **short** and **long** types.


<!--HONumber=Jan17_HO2-->


