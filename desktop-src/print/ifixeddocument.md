---
Description: The IFixedDocument interface represents a fixed document for an XPS document sequence.
ms.assetid: 3f9f64a1-8681-4b70-8cdc-7c944912f767
title: IFixedDocument interface
ms.technology: desktop
ms.prod: windows
ms.author: windowssdkdev
ms.topic: interface
ms.date: 05/31/2018
---

# IFixedDocument interface

The **IFixedDocument** interface represents a fixed document for an XPS document sequence. An XPS fixed document sequence will have one or more fixed documents in it.

## Members

The **IFixedDocument** interface inherits from the [**IUnknown**](https://msdn.microsoft.com/33f1d79a-33fc-4ce5-a372-e08bda378332) interface. **IFixedDocument** also has these types of members:

-   [Methods](#methods)

### Methods

The **IFixedDocument** interface has these methods.



| Method                                                                  | Description                                                                                   |
|:------------------------------------------------------------------------|:----------------------------------------------------------------------------------------------|
| [**IFixedDocument::GetPrintTicket**](ifixeddocument-getprintticket.md) | The **GetPrintTicket** method gets the print ticket object for the fixed document.<br/> |
| [**IFixedDocument::GetUri**](ifixeddocument-geturi.md)                 | The **GetUri** method gets the URI of the fixed document.<br/>                          |
| [**IFixedDocument::SetPrintTicket**](ifixeddocument-setprintticket.md) | The **SetPrintTicket** method inserts a print ticket into the fixed document.<br/>      |



 

## Requirements



|                   |                                                                                                                        |
|-------------------|------------------------------------------------------------------------------------------------------------------------|
| Header<br/> | <dl> <dt>Filterpipeline.h (include Filterpipeline.h)</dt> </dl> |



 

 

[Send comments about this topic to Microsoft](mailto:wsddocfb@microsoft.com?subject=Documentation%20feedback%20%5Bprint\print%5D:%20IFixedDocument%20interface%20%20RELEASE:%20%285/12/2018%29&body=%0A%0APRIVACY%20STATEMENT%0A%0AWe%20use%20your%20feedback%20to%20improve%20the%20documentation.%20We%20don't%20use%20your%20email%20address%20for%20any%20other%20purpose,%20and%20we'll%20remove%20your%20email%20address%20from%20our%20system%20after%20the%20issue%20that%20you're%20reporting%20is%20fixed.%20While%20we're%20working%20to%20fix%20this%20issue,%20we%20might%20send%20you%20an%20email%20message%20to%20ask%20for%20more%20info.%20Later,%20we%20might%20also%20send%20you%20an%20email%20message%20to%20let%20you%20know%20that%20we've%20addressed%20your%20feedback.%0A%0AFor%20more%20info%20about%20Microsoft's%20privacy%20policy,%20see%20http://privacy.microsoft.com/en-us/default.aspx. "Send comments about this topic to Microsoft")



