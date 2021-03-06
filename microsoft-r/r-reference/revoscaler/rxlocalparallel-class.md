--- 
 
# required metadata 
title: "RxLocalParallel-class function (RevoScaleR) " 
description: "   Class for the RevoScaleR Local Parallel Compute Context.   " 
keywords: "(RevoScaleR), RxLocalParallel-class, show,RxLocalParallel-method, classes" 
author: "heidisteen" 
manager: "jhubbard" 
ms.date: "09/07/2017" 
ms.topic: "reference" 
ms.prod: "microsoft-r" 
ms.service: "" 
ms.assetid: "" 
 
# optional metadata 
ROBOTS: "" 
audience: "" 
ms.devlang: "" 
ms.reviewer: "" 
ms.suite: "" 
ms.tgt_pltfrm: "" 
ms.technology: "r-server" 
ms.custom: "" 
 
--- 
 
 
 
 
 #RxLocalParallel-class: Class RxLocalParallel 
 ##Description
 
Class for the RevoScaleR Local Parallel Compute Context.  
 
 
 ## Generators 

 
The targeted generator [RxLocalParallel](RxLocalParallel.md) as well as the general generator
[RxComputeContext](RxComputeContext.md).
 
 ## Extends 

 
Class RxComputeContext, directly.
 
 ## Methods 

 


###`show`
`signature(object = "RxLocalParallel")`: ...



 

 
 
 
 ##See Also
 
[RxHadoopMR](RxHadoopMR.md),
[RxSpark](RxSpark.md),
[RxInSqlServer](RxInSqlServer.md),
[RxLocalSeq](RxLocalSeq.md).
   
 ##Examples

 ```
   
  ## Not run:
 
myComputeContext <- RxComputeContext("RxLocalParallel")
is(myComputeContext, "RxComputeContext")
# [1] TRUE
is(myComputeContext, "RxLocalParallel")
# [1] TRUE
 ## End(Not run) 
  
 
```
 
 
