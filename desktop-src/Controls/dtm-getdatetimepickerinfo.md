---
title: DTM\_GETDATETIMEPICKERINFO message
description: Gets information on a date and time picker (DTP) control.
ms.assetid: 04847b68-ac45-4b28-8f62-2cd68ffe48d4
keywords:
- DTM_GETDATETIMEPICKERINFO message Windows Controls
topic_type:
- apiref
api_name:
- DTM_GETDATETIMEPICKERINFO
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

# DTM\_GETDATETIMEPICKERINFO message

Gets information on a date and time picker (DTP) control.

## Parameters

<dl> <dt>

*wParam* 
</dt> <dd>

Must be zero.

</dd> <dt>

*lParam* \[in\]
</dt> <dd> A pointer to [**DATETIMEPICKERINFO**](/windows/desktop/api/Commctrl/ns-commctrl-tagdatetimepickerinfo) to receive the information. The caller is responsible for allocating the memory for this structure. Set the **cbSize** member of the structure to sizeof(DATETIMEPICKERINFO) before sending this message.</dd> </dl>

## Return value

Return value is ignored.

## Requirements



|                                     |                                                                                       |
|-------------------------------------|---------------------------------------------------------------------------------------|
| Minimum supported client<br/> | Windows Vista \[desktop apps only\]<br/>                                        |
| Minimum supported server<br/> | Windows Server 2008 \[desktop apps only\]<br/>                                  |
| Header<br/>                   | <dl> <dt>Commctrl.h</dt> </dl> |



 

 




