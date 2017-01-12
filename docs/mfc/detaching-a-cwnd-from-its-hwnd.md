---
title: Detaching a CWnd from Its HWND | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: article
f1_keywords:
- CWnd
dev_langs:
- C++
helpviewer_keywords:
- HWND, detaching CWnd from
- removing HWNDs from CWnds
- CWnd objects, detaching from HWND
- detaching CWnds from HWNDs
- Detach method (CWnd class)
ms.assetid: 6efadf84-0517-4a3f-acfd-216e088f19c6
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
ms.openlocfilehash: 4f3ab29e16c6bee10208e71019d955b5b6a44f84

---
# Detaching a CWnd from Its HWND
If you need to circumvent the object-`HWND` relationship, MFC provides another `CWnd` member function, [Detach](../mfc/reference/cwnd-class.md#cwnd__detach), which disconnects the C++ window object from the Windows window. This prevents the destructor from destroying the Windows window when the object is destroyed.  
  
## What do you want to know more about  
  
-   [Creating windows](../mfc/creating-windows.md)  
  
-   [Window destruction sequence](../mfc/window-destruction-sequence.md)  
  
-   [Allocating and deallocating window memory](../mfc/allocating-and-deallocating-window-memory.md)  
  
## See Also  
 [Window Objects](../mfc/window-objects.md)




<!--HONumber=Jan17_HO2-->


