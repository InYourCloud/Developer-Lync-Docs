﻿---
title: Modality.EndConsultativeTransfer method  (Microsoft.Lync.Model.Conversation)
TOCTitle: 'EndConsultativeTransfer method '
ms:assetid: M:Microsoft.Lync.Model.Conversation.Modality.EndConsultativeTransfer(Microsoft.Lync.Model.Conversation.ModalityState@,System.Collections.Generic.IList{System.String}@,System.IAsyncResult)_DI_3_UC_OCS14MrefLyncWPF
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/microsoft.lync.model.conversation.modality.endconsultativetransfer(v=office.15)
ms:contentKeyID: 48601843
ms.date: 07/28/2014
mtps_version: v=office.15
f1_keywords:
- Microsoft.Lync.Model.Conversation.Modality.EndConsultativeTransfer
dev_langs:
- CSharp
- JScript
- VB
- other
---

# Modality.EndConsultativeTransfer method

Transfers a connected modality to an existing conversation.

**Namespace:**  [Microsoft.Lync.Model.Conversation](microsoft-lync-model-conversation-namespace_2.md)  
**Assembly:**  Microsoft.Lync.Model (in Microsoft.Lync.Model.dll)

## Syntax

``` vb
'Declaration
Public Sub EndConsultativeTransfer ( _
    <OutAttribute> ByRef targetState As ModalityState, _
    <OutAttribute> ByRef contextProperties As IList(Of String), _
    asyncResult As IAsyncResult _
)
'Usage
Dim instance As Modality
Dim targetState As ModalityState
Dim contextProperties As IList(Of String)
Dim asyncResult As IAsyncResult

instance.EndConsultativeTransfer(targetState, _
    contextProperties, asyncResult)
```

``` csharp
public void EndConsultativeTransfer(
    out ModalityState targetState,
    out IList<string> contextProperties,
    IAsyncResult asyncResult
)
```

#### Parameters

  - targetState  
    Type: [Microsoft.Lync.Model.Conversation.ModalityState](modalitystate-enumeration-microsoft-lync-model-conversation_2.md)  

<!-- end list -->

  - contextProperties  
    Type: [System.Collections.Generic.IList](http://msdn2.microsoft.com/en-us/library/5y536ey6)\<[String](http://msdn2.microsoft.com/en-us/library/s1wwdcbf)\>  

<!-- end list -->

  - asyncResult  
    Type: [System.IAsyncResult](http://msdn2.microsoft.com/en-us/library/ft8a6455)  

## See also

#### Reference

[Modality class](modality-class-microsoft-lync-model-conversation_2.md)

[Modality members](modality-members-microsoft-lync-model-conversation_2.md)

[Microsoft.Lync.Model.Conversation namespace](microsoft-lync-model-conversation-namespace_2.md)
