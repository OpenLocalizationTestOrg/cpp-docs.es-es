---
title: '&lt;random&gt; functions | Microsoft Docs'
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.tgt_pltfrm: 
ms.topic: article
ms.assetid: 2ac9ec59-619b-4b85-a425-f729277c1bc8
caps.latest.revision: 10
manager: ghogen
translationtype: Human Translation
ms.sourcegitcommit: 3168772cbb7e8127523bc2fc2da5cc9b4f59beb8
ms.openlocfilehash: 3aebef535acb59046fab53d49051df16bd362c3c

---
# &lt;random&gt; functions
  
##  <a name="generate_canonical"></a>  generate_canonical  
 Returns a floating-point value from a random sequence.  
  
> [!NOTE]
>  The ISO C++ Standard states that this function should return values in the range [ `0`, `1`). Visual Studio is not yet compliant with this constraint. As a workaround to generate values in this range, use [uniform_real_distribution](../standard-library/uniform-real-distribution-class.md).  
  
```  
template <class RealType, size_t Bits, class Generator>  
RealType generate_canonical(Generator& Gen);
```  
  
### Parameters  
 `RealType`  
 The floating point integral type. For possible types, see [\<random>](../standard-library/random.md).  
  
 `Bits`  
 The random number generator.  
  
 `Gen`  
 The random number generator.  
  
### Remarks  
 The template function calls `operator()` of `Gen` repeatedly and packs the returned values into a floating-point value `x` of type `RealType` until it has gathered the specified number of mantissa bits in `x`. The specified number is the smaller of `Bits` (which must be nonzero) and the full number of mantissa bits in `RealType`. The first call supplies the lowest-order bits. The function returns `x`.  
  
## See Also  
 [\<random>](../standard-library/random.md)




<!--HONumber=Jan17_HO2-->


