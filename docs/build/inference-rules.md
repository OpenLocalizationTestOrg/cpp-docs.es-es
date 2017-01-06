---
title: Inference Rules | Microsoft Docs
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
- inference rules in NMAKE
- rules, inference
- NMAKE program, inference rules
ms.assetid: caff320f-fb07-4eea-80c3-a6a2133a8492
caps.latest.revision: 6
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
ms.openlocfilehash: d765e212d2b6e461bff5cd4addd3b38ed06aaa9d

---
# Inference Rules
Inference rules supply commands to update targets and to infer dependents for targets. Extensions in an inference rule match a single target and dependent that have the same base name. Inference rules are user-defined or predefined; predefined rules can be redefined.  
  
 If an out-of-date dependency has no commands, and if [.SUFFIXES](../build/dot-directives.md) contains the dependent's extension, NMAKE uses a rule whose extensions match the target and an existing file in the current or specified directory. If more than one rule matches existing files, the **.SUFFIXES** list determines which to use; list priority descends from left to right. If a dependent file does not exist and is not listed as a target in another description block, an inference rule can create the missing dependent from another file with the same base name. If a description block's target has no dependents or commands, an inference rule can update the target. Inference rules can build a command-line target even if no description block exists. NMAKE may invoke a rule for an inferred dependent even if an explicit dependent is specified.  
  
## What do you want to know more about?  
 [Defining a rule](../build/defining-a-rule.md)  
  
 [Batch-mode rules](../build/batch-mode-rules.md)  
  
 [Predefined rules](../build/predefined-rules.md)  
  
 [Inferred dependents and rules](../build/inferred-dependents-and-rules.md)  
  
 [Precedence in inference rules](../build/precedence-in-inference-rules.md)  
  
## See Also  
 [NMAKE Reference](../build/nmake-reference.md)


<!--HONumber=Jan17_HO1-->


