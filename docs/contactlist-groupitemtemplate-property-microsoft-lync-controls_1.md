﻿---
title: ContactList.GroupItemTemplate property  (Microsoft.Lync.Controls)
TOCTitle: 'GroupItemTemplate property '
ms:assetid: P:Microsoft.Lync.Controls.ContactList.GroupItemTemplate_DI_3_UC_OCS14MrefLyncWPF
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/microsoft.lync.controls.contactlist.groupitemtemplate_di_3_uc_ocs14mreflyncwpf(v=office.15)
ms:contentKeyID: 48601472
ms.date: 07/28/2014
mtps_version: v=office.15
f1_keywords:
- Microsoft.Lync.Controls.ContactList.GroupItemTemplate
dev_langs:
- CSharp
- JScript
- VB
- other
---

# ContactList.GroupItemTemplate property

Gets or sets the [DataTemplate](http://msdn2.microsoft.com/en-us/library/ms589297) used for Group-type contacts in [OneLine](contactlayoutoption-enumeration-microsoft-lync-controls_1.md) mode. (See [ContactLayoutView](contactlist-contactlayoutview-property-microsoft-lync-controls_1.md)).

**Namespace:**  [Microsoft.Lync.Controls](microsoft-lync-controls-namespace_1.md)  
**Assembly:**  Microsoft.Lync.Controls (in Microsoft.Lync.Controls.dll)

## Syntax

``` vb
'Declaration
Public Property GroupItemTemplate As DataTemplate
    Get
    Set
'Usage
Dim instance As ContactList
Dim value As DataTemplate

value = instance.GroupItemTemplate

instance.GroupItemTemplate = value
```

``` csharp
public DataTemplate GroupItemTemplate { get; set; }
```

#### Property value

Type: [System.Windows.DataTemplate](http://msdn2.microsoft.com/en-us/library/ms589297)  

## See also

#### Reference

[ContactList class](contactlist-class-microsoft-lync-controls_1.md)

[ContactList members](contactlist-members-microsoft-lync-controls_1.md)

[Microsoft.Lync.Controls namespace](microsoft-lync-controls-namespace_1.md)
