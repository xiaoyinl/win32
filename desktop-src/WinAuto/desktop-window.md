---
title: Desktop Window (MSAA UI Element Reference)
description: The desktop window displays the desktop list view (which contains icons such as My Computer) and the taskbar that contains the Start button.
ms.assetid: 3668c26e-6462-4219-95d3-507811ed7f3c
ms.technology: desktop
ms.prod: windows
ms.author: windowssdkdev
ms.topic: article
ms.date: 05/31/2018
---

# Desktop Window (MSAA UI Element Reference)

The desktop window displays the desktop list view (which contains icons such as My Computer) and the taskbar that contains the **Start** button.

This object is rarely queried by clients because the list view and the taskbar cover the entire desktop. The desktop object is retrieved when you log on, before the operating system shell displays the list view and taskbar. In some cases, the desktop is obtained when navigating from other objects.

The window class name for the desktop window is "\#32769".

## IAccessible Methods

The desktop window supports the following [**IAccessible**](/windows/desktop/api/oleacc/nn-oleacc-iaccessible) methods:

-   [**accHitTest**](/windows/desktop/api/Oleacc/nf-oleacc-iaccessible-acchittest)
-   [**accLocation**](/windows/desktop/api/Oleacc/nf-oleacc-iaccessible-acclocation)
-   [**accNavigate**](/windows/desktop/api/Oleacc/nf-oleacc-iaccessible-accnavigate)
-   [**accSelect**](/windows/desktop/api/Oleacc/nf-oleacc-iaccessible-accselect)

## IAccessible Properties

The desktop window supports the following [**IAccessible**](/windows/desktop/api/oleacc/nn-oleacc-iaccessible) properties:



| Property                                                                 | Comments                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
|--------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [**get\_accChildCount**](/windows/desktop/api/Oleacc/nf-oleacc-iaccessible-get_accchildcount) |                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| [**get\_accFocus**](/windows/desktop/api/Oleacc/nf-oleacc-iaccessible-get_accfocus)           |                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| [**get\_accName**](/windows/desktop/api/Oleacc/nf-oleacc-iaccessible-get_accname)             | The Name property is "Desktop".                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| [**get\_accRole**](/windows/desktop/api/Oleacc/nf-oleacc-iaccessible-get_accrole)             | The **Role** property is [**ROLE\_SYSTEM\_CLIENT**](https://www.bing.com/search?q=**ROLE\_SYSTEM\_CLIENT**).                                                                                                                                                                                                                                                                                                                                                                                |
| [**get\_accSelection**](/windows/desktop/api/Oleacc/nf-oleacc-iaccessible-get_accselection)   |                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| [**get\_accState**](/windows/desktop/api/Oleacc/nf-oleacc-iaccessible-get_accstate)           | The **State** property is a combination of one or more of the following [values](object-state-constants.md):[**STATE\_SYSTEM\_INVISIBLE**](https://www.bing.com/search?q=**STATE\_SYSTEM\_INVISIBLE**) \| [**STATE\_SYSTEM\_UNAVAILABLE**](https://www.bing.com/search?q=**STATE\_SYSTEM\_UNAVAILABLE**) \| [**STATE\_SYSTEM\_FOCUSED**](https://www.bing.com/search?q=**STATE\_SYSTEM\_FOCUSED**) \| [**STATE\_SYSTEM\_FOCUSABLE**](https://www.bing.com/search?q=**STATE\_SYSTEM\_FOCUSABLE**)<br/> |



 

## Related topics

<dl> <dt>

[IAccessible Interface](/windows/desktop/api/oleacc/nn-oleacc-iaccessible)
</dt> </dl>

 

 




