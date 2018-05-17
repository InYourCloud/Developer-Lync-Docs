﻿---
title: Participant.Properties property  (Microsoft.Lync.Model.Conversation)
TOCTitle: 'Properties property '
ms:assetid: P:Microsoft.Lync.Model.Conversation.Participant.Properties_DI_3_UC_OCS14MrefLyncWPF
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/microsoft.lync.model.conversation.participant.properties_di_3_uc_ocs14mreflyncwpf(v=office.15)
ms:contentKeyID: 48600240
ms.date: 07/28/2014
mtps_version: v=office.15
f1_keywords:
- Microsoft.Lync.Model.Conversation.Participant.Properties
dev_langs:
- CSharp
- JScript
- VB
- other
---

# Participant.Properties property

Gets a collection of participant properties.

**Namespace:**  [Microsoft.Lync.Model.Conversation](microsoft-lync-model-conversation-namespace_2.md)  
**Assembly:**  Microsoft.Lync.Model (in Microsoft.Lync.Model.dll)

## Syntax

``` vb
'Declaration
Public ReadOnly Property Properties As IDictionary(Of ParticipantProperty, Object)
    Get
'Usage
Dim instance As Participant
Dim value As IDictionary(Of ParticipantProperty, Object)

value = instance.Properties
```

``` csharp
public IDictionary<ParticipantProperty, Object> Properties { get; }
```

#### Property value

Type: [System.Collections.Generic.IDictionary](http://msdn2.microsoft.com/en-us/library/s4ys34ea)\<[ParticipantProperty](participantproperty-enumeration-microsoft-lync-model-conversation_2.md), [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b)\>  

## See also

#### Reference

[Participant class](participant-class-microsoft-lync-model-conversation_2.md)

[Participant members](participant-members-microsoft-lync-model-conversation_2.md)

[Microsoft.Lync.Model.Conversation namespace](microsoft-lync-model-conversation-namespace_2.md)
