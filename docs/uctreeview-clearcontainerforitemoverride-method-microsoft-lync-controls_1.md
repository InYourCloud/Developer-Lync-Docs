﻿---
title: UCTreeView.ClearContainerForItemOverride method  (Microsoft.Lync.Controls)
TOCTitle: 'ClearContainerForItemOverride method '
ms:assetid: M:Microsoft.Lync.Controls.UCTreeView.ClearContainerForItemOverride(System.Windows.DependencyObject,System.Object)_DI_3_UC_OCS14MrefLyncWPF
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/microsoft.lync.controls.uctreeview.clearcontainerforitemoverride(v=office.15)
ms:contentKeyID: 48598022
ms.date: 07/28/2014
mtps_version: v=office.15
f1_keywords:
- Microsoft.Lync.Controls.UCTreeView.ClearContainerForItemOverride
dev_langs:
- CSharp
- JScript
- VB
- other
---

# UCTreeView.ClearContainerForItemOverride method

Undoes the effects of **\[PrepareContainerForItemOverride\]**

**Namespace:**  [Microsoft.Lync.Controls](microsoft-lync-controls-namespace_1.md)  
**Assembly:**  Microsoft.Lync.Controls (in Microsoft.Lync.Controls.dll)

## Syntax

``` vb
'Declaration
Protected Overrides Sub ClearContainerForItemOverride ( _
    element As DependencyObject, _
    item As Object _
)
'Usage
Dim element As DependencyObject
Dim item As Object

Me.ClearContainerForItemOverride(element, _
    item)
```

``` csharp
protected override void ClearContainerForItemOverride(
    DependencyObject element,
    Object item
)
```

#### Parameters

  - element  
    Type: [System.Windows.DependencyObject](http://msdn2.microsoft.com/en-us/library/ms589309)  

<!-- end list -->

  - item  
    Type: [System.Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b)  

## See also

#### Reference

[UCTreeView class](uctreeview-class-microsoft-lync-controls_1.md)

[UCTreeView members](uctreeview-members-microsoft-lync-controls_1.md)

[Microsoft.Lync.Controls namespace](microsoft-lync-controls-namespace_1.md)
