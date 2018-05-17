﻿---
title: SelfBase.OnPresenceItemsPropertyChanged method  (Microsoft.Lync.Controls)
TOCTitle: 'OnPresenceItemsPropertyChanged method '
ms:assetid: M:Microsoft.Lync.Controls.SelfBase.OnPresenceItemsPropertyChanged(Microsoft.Lync.Controls.Internal.Model.IPresenceItems,System.String)_DI_3_UC_OCS14MrefLyncWPF
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/microsoft.lync.controls.selfbase.onpresenceitemspropertychanged(v=office.15)
ms:contentKeyID: 48595838
ms.date: 07/28/2014
mtps_version: v=office.15
f1_keywords:
- Microsoft.Lync.Controls.SelfBase.OnPresenceItemsPropertyChanged
dev_langs:
- CSharp
- JScript
- VB
- other
---

# SelfBase.OnPresenceItemsPropertyChanged method

Reserved for internal use.

**Namespace:**  [Microsoft.Lync.Controls](microsoft-lync-controls-namespace_1.md)  
**Assembly:**  Microsoft.Lync.Controls (in Microsoft.Lync.Controls.dll)

## Syntax

``` vb
'Declaration
Protected Overridable Sub OnPresenceItemsPropertyChanged ( _
    presenceItems As IPresenceItems, _
    propertyName As String _
)
'Usage
Dim presenceItems As IPresenceItems
Dim propertyName As String

Me.OnPresenceItemsPropertyChanged(presenceItems, _
    propertyName)
```

``` csharp
protected virtual void OnPresenceItemsPropertyChanged(
    IPresenceItems presenceItems,
    string propertyName
)
```

#### Parameters

  - presenceItems  
    Type: **IPresenceItems**  

<!-- end list -->

  - propertyName  
    Type: [System.String](http://msdn2.microsoft.com/en-us/library/s1wwdcbf)  

## See also

#### Reference

[SelfBase class](selfbase-class-microsoft-lync-controls_1.md)

[SelfBase members](selfbase-members-microsoft-lync-controls_1.md)

[Microsoft.Lync.Controls namespace](microsoft-lync-controls-namespace_1.md)
