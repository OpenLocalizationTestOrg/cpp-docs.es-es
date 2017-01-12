---
title: Stream Operations in Rich Edit Controls | Microsoft Docs
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
- CRichEditCtrl class, stream operations
- CRichEditCtrl class, stream storage
- rich edit controls, stream operations
- storage, stream in CRichEditCtrl
- stream operations in CRichEditCtrl
- stream storage and CRichEditCtrl
ms.assetid: 110b4684-1e76-4ca6-9ef0-5bc8b2d93c78
caps.latest.revision: 10
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
ms.openlocfilehash: 7f43fbbffe73c66d26ad6a06008593591dc52d38

---
# Stream Operations in Rich Edit Controls
You can use streams to transfer data into or out of a rich edit control ([CRichEditCtrl](../mfc/reference/cricheditctrl-class.md)). A stream is defined by an [EDITSTREAM](http://msdn.microsoft.com/library/windows/desktop/bb787891) structure, which specifies a buffer and an application-defined callback function.  
  
 To read data into a rich edit control (that is, stream the data in), use the [StreamIn](../mfc/reference/cricheditctrl-class.md#cricheditctrl__streamin) member function. The control repeatedly calls the application-defined callback function, which transfers a portion of the data into the buffer each time.  
  
 To save the contents of a rich edit control (that is, stream the data out), you can use the [StreamOut](../mfc/reference/cricheditctrl-class.md#cricheditctrl__streamout) member function. The control repeatedly writes to the buffer and then calls the application-defined callback function. For each call, the callback function saves the contents of the buffer.  
  
## See Also  
 [Using CRichEditCtrl](../mfc/using-cricheditctrl.md)   
 [Controls](../mfc/controls-mfc.md)




<!--HONumber=Jan17_HO2-->


