---
title: When to Initialize CWnd Objects | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: article
dev_langs:
- C++
helpviewer_keywords:
- window objects, when to initialize CWnd
- initializing CWnd objects
- initializing objects, CWnd
- CWnd objects, when HWND is attached
- HWND, when attached to CWnd object
- CWnd objects, when to initialize
ms.assetid: 4d31bcb1-73db-4f2f-b71c-89b087569a10
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
ms.sourcegitcommit: bab0fc336db7298de42d9cb302039a6eb2c5827e
ms.openlocfilehash: fb70332d0c2a5cc696dff5b4a371a9f0ebf89b3f

---
# When to Initialize CWnd Objects
You cannot create your own child windows or call any Windows API functions in the constructor of a `CWnd`-derived object. This is because the `HWND` for the `CWnd` object has not been created yet. Most Windows-specific initialization, such as adding child windows, must be done in an [OnCreate](../mfc/reference/cwnd-class.md#cwnd__oncreate) message handler.  
  
## What do you want to know more about  
  
-   [Creating document frame windows](../mfc/creating-document-frame-windows.md)  
  
-   [Document/view creation](../mfc/document-view-creation.md)  
  
## See Also  
 [Using Frame Windows](../mfc/using-frame-windows.md)




<!--HONumber=Jan17_HO1-->


