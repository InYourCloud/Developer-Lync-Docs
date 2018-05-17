﻿---
title: LyncClient.DelegatorClientRemoved event (Microsoft.Lync.Model)
TOCTitle: DelegatorClientRemoved event
ms:assetid: E:Microsoft.Lync.Model.LyncClient.DelegatorClientRemoved_DI_3_UC_OCS14MrefLyncWPF
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/microsoft.lync.model.lyncclient.delegatorclientremoved_di_3_uc_ocs14mreflyncwpf(v=office.15)
ms:contentKeyID: 48600276
ms.date: 07/28/2014
mtps_version: v=office.15
f1_keywords:
- Microsoft.Lync.Model.LyncClient.DelegatorClientRemoved
dev_langs:
- CSharp
- JScript
- VB
- other
---

# LyncClient.DelegatorClientRemoved event

Raised when an existing delegate endpoint is released.

**Namespace:**  [Microsoft.Lync.Model](microsoft-lync-model-namespace_2.md)  
**Assembly:**  Microsoft.Lync.Model (in Microsoft.Lync.Model.dll)

## Syntax

``` vb
'Declaration
Public Event DelegatorClientRemoved As EventHandler(Of DelegatorClientCollectionEventArgs)
'Usage
Dim instance As LyncClient
Dim handler As EventHandler(Of DelegatorClientCollectionEventArgs)

AddHandler instance.DelegatorClientRemoved, handler
```

``` csharp
public event EventHandler<DelegatorClientCollectionEventArgs> DelegatorClientRemoved
```

## See also

#### Reference

[LyncClient class](lyncclient-class-microsoft-lync-model_2.md)

[LyncClient members](lyncclient-members-microsoft-lync-model_2.md)

[Microsoft.Lync.Model namespace](microsoft-lync-model-namespace_2.md)
