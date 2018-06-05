---
title: MCM\_SETSELRANGE message
description: Sets the selection for a month calendar control to a given date range. You can send this message explicitly or by using the MonthCal\_SetSelRange macro.
ms.assetid: 750b0c83-6baa-4caa-a738-feae8751a70e
keywords:
- MCM_SETSELRANGE message Windows Controls
topic_type:
- apiref
api_name:
- MCM_SETSELRANGE
api_location:
- Commctrl.h
api_type:
- HeaderDef
ms.technology: desktop
ms.prod: windows
ms.author: windowssdkdev
ms.topic: article
ms.date: 05/31/2018
---

# MCM\_SETSELRANGE message

Sets the selection for a month calendar control to a given date range. You can send this message explicitly or by using the [**MonthCal\_SetSelRange**](/windows/desktop/api/Commctrl/nf-commctrl-monthcal_setselrange) macro.

## Parameters

<dl> <dt>

*wParam* 
</dt> <dd>Must be zero.</dd> <dt>

*lParam* 
</dt> <dd>

Pointer to a two-element array of [**SYSTEMTIME**](https://msdn.microsoft.com/library/windows/desktop/ms724950) structures that contain date information representing the selection limits. The first selected date must be specified in *lpSysTimeArray*\[0\], and the last selected date must be specified in *lpSysTimeArray*\[1\].

</dd> </dl>

## Return value

Returns nonzero if successful, or zero otherwise. This message will fail if applied to a month calendar control that does not use the [**MCS\_MULTISELECT**](https://www.bing.com/search?q=**MCS\_MULTISELECT**) style.

## Requirements



|                                     |                                                                                       |
|-------------------------------------|---------------------------------------------------------------------------------------|
| Minimum supported client<br/> | Windows Vista \[desktop apps only\]<br/>                                        |
| Minimum supported server<br/> | Windows Server 2003 \[desktop apps only\]<br/>                                  |
| Header<br/>                   | <dl> <dt>Commctrl.h</dt> </dl> |



## See also

<dl> <dt>

[Times in the Month Calendar Control](https://www.bing.com/search?q=Times in the Month Calendar Control)
</dt> </dl>

 

 




