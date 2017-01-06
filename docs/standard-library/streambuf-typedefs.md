---
title: '&lt;streambuf&gt; typedefs | Microsoft Docs'
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.tgt_pltfrm: 
ms.topic: article
ms.assetid: 2678e18f-f0f0-4995-bc53-f1bc7dfc4ec6
caps.latest.revision: 11
manager: ghogen
translationtype: Human Translation
ms.sourcegitcommit: 3168772cbb7e8127523bc2fc2da5cc9b4f59beb8
ms.openlocfilehash: 8a11f21fc55babc7c71bb312bc582719f532347a

---
# &lt;streambuf&gt; typedefs
|||  
|-|-|  
|[streambuf](#streambuf)|[wstreambuf](#wstreambuf)|  
  
##  <a name="streambuf"></a>  streambuf  
 A specialization of `basic_streambuf` that uses `char` as the template parameters.  
  
```
typedef basic_streambuf<char, char_traits<char>> streambuf;
```  
  
### Remarks  
 The type is a synonym for the template class [basic_streambuf](../standard-library/basic-streambuf-class.md), specialized for elements of type `char` with default character traits.  
  
##  <a name="wstreambuf"></a>  wstreambuf  
 A specialization of `basic_streambuf` that uses `wchar_t` as the template parameters.  
  
```
typedef basic_streambuf<wchar_t, char_traits<wchar_t>> wstreambuf;
```  
  
### Remarks  
 The type is a synonym for the template class [basic_streambuf](../standard-library/basic-streambuf-class.md), specialized for elements of type `wchar_t` with default character traits.  
  
## See Also  
 [\<streambuf>](../standard-library/streambuf.md)






<!--HONumber=Jan17_HO1-->


