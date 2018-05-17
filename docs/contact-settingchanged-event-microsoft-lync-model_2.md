﻿---
title: Contact.SettingChanged event (Microsoft.Lync.Model)
TOCTitle: SettingChanged event
ms:assetid: E:Microsoft.Lync.Model.Contact.SettingChanged_DI_3_UC_OCS14MrefLyncWPF
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/microsoft.lync.model.contact.settingchanged_di_3_uc_ocs14mreflyncwpf(v=office.15)
ms:contentKeyID: 48596369
ms.date: 07/28/2014
mtps_version: v=office.15
f1_keywords:
- Microsoft.Lync.Model.Contact.SettingChanged
dev_langs:
- CSharp
- JScript
- VB
- other
---

# Contact.SettingChanged event

Occurs when the value of a contact property changes.

**Namespace:**  [Microsoft.Lync.Model](microsoft-lync-model-namespace_2.md)  
**Assembly:**  Microsoft.Lync.Model (in Microsoft.Lync.Model.dll)

## Syntax

``` vb
'Declaration
Public Event SettingChanged As EventHandler(Of ContactSettingChangedEventArgs)
'Usage
Dim instance As Contact
Dim handler As EventHandler(Of ContactSettingChangedEventArgs)

AddHandler instance.SettingChanged, handler
```

``` csharp
public event EventHandler<ContactSettingChangedEventArgs> SettingChanged
```

## See also

#### Reference

[Contact class](contact-class-microsoft-lync-model_2.md)

[Contact members](contact-members-microsoft-lync-model_2.md)

[Microsoft.Lync.Model namespace](microsoft-lync-model-namespace_2.md)
