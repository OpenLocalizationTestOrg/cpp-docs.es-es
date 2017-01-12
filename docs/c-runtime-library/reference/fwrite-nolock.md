---
title: _fwrite_nolock | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: article
apiname:
- _fwrite_nolock
apilocation:
- msvcrt.dll
- msvcr80.dll
- msvcr90.dll
- msvcr100.dll
- msvcr100_clr0400.dll
- msvcr110.dll
- msvcr110_clr0400.dll
- msvcr120.dll
- msvcr120_clr0400.dll
- ucrtbase.dll
- api-ms-win-crt-stdio-l1-1-0.dll
apitype: DLLExport
f1_keywords:
- _fwrite_nolock
- fwrite_nolock
dev_langs:
- C++
- C
helpviewer_keywords:
- fwrite_nolock function
- streams, writing data to
- _fwrite_nolock function
ms.assetid: 2b4ec6ce-742e-4615-8407-44a0a18ec1d7
caps.latest.revision: 11
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
ms.openlocfilehash: 5f0f0aba9bdc1986b662e949332b389eb2e44a42

---
# _fwrite_nolock
Writes data to a stream, without locking the thread.  
  
## Syntax  
  
```  
size_t _fwrite_nolock(  
   const void *buffer,  
   size_t size,  
   size_t count,  
   FILE *stream   
);  
```  
  
#### Parameters  
 `buffer`  
 Pointer to the data to be written.  
  
 `size`  
 Item size in bytes.  
  
 `count`  
 Maximum number of items to be written.  
  
 `stream`  
 Pointer to the `FILE` structure.  
  
## Return Value  
 Same as [fwrite](../../c-runtime-library/reference/fwrite.md).  
  
## Remarks  
 This function is a non-locking version of `fwrite`. It is identical to `fwrite` except that it is not protected from interference by other threads. It might be faster because it does not incur the overhead of locking out other threads. Use this function only in thread-safe contexts such as single-threaded applications or where the calling scope already handles thread isolation.  
  
## Requirements  
  
|Function|Required header|  
|--------------|---------------------|  
|`_fwrite_nolock`|\<stdio.h>|  
  
 For more compatibility information, see [Compatibility](../../c-runtime-library/compatibility.md) in the Introduction.  
  
## Example  
 See the example for [fread](../../c-runtime-library/reference/fread.md).  
  
## .NET Framework Equivalent  
 [System::IO::FileStream::Write](https://msdn.microsoft.com/en-us/library/system.io.filestream.write.aspx)  
  
## See Also  
 [Stream I/O](../../c-runtime-library/stream-i-o.md)   
 [fread](../../c-runtime-library/reference/fread.md)   
 [_write](../../c-runtime-library/reference/write.md)


<!--HONumber=Jan17_HO2-->


