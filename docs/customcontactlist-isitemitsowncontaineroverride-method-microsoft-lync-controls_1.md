﻿---
title: CustomContactList.IsItemItsOwnContainerOverride method  (Microsoft.Lync.Controls)
TOCTitle: 'IsItemItsOwnContainerOverride method '
ms:assetid: M:Microsoft.Lync.Controls.CustomContactList.IsItemItsOwnContainerOverride(System.Object)_DI_3_UC_OCS14MrefLyncWPF
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/microsoft.lync.controls.customcontactlist.isitemitsowncontaineroverride(v=office.15)
ms:contentKeyID: 48593945
ms.date: 07/28/2014
mtps_version: v=office.15
f1_keywords:
- Microsoft.Lync.Controls.CustomContactList.IsItemItsOwnContainerOverride
dev_langs:
- CSharp
- JScript
- VB
- other
---

# CustomContactList.IsItemItsOwnContainerOverride method

Overrides the IsItemItsOwnContainerOverride method to return a bool indicating whether the type is a CustomContactListItem.

**Namespace:**  [Microsoft.Lync.Controls](microsoft-lync-controls-namespace_1.md)  
**Assembly:**  Microsoft.Lync.Controls (in Microsoft.Lync.Controls.dll)

## Syntax

``` vb
'Declaration
Protected Overrides Function IsItemItsOwnContainerOverride ( _
    item As Object _
) As Boolean
'Usage
Dim item As Object
Dim returnValue As Boolean

returnValue = Me.IsItemItsOwnContainerOverride(item)
```

``` csharp
protected override bool IsItemItsOwnContainerOverride(
    Object item
)
```

#### Parameters

  - item  
    Type: [System.Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b)  

#### Return value

Type: [System.Boolean](http://msdn2.microsoft.com/en-us/library/a28wyd50)  

## See also

#### Reference

[CustomContactList class](customcontactlist-class-microsoft-lync-controls_1.md)

[CustomContactList members](customcontactlist-members-microsoft-lync-controls_1.md)

[Microsoft.Lync.Controls namespace](microsoft-lync-controls-namespace_1.md)
