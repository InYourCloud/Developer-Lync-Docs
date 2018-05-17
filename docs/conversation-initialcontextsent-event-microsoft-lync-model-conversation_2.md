﻿---
title: Conversation.InitialContextSent event (Microsoft.Lync.Model.Conversation)
TOCTitle: InitialContextSent event
ms:assetid: E:Microsoft.Lync.Model.Conversation.Conversation.InitialContextSent_DI_3_UC_OCS14MrefLyncWPF
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/microsoft.lync.model.conversation.conversation.initialcontextsent_di_3_uc_ocs14mreflyncwpf(v=office.15)
ms:contentKeyID: 48588622
ms.date: 07/28/2014
mtps_version: v=office.15
f1_keywords:
- Microsoft.Lync.Model.Conversation.Conversation.InitialContextSent
dev_langs:
- CSharp
- JScript
- VB
- other
---

# Conversation.InitialContextSent event

Raised to notify of the 3rd party applications of outgoing calls .

**Namespace:**  [Microsoft.Lync.Model.Conversation](microsoft-lync-model-conversation-namespace_2.md)  
**Assembly:**  Microsoft.Lync.Model (in Microsoft.Lync.Model.dll)

## Syntax

``` vb
'Declaration
Public Event InitialContextSent As EventHandler(Of InitialContextEventArgs)
'Usage
Dim instance As Conversation
Dim handler As EventHandler(Of InitialContextEventArgs)

AddHandler instance.InitialContextSent, handler
```

``` csharp
public event EventHandler<InitialContextEventArgs> InitialContextSent
```

## See also

#### Reference

[Conversation class](conversation-class-microsoft-lync-model-conversation_2.md)

[Conversation members](conversation-members-microsoft-lync-model-conversation_2.md)

[Microsoft.Lync.Model.Conversation namespace](microsoft-lync-model-conversation-namespace_2.md)
