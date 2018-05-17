﻿---
title: ContentSharingModality.ActivePresenterChanged event (Microsoft.Lync.Model.Conversation.Sharing)
TOCTitle: ActivePresenterChanged event
ms:assetid: E:Microsoft.Lync.Model.Conversation.Sharing.ContentSharingModality.ActivePresenterChanged_DI_3_UC_OCS14MrefLyncWPF
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/microsoft.lync.model.conversation.sharing.contentsharingmodality.activepresenterchanged_di_3_uc_ocs14mreflyncwpf(v=office.15)
ms:contentKeyID: 48589959
ms.date: 07/28/2014
mtps_version: v=office.15
f1_keywords:
- Microsoft.Lync.Model.Conversation.Sharing.ContentSharingModality.ActivePresenterChanged
dev_langs:
- CSharp
- JScript
- VB
- other
---

# ContentSharingModality.ActivePresenterChanged event

Raised when the active presenter is changed

**Namespace:**  [Microsoft.Lync.Model.Conversation.Sharing](microsoft-lync-model-conversation-sharing-namespace_2.md)  
**Assembly:**  Microsoft.Lync.Model (in Microsoft.Lync.Model.dll)

## Syntax

``` vb
'Declaration
Public Event ActivePresenterChanged As EventHandler(Of ActivePresenterChangedEventArgs)
'Usage
Dim instance As ContentSharingModality
Dim handler As EventHandler(Of ActivePresenterChangedEventArgs)

AddHandler instance.ActivePresenterChanged, handler
```

``` csharp
public event EventHandler<ActivePresenterChangedEventArgs> ActivePresenterChanged
```

## Remarks

The active presenter is changed when the the shared content of one conversation participant is swapped for the shared content of a different conversation participant.

## See also

#### Reference

[ContentSharingModality class](contentsharingmodality-class-microsoft-lync-model-conversation-sharing_2.md)

[ContentSharingModality members](contentsharingmodality-members-microsoft-lync-model-conversation-sharing_2.md)

[Microsoft.Lync.Model.Conversation.Sharing namespace](microsoft-lync-model-conversation-sharing-namespace_2.md)
