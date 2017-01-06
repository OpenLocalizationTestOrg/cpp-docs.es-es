---
title: Compiler Warning (level 3) C4278 | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: error-reference
f1_keywords:
- C4278
dev_langs:
- C++
helpviewer_keywords:
- C4278
ms.assetid: 4b6053fb-df62-4c04-b6c8-c011759557b8
caps.latest.revision: 7
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
ms.openlocfilehash: 8b7811a0112e0054e6e1ce1b62f0900f7333ccc6

---
# Compiler Warning (level 3) C4278
'identifier': identifier in type library 'tlb' is already a macro; use the 'rename' qualifier  
  
 When using [#import](../../preprocessor/hash-import-directive-cpp.md), an identifier in the typelib you are importing is attempting to declare an identifier ***identifier***. However, this is already a valid symbol.  
  
 Use the `#import` **rename** attribute to assign an alias to the symbol in the type library.


<!--HONumber=Jan17_HO1-->


