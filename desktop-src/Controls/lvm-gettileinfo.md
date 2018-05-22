---
title: LVM\_GETTILEINFO message
description: Retrieves information about a tile in a list-view control.
ms.assetid: 'e89a3eae-0970-488c-ba95-1072aa85bbf4'
keywords: ["LVM_GETTILEINFO message Windows Controls"]
topic_type:
- apiref
api_name:
- LVM_GETTILEINFO
api_location:
- Commctrl.h
api_type:
- HeaderDef
---

# LVM\_GETTILEINFO message

Retrieves information about a tile in a list-view control.

## Parameters

<dl> <dt>

*wParam* 
</dt> <dd>Must be zero.</dd> <dt>

*lParam* 
</dt> <dd>Pointer to an [**LVTILEINFO**](lvtileinfo.md) structure that receives the retrieved information.</dd> </dl>

## Return value

Return value not used.

## Remarks

Tile view is a new way of arranging and displaying items in a list-view control. The other views are icon, small icon, details, and list.

> [!Note]  
> To use this message, you must provide a manifest specifying Comclt32.dll version 6.0. For more information on manifests, see [Enabling Visual Styles](cookbook-overview.md).

�

## Requirements



|                                     |                                                                                       |
|-------------------------------------|---------------------------------------------------------------------------------------|
| Minimum supported client<br/> | Windows�Vista \[desktop apps only\]<br/>                                        |
| Minimum supported server<br/> | Windows Server�2003 \[desktop apps only\]<br/>                                  |
| Header<br/>                   | <dl> <dt>Commctrl.h</dt> </dl> |



�

�




