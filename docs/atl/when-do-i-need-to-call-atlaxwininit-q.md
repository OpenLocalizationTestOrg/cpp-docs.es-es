---
title: When Do I Need to Call AtlAxWinInit? | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: article
f1_keywords:
- AtlAxWinInit
dev_langs:
- C++
helpviewer_keywords:
- AtlAxWinInit method
ms.assetid: 080b9cfe-d85a-4439-a9e9-ab3966ebaa8e
caps.latest.revision: 11
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
ms.openlocfilehash: 6d37d009b305078b262198341a8b2ec3bec60a14

---
# When Do I Need to Call AtlAxWinInit?

[AtlAxWinInit](http://msdn.microsoft.com/library/fe1b3bd1-3fc9-42e5-ba03-66cae7dd5b7e) registers the **"AtlAxWin80"** window class (plus a couple of custom window messages) so this function must be called before you try to create a host window. However, you don't always need to call this function explicitly, since the hosting APIs (and the classes that use them) often call this function for you. There is no harm in calling this function more than once. .  
  
## See Also  
 When Do I Need to Call AtlAxWinTerm     
 [Control Containment FAQ](../atl/atl-control-containment-faq.md)



<!--HONumber=Jan17_HO1-->


