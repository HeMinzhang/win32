---
Description: The GetPositions method retrieves the current position and the stop position, relative to the total duration of the stream. This method implements the IMediaSeeking::GetPositions method.
ms.assetid: 51e45bc3-ae30-4b05-b9d9-684c1b028f51
title: CPosPassThru.GetPositions method
ms.technology: desktop
ms.prod: windows
ms.author: windowssdkdev
ms.topic: article
ms.date: 05/31/2018
---

# CPosPassThru.GetPositions method

The `GetPositions` method retrieves the current position and the stop position, relative to the total duration of the stream. This method implements the [**IMediaSeeking::GetPositions**](/windows/desktop/api/Strmif/nf-strmif-imediaseeking-getpositions) method.

## Syntax


```C++
HRESULT GetPositions(
   LONGLONG *pCurrent,
   LONGLONG *pStop
);
```



## Parameters

<dl> <dt>

*pCurrent* 
</dt> <dd>

Pointer to a variable that receives the current position, in units of the current time format.

</dd> <dt>

*pStop* 
</dt> <dd>

Pointer to a variable that receives the stop position, in units of the current time format.

</dd> </dl>

## Return value

Returns the **HRESULT** value from the connected pin.

## Requirements



|                    |                                                                                                                                                                                            |
|--------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Header<br/>  | <dl> <dt>Ctlutil.h (include Streams.h)</dt> </dl>                                                                                   |
| Library<br/> | <dl> <dt>Strmbase.lib (retail builds); </dt> <dt>Strmbasd.lib (debug builds)</dt> </dl> |



## See also

<dl> <dt>

[**CPosPassThru Class**](cpospassthru.md)
</dt> </dl>

 

 



