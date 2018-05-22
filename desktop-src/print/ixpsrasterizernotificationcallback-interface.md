﻿---
Description: 'The IXpsRasterizerNotificationCallback interface enables the XPS rasterization service to determine whether to continue a rasterization operation that was previously initiated by an XPSDrv filter.'
ms.assetid: '7616b5c7-a21f-4db1-923b-ebf2a039b5ec'
title: IXpsRasterizerNotificationCallback interface
---

# IXpsRasterizerNotificationCallback interface

The IXpsRasterizerNotificationCallback interface enables the XPS rasterization service to determine whether to continue a rasterization operation that was previously initiated by an XPSDrv filter. The filter implements this interface and passes an IXpsRasterizerNotificationCallback pointer as a parameter to the [**IXpsRasterizer::RasterizeRect**](ixpsrasterizer-rasterizerect.md) method.

## Members

The **IXpsRasterizerNotificationCallback** interface inherits from the [**IUnknown**](com.iunknown) interface. **IXpsRasterizerNotificationCallback** also has these types of members:

-   [Methods](#methods)

### Methods

The **IXpsRasterizerNotificationCallback** interface has these methods.



| Method                                                          | Description                                                                                                                                   |
|:----------------------------------------------------------------|:----------------------------------------------------------------------------------------------------------------------------------------------|
| [**Continue**](ixpsrasterizernotificationcallback-continue.md) | The `Continue` method tells the caller (the XPS rasterization service) whether to continue rasterizing the current XPS fixed page.<br/> |



 

## Requirements



|                   |                                                                                        |
|-------------------|----------------------------------------------------------------------------------------|
| Header<br/> | <dl> <dt>Xpsrassvc.h</dt> </dl> |



 

 

[Send comments about this topic to Microsoft](mailto:wsddocfb@microsoft.com?subject=Documentation%20feedback%20%5Bprint\print%5D:%20IXpsRasterizerNotificationCallback%20interface%20%20RELEASE:%20%285/12/2018%29&body=%0A%0APRIVACY%20STATEMENT%0A%0AWe%20use%20your%20feedback%20to%20improve%20the%20documentation.%20We%20don't%20use%20your%20email%20address%20for%20any%20other%20purpose,%20and%20we'll%20remove%20your%20email%20address%20from%20our%20system%20after%20the%20issue%20that%20you're%20reporting%20is%20fixed.%20While%20we're%20working%20to%20fix%20this%20issue,%20we%20might%20send%20you%20an%20email%20message%20to%20ask%20for%20more%20info.%20Later,%20we%20might%20also%20send%20you%20an%20email%20message%20to%20let%20you%20know%20that%20we've%20addressed%20your%20feedback.%0A%0AFor%20more%20info%20about%20Microsoft's%20privacy%20policy,%20see%20http://privacy.microsoft.com/en-us/default.aspx. "Send comments about this topic to Microsoft")



