﻿---
title: ContactList.OnCreateAutomationPeer method  (Microsoft.Lync.Controls)
TOCTitle: 'OnCreateAutomationPeer method '
ms:assetid: M:Microsoft.Lync.Controls.ContactList.OnCreateAutomationPeer_DI_3_UC_OCS14MrefLyncWPF
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/microsoft.lync.controls.contactlist.oncreateautomationpeer_di_3_uc_ocs14mreflyncwpf(v=office.15)
ms:contentKeyID: 48600351
ms.date: 07/28/2014
mtps_version: v=office.15
f1_keywords:
- Microsoft.Lync.Controls.ContactList.OnCreateAutomationPeer
dev_langs:
- CSharp
- JScript
- VB
- other
---

# ContactList.OnCreateAutomationPeer method

Overrides OnCreateAutomationPeer to return the ContactListAutomationPeer object.

**Namespace:**  [Microsoft.Lync.Controls](microsoft-lync-controls-namespace_1.md)  
**Assembly:**  Microsoft.Lync.Controls (in Microsoft.Lync.Controls.dll)

## Syntax

``` vb
'Declaration
Protected Overrides Function OnCreateAutomationPeer As AutomationPeer
'Usage
Dim returnValue As AutomationPeer

returnValue = Me.OnCreateAutomationPeer()
```

``` csharp
protected override AutomationPeer OnCreateAutomationPeer()
```

#### Return value

Type: [System.Windows.Automation.Peers.AutomationPeer](http://msdn2.microsoft.com/en-us/library/ms523415)  

## See also

#### Reference

[ContactList class](contactlist-class-microsoft-lync-controls_1.md)

[ContactList members](contactlist-members-microsoft-lync-controls_1.md)

[Microsoft.Lync.Controls namespace](microsoft-lync-controls-namespace_1.md)
