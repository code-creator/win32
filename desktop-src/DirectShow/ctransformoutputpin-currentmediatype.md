---
Description: The CurrentMediaType method retrieves the media type for the current pin connection.
ms.assetid: 1c42664d-160a-4f76-9d7a-40414c5c1704
title: CTransformOutputPin.CurrentMediaType method
ms.technology: desktop
ms.prod: windows
ms.author: windowssdkdev
ms.topic: article
ms.date: 05/31/2018
---

# CTransformOutputPin.CurrentMediaType method

The `CurrentMediaType` method retrieves the media type for the current pin connection.

## Syntax


```C++
CMediaType&amp; CurrentMediaType();
```



## Parameters

This method has no parameters.

## Return value

Returns a reference to the [**CBasePin::m\_mt**](cbasepin-m-mt.md) member variable.

## Requirements



|                    |                                                                                                                                                                                            |
|--------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Header<br/>  | <dl> <dt>Transfrm.h (include Streams.h)</dt> </dl>                                                                                  |
| Library<br/> | <dl> <dt>Strmbase.lib (retail builds); </dt> <dt>Strmbasd.lib (debug builds)</dt> </dl> |



 

 



