---
title: Linker Tools Error LNK1200 | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: error-reference
f1_keywords:
- LNK1200
dev_langs:
- C++
helpviewer_keywords:
- LNK1200
ms.assetid: 55771145-915e-4006-ac6c-ac702041eb2f
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
ms.openlocfilehash: 898b098944d223c2be74f454cc979fb7393f9fed

---
# Linker Tools Error LNK1200
error reading program database 'filename'  
  
 The program database (PDB) could not be read.  
  
 This error can be caused by file corruption.  
  
 If `filename` is the PDB for an object file, recompile the object file using [/Zi](../../build/reference/z7-zi-zi-debug-information-format.md).  
  
 If `filename` is the PDB for the main output file, and this error occurred during an incremental link, delete the PDB and relink.


<!--HONumber=Jan17_HO2-->


