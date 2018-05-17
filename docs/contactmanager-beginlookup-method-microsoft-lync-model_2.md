﻿---
title: ContactManager.BeginLookup method  (Microsoft.Lync.Model)
TOCTitle: 'BeginLookup method '
ms:assetid: M:Microsoft.Lync.Model.ContactManager.BeginLookup(System.String,System.AsyncCallback,System.Object)_DI_3_UC_OCS14MrefLyncWPF
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/microsoft.lync.model.contactmanager.beginlookup(v=office.15)
ms:contentKeyID: 48591200
ms.date: 07/28/2014
mtps_version: v=office.15
f1_keywords:
- Microsoft.Lync.Model.ContactManager.BeginLookup
dev_langs:
- CSharp
- JScript
- VB
- other
---

# ContactManager.BeginLookup method

Looks up a contact or a distribution group by entryid, sip address, email address, display name, etc..

**Namespace:**  [Microsoft.Lync.Model](microsoft-lync-model-namespace_2.md)  
**Assembly:**  Microsoft.Lync.Model (in Microsoft.Lync.Model.dll)

## Syntax

``` vb
'Declaration
Public Function BeginLookup ( _
    lookupString As String, _
    contactsAndGroupsCallback As AsyncCallback, _
    state As Object _
) As IAsyncResult
'Usage
Dim instance As ContactManager
Dim lookupString As String
Dim contactsAndGroupsCallback As AsyncCallback
Dim state As Object
Dim returnValue As IAsyncResult

returnValue = instance.BeginLookup(lookupString, _
    contactsAndGroupsCallback, state)
```

``` csharp
public IAsyncResult BeginLookup(
    string lookupString,
    AsyncCallback contactsAndGroupsCallback,
    Object state
)
```

#### Parameters

  - lookupString  
    Type: [System.String](http://msdn2.microsoft.com/en-us/library/s1wwdcbf)  

<!-- end list -->

  - contactsAndGroupsCallback  
    Type: [System.AsyncCallback](http://msdn2.microsoft.com/en-us/library/ckbe7yh5)  

<!-- end list -->

  - state  
    Type: [System.Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b)  

#### Return value

Type: [System.IAsyncResult](http://msdn2.microsoft.com/en-us/library/ft8a6455)  

## See also

#### Reference

[ContactManager class](contactmanager-class-microsoft-lync-model_2.md)

[ContactManager members](contactmanager-members-microsoft-lync-model_2.md)

[Microsoft.Lync.Model namespace](microsoft-lync-model-namespace_2.md)
