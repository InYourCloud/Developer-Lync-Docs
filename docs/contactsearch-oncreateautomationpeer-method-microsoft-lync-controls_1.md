﻿---
title: ContactSearch.OnCreateAutomationPeer method  (Microsoft.Lync.Controls)
TOCTitle: 'OnCreateAutomationPeer method '
ms:assetid: M:Microsoft.Lync.Controls.ContactSearch.OnCreateAutomationPeer_DI_3_UC_OCS14MrefLyncWPF
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/microsoft.lync.controls.contactsearch.oncreateautomationpeer_di_3_uc_ocs14mreflyncwpf(v=office.15)
ms:contentKeyID: 48594910
ms.date: 07/28/2014
mtps_version: v=office.15
f1_keywords:
- Microsoft.Lync.Controls.ContactSearch.OnCreateAutomationPeer
dev_langs:
- CSharp
- JScript
- VB
- other
---

# ContactSearch.OnCreateAutomationPeer method

Overrides the OnCreateAutomationPeer method to return the ContactSearchAutomationPeer object.

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

[ContactSearch class](contactsearch-class-microsoft-lync-controls_1.md)

[ContactSearch members](contactsearch-members-microsoft-lync-controls_1.md)

[Microsoft.Lync.Controls namespace](microsoft-lync-controls-namespace_1.md)
