﻿---
title: ClientNotFoundException constructor  (Microsoft.Lync.Model)
TOCTitle: 'ClientNotFoundException constructor '
ms:assetid: M:Microsoft.Lync.Model.ClientNotFoundException.#ctor(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext)_DI_3_UC_OCS14MrefLyncWPF
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/microsoft.lync.model.clientnotfoundexception.clientnotfoundexception(v=office.15)
ms:contentKeyID: 48599415
ms.date: 07/28/2014
mtps_version: v=office.15
f1_keywords:
- Microsoft.Lync.Model.ClientNotFoundException.ClientNotFoundException
dev_langs:
- CSharp
- JScript
- VB
- other
---

# ClientNotFoundException constructor

Initializes a new instance of the HostNotFoundException class with serialized data.

**Namespace:**  [Microsoft.Lync.Model](microsoft-lync-model-namespace_2.md)  
**Assembly:**  Microsoft.Lync.Model (in Microsoft.Lync.Model.dll)

## Syntax

``` vb
'Declaration
Protected Sub New ( _
    info As SerializationInfo, _
    context As StreamingContext _
)
'Usage
Dim info As SerializationInfo
Dim context As StreamingContext

Dim instance As New ClientNotFoundException(info, context)
```

``` csharp
protected ClientNotFoundException(
    SerializationInfo info,
    StreamingContext context
)
```

#### Parameters

  - info  
    Type: [System.Runtime.Serialization.SerializationInfo](http://msdn2.microsoft.com/en-us/library/a9b6042e)  
    
    SerializationInfo object that holds the serialized object data about the exception being thrown.

<!-- end list -->

  - context  
    Type: [System.Runtime.Serialization.StreamingContext](http://msdn2.microsoft.com/en-us/library/t16abws5)  
    
    StreamingContext object that contains contextual information about the source or destination.

## See also

#### Reference

[ClientNotFoundException class](clientnotfoundexception-class-microsoft-lync-model_2.md)

[ClientNotFoundException members](clientnotfoundexception-members-microsoft-lync-model_2.md)

[Microsoft.Lync.Model namespace](microsoft-lync-model-namespace_2.md)
