---
title: Linker Tools Warning LNK4253 | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: error-reference
f1_keywords:
- LNK4253
dev_langs:
- C++
helpviewer_keywords:
- LNK4253
ms.assetid: ec7433a9-aa9c-495a-a9f2-075e7bc3e7bc
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
ms.openlocfilehash: 7a8500b427a9e6aa57bf12f0ecda9afaee8aadd1

---
# Linker Tools Warning LNK4253
section 'section1' not merged into 'section2'; already merged into 'section3'  
  
 The linker detected multiple, conflicting merge requests. The linker will ignore one of the requests.  
  
 A **/MERGE** option or directive is encountered and the `from` section has already been merged into a different section due to a previous **/MERGE** option or directive (or due to an implicit merge from the linker).  
  
 To resolve LNK4253, remove one of the merge requests.  
  
 When targeting x86 machines and Windows CE targets (ARM, MIPS, SH4, and Thumb) with Visual C++, the .CRT section is now read only. If your code depends on the previous behavior (.CRT sections are read/write), you could see unexpected behavior.  
  
 For more information, see,  
  
-   [/MERGE (Combine Sections)](../../build/reference/merge-combine-sections.md)  
  
-   [comment (C/C++)](../../preprocessor/comment-c-cpp.md)  
  
## Example  
 In the following sample, the linker is instructed to merge the `.rdata` section twice, but into different sections. The following sample generates LNK4253.  
  
```  
// LNK4253.cpp  
// compile with: /W1 /link /merge:.rdata=text2  
// LNK4253 expected  
#pragma comment(linker, "/merge:.rdata=.text")  
int main() {}  
```


<!--HONumber=Jan17_HO1-->


