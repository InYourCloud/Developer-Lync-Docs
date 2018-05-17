﻿---
title: InstantMessageModality members (Microsoft.Lync.Model.Conversation)
TOCTitle: InstantMessageModality members
ms:assetid: AllMembers.T:Microsoft.Lync.Model.Conversation.InstantMessageModality_DI_3_UC_OCS14MrefLyncWPF
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/microsoft.lync.model.conversation.instantmessagemodality_di_3_uc_ocs14mreflyncwpf_members(v=office.15)
ms:contentKeyID: 48597550
ms.date: 07/28/2014
mtps_version: v=office.15
---

# InstantMessageModality members

Include protected members  
Include inherited members  

Defines the instant messaging modality. It supports actions such as sending an instant message, checking or setting the composing (typing) flag, etc. This class exposes events such as messages being sent or received.

The [InstantMessageModality](instantmessagemodality-class-microsoft-lync-model-conversation_2.md) type exposes the following members.

## Properties

<table>
<thead>
<tr class="header">
<th> </th>
<th>Name</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><img src="images/JJ275421.pubproperty(Office.15).gif" title="Public property" alt="Public property" /></td>
<td><a href="instantmessagemodality-capabilities-property-microsoft-lync-model-conversation_2.md">Capabilities</a></td>
<td>Gets instant messaging Capabilities.</td>
</tr>
<tr class="even">
<td><img src="images/JJ275421.pubproperty(Office.15).gif" title="Public property" alt="Public property" /></td>
<td><a href="modality-conversation-property-microsoft-lync-model-conversation_2.md">Conversation</a></td>
<td>Gets the associated conversation object. (Inherited from <a href="modality-class-microsoft-lync-model-conversation_2.md">Modality</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/JJ275421.pubproperty(Office.15).gif" title="Public property" alt="Public property" /></td>
<td><a href="modality-endpoint-property-microsoft-lync-model-conversation_2.md">Endpoint</a></td>
<td>Gets the collaboration endpoint that is used by the modality. (Inherited from <a href="modality-class-microsoft-lync-model-conversation_2.md">Modality</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/JJ275421.pubproperty(Office.15).gif" title="Public property" alt="Public property" /></td>
<td><a href="instantmessagemodality-istyping-property-microsoft-lync-model-conversation_2.md">IsTyping</a></td>
<td>Gets a flag indicating whether the endpoint is composing a message.</td>
</tr>
<tr class="odd">
<td><img src="images/JJ275421.pubproperty(Office.15).gif" title="Public property" alt="Public property" /></td>
<td><a href="modality-participant-property-microsoft-lync-model-conversation_2.md">Participant</a></td>
<td>Gets the associated participant object. (Inherited from <a href="modality-class-microsoft-lync-model-conversation_2.md">Modality</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/JJ275421.pubproperty(Office.15).gif" title="Public property" alt="Public property" /></td>
<td><a href="modality-properties-property-microsoft-lync-model-conversation_2.md">Properties</a></td>
<td>Gets a collection of modality properties. (Inherited from <a href="modality-class-microsoft-lync-model-conversation_2.md">Modality</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/JJ275421.pubproperty(Office.15).gif" title="Public property" alt="Public property" /></td>
<td><a href="modality-state-property-microsoft-lync-model-conversation_2.md">State</a></td>
<td>Gets the modality state. (Inherited from <a href="modality-class-microsoft-lync-model-conversation_2.md">Modality</a>.)</td>
</tr>
</tbody>
</table>


Top

## Methods

<table>
<thead>
<tr class="header">
<th> </th>
<th>Name</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><img src="images/Hh347903.pubmethod(Office.15).gif" title="Public method" alt="Public method" /></td>
<td><a href="modality-accept-method-microsoft-lync-model-conversation_2.md">Accept</a></td>
<td>Accept an offer for the modality. (Inherited from <a href="modality-class-microsoft-lync-model-conversation_2.md">Modality</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Hh347903.pubmethod(Office.15).gif" title="Public method" alt="Public method" /></td>
<td><a href="modality-beginconnect-method-microsoft-lync-model-conversation_2.md">BeginConnect</a></td>
<td>Activates a conversation modality by connecting the modality to its associated local and remote endpoints. (Inherited from <a href="modality-class-microsoft-lync-model-conversation_2.md">Modality</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Hh347903.pubmethod(Office.15).gif" title="Public method" alt="Public method" /></td>
<td><a href="modality-beginconsultativetransfer-method-microsoft-lync-model-conversation_2.md">BeginConsultativeTransfer</a></td>
<td>Transfers a connected modality to an existing conversation. (Inherited from <a href="modality-class-microsoft-lync-model-conversation_2.md">Modality</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Hh347903.pubmethod(Office.15).gif" title="Public method" alt="Public method" /></td>
<td><a href="modality-begindisconnect-method-microsoft-lync-model-conversation_2.md">BeginDisconnect</a></td>
<td>Disconnects from the modality. (Inherited from <a href="modality-class-microsoft-lync-model-conversation_2.md">Modality</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Hh347903.pubmethod(Office.15).gif" title="Public method" alt="Public method" /></td>
<td><a href="modality-beginforward-method-contact-asynccallback-object-microsoft-lync-model-conversation_2.md">BeginForward(Contact, AsyncCallback, Object)</a></td>
<td>Forwards an active conversation (in ringing state) to a specified remote contact endpoint. You cannot forward conversations between the local contacts endpoints. (Inherited from <a href="modality-class-microsoft-lync-model-conversation_2.md">Modality</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Hh347903.pubmethod(Office.15).gif" title="Public method" alt="Public method" /></td>
<td><a href="modality-beginforward-method-contactendpoint-asynccallback-object-microsoft-lync-model-conversation_2.md">BeginForward(ContactEndpoint, AsyncCallback, Object)</a></td>
<td>Forwards an active conversation to a specified remote contact endpoint. You cannot forward conversations between the local contacts endpoints. (Inherited from <a href="modality-class-microsoft-lync-model-conversation_2.md">Modality</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Hh347903.pubmethod(Office.15).gif" title="Public method" alt="Public method" /></td>
<td><a href="modality-beginhold-method-microsoft-lync-model-conversation_2.md">BeginHold</a></td>
<td>Places the modality on hold. (Inherited from <a href="modality-class-microsoft-lync-model-conversation_2.md">Modality</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Hh347903.pubmethod(Office.15).gif" title="Public method" alt="Public method" /></td>
<td><a href="modality-beginretrieve-method-microsoft-lync-model-conversation_2.md">BeginRetrieve</a></td>
<td>Retrives a held modality. (Inherited from <a href="modality-class-microsoft-lync-model-conversation_2.md">Modality</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Hh347903.pubmethod(Office.15).gif" title="Public method" alt="Public method" /></td>
<td><a href="instantmessagemodality-beginsendmessage-method-string-asynccallback-object-microsoft-lync-model-conversation_2.md">BeginSendMessage(String, AsyncCallback, Object)</a></td>
<td>Sends a plain text message to a remote conversation participant.</td>
</tr>
<tr class="even">
<td><img src="images/Hh347903.pubmethod(Office.15).gif" title="Public method" alt="Public method" /></td>
<td><a href="instantmessagemodality-beginsendmessage-method-idictionary-instantmessagecontenttype-string-asynccallback-object-microsoft-lync-model-conversation_2.md">BeginSendMessage(IDictionary&lt;InstantMessageContentType, String&gt;, AsyncCallback, Object)</a></td>
<td>Sends a text message formatted for specified content type to a remote conversation participant.</td>
</tr>
<tr class="odd">
<td><img src="images/Hh347903.pubmethod(Office.15).gif" title="Public method" alt="Public method" /></td>
<td><a href="instantmessagemodality-beginsetcomposing-method-microsoft-lync-model-conversation_2.md">BeginSetComposing</a></td>
<td>Sets the local composing state. The composing flag indicates that the local participant is typing a message.</td>
</tr>
<tr class="even">
<td><img src="images/Hh347903.pubmethod(Office.15).gif" title="Public method" alt="Public method" /></td>
<td><a href="modality-beginsetproperty-method-microsoft-lync-model-conversation_2.md">BeginSetProperty</a></td>
<td>Sets a property associated with this modality. (Inherited from <a href="modality-class-microsoft-lync-model-conversation_2.md">Modality</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Hh347903.pubmethod(Office.15).gif" title="Public method" alt="Public method" /></td>
<td><a href="modality-begintransfer-method-contact-transferoptions-asynccallback-object-microsoft-lync-model-conversation_2.md">BeginTransfer(Contact, TransferOptions, AsyncCallback, Object)</a></td>
<td>Transfers an active conversation to a specified remote contact. (Inherited from <a href="modality-class-microsoft-lync-model-conversation_2.md">Modality</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Hh347903.pubmethod(Office.15).gif" title="Public method" alt="Public method" /></td>
<td><a href="modality-begintransfer-method-contactendpoint-transferoptions-asynccallback-object-microsoft-lync-model-conversation_2.md">BeginTransfer(ContactEndpoint, TransferOptions, AsyncCallback, Object)</a></td>
<td>Transfer an active conversation to a specified remote contact endpoint. You cannot transfer a conversation to another local contact endpoint. (Inherited from <a href="modality-class-microsoft-lync-model-conversation_2.md">Modality</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Hh347903.pubmethod(Office.15).gif" title="Public method" alt="Public method" /></td>
<td><a href="modality-caninvoke-method-microsoft-lync-model-conversation_2.md">CanInvoke</a></td>
<td>Returns a flag indicating whether a specific action is available. (Inherited from <a href="modality-class-microsoft-lync-model-conversation_2.md">Modality</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Hh347903.pubmethod(Office.15).gif" title="Public method" alt="Public method" /></td>
<td><a href="modality-cansetproperty-method-microsoft-lync-model-conversation_2.md">CanSetProperty</a></td>
<td>Test whether the property can be set to the modality. (Inherited from <a href="modality-class-microsoft-lync-model-conversation_2.md">Modality</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Hh347903.pubmethod(Office.15).gif" title="Public method" alt="Public method" /></td>
<td><a href="http://msdn2.microsoft.com/en-us/library/2ch65xad">CreateObjRef</a></td>
<td>(Inherited from <a href="http://msdn2.microsoft.com/en-us/library/w4302s1f">MarshalByRefObject</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Hh347903.pubmethod(Office.15).gif" title="Public method" alt="Public method" /></td>
<td><a href="modality-endconnect-method-microsoft-lync-model-conversation_2.md">EndConnect</a></td>
<td>Connects to the modality. (Inherited from <a href="modality-class-microsoft-lync-model-conversation_2.md">Modality</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Hh347903.pubmethod(Office.15).gif" title="Public method" alt="Public method" /></td>
<td><a href="modality-endconsultativetransfer-method-microsoft-lync-model-conversation_2.md">EndConsultativeTransfer</a></td>
<td>Transfers a connected modality to an existing conversation. (Inherited from <a href="modality-class-microsoft-lync-model-conversation_2.md">Modality</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Hh347903.pubmethod(Office.15).gif" title="Public method" alt="Public method" /></td>
<td><a href="modality-enddisconnect-method-microsoft-lync-model-conversation_2.md">EndDisconnect</a></td>
<td>Disconnects from the modality. (Inherited from <a href="modality-class-microsoft-lync-model-conversation_2.md">Modality</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Hh347903.pubmethod(Office.15).gif" title="Public method" alt="Public method" /></td>
<td><a href="modality-endforward-method-microsoft-lync-model-conversation_2.md">EndForward</a></td>
<td>Forwards a connecting incoming modality to a different location. (Inherited from <a href="modality-class-microsoft-lync-model-conversation_2.md">Modality</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Hh347903.pubmethod(Office.15).gif" title="Public method" alt="Public method" /></td>
<td><a href="modality-endhold-method-microsoft-lync-model-conversation_2.md">EndHold</a></td>
<td>Places the modality on hold. (Inherited from <a href="modality-class-microsoft-lync-model-conversation_2.md">Modality</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Hh347903.pubmethod(Office.15).gif" title="Public method" alt="Public method" /></td>
<td><a href="modality-endretrieve-method-microsoft-lync-model-conversation_2.md">EndRetrieve</a></td>
<td>Retrives a held modality. (Inherited from <a href="modality-class-microsoft-lync-model-conversation_2.md">Modality</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Hh347903.pubmethod(Office.15).gif" title="Public method" alt="Public method" /></td>
<td><a href="instantmessagemodality-endsendmessage-method-microsoft-lync-model-conversation_2.md">EndSendMessage</a></td>
<td>Ends send message operation and un-blocks program execution on calling thread.</td>
</tr>
<tr class="odd">
<td><img src="images/Hh347903.pubmethod(Office.15).gif" title="Public method" alt="Public method" /></td>
<td><a href="instantmessagemodality-endsetcomposing-method-microsoft-lync-model-conversation_2.md">EndSetComposing</a></td>
<td>Sets the local composing state. The composing flag indicates that the local participant is typing a message.</td>
</tr>
<tr class="even">
<td><img src="images/Hh347903.pubmethod(Office.15).gif" title="Public method" alt="Public method" /></td>
<td><a href="modality-endsetproperty-method-microsoft-lync-model-conversation_2.md">EndSetProperty</a></td>
<td>Sets a property associated with this modality. (Inherited from <a href="modality-class-microsoft-lync-model-conversation_2.md">Modality</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Hh347903.pubmethod(Office.15).gif" title="Public method" alt="Public method" /></td>
<td><a href="modality-endtransfer-method-microsoft-lync-model-conversation_2.md">EndTransfer</a></td>
<td>Transfers a connected modality to a different location. (Inherited from <a href="modality-class-microsoft-lync-model-conversation_2.md">Modality</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Hh347903.pubmethod(Office.15).gif" title="Public method" alt="Public method" /></td>
<td><a href="http://msdn2.microsoft.com/en-us/library/bsc2ak47">Equals</a></td>
<td>(Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Hh347903.protmethod(Office.15).gif" title="Protected method" alt="Protected method" /></td>
<td><a href="instantmessagemodality-finalize-method-microsoft-lync-model-conversation_1.md">Finalize</a></td>
<td>(Overrides <a href="modality-finalize-method-microsoft-lync-model-conversation_1.md">Modality.Finalize()</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Hh347903.pubmethod(Office.15).gif" title="Public method" alt="Public method" /></td>
<td><a href="http://msdn2.microsoft.com/en-us/library/zdee4b3y">GetHashCode</a></td>
<td>(Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Hh347903.pubmethod(Office.15).gif" title="Public method" alt="Public method" /></td>
<td><a href="http://msdn2.microsoft.com/en-us/library/c6y7316f">GetLifetimeService</a></td>
<td>(Inherited from <a href="http://msdn2.microsoft.com/en-us/library/w4302s1f">MarshalByRefObject</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Hh347903.pubmethod(Office.15).gif" title="Public method" alt="Public method" /></td>
<td><a href="http://msdn2.microsoft.com/en-us/library/dfwy45w9">GetType</a></td>
<td>(Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Hh347903.pubmethod(Office.15).gif" title="Public method" alt="Public method" /></td>
<td><a href="http://msdn2.microsoft.com/en-us/library/zwt5tzck">InitializeLifetimeService</a></td>
<td>(Inherited from <a href="http://msdn2.microsoft.com/en-us/library/w4302s1f">MarshalByRefObject</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Hh347903.protmethod(Office.15).gif" title="Protected method" alt="Protected method" /></td>
<td><a href="http://msdn2.microsoft.com/en-us/library/57ctke0a">MemberwiseClone()</a></td>
<td>(Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Hh347903.protmethod(Office.15).gif" title="Protected method" alt="Protected method" /></td>
<td><a href="http://msdn2.microsoft.com/en-us/library/ms131262">MemberwiseClone(Boolean)</a></td>
<td>(Inherited from <a href="http://msdn2.microsoft.com/en-us/library/w4302s1f">MarshalByRefObject</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Hh347903.pubmethod(Office.15).gif" title="Public method" alt="Public method" /></td>
<td><a href="modality-reject-method-microsoft-lync-model-conversation_2.md">Reject</a></td>
<td>Reject an offer for the modality. (Inherited from <a href="modality-class-microsoft-lync-model-conversation_2.md">Modality</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Hh347903.pubmethod(Office.15).gif" title="Public method" alt="Public method" /></td>
<td><a href="instantmessagemodality-setcapabilities-method-microsoft-lync-model-conversation_2.md">SetCapabilities</a></td>
<td>Sets self instant messaging Capabilities.</td>
</tr>
<tr class="even">
<td><img src="images/Hh347903.pubmethod(Office.15).gif" title="Public method" alt="Public method" /></td>
<td><a href="http://msdn2.microsoft.com/en-us/library/7bxwbwt2">ToString</a></td>
<td>(Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
</tbody>
</table>


Top

## Events

<table>
<thead>
<tr class="header">
<th> </th>
<th>Name</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><img src="images/JJ266306.pubevent(Office.15).gif" title="Public event" alt="Public event" /></td>
<td><a href="modality-actionavailabilitychanged-event-microsoft-lync-model-conversation_2.md">ActionAvailabilityChanged</a></td>
<td>Raised when an action availability changes. (Inherited from <a href="modality-class-microsoft-lync-model-conversation_2.md">Modality</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/JJ266306.pubevent(Office.15).gif" title="Public event" alt="Public event" /></td>
<td><a href="instantmessagemodality-instantmessagepropertychanged-event-microsoft-lync-model-conversation_2.md">InstantMessagePropertyChanged</a></td>
<td>Raised when a property value changes</td>
</tr>
<tr class="odd">
<td><img src="images/JJ266306.pubevent(Office.15).gif" title="Public event" alt="Public event" /></td>
<td><a href="instantmessagemodality-instantmessagereceived-event-microsoft-lync-model-conversation_2.md">InstantMessageReceived</a></td>
<td>Raised when an instant message is received.</td>
</tr>
<tr class="even">
<td><img src="images/JJ266306.pubevent(Office.15).gif" title="Public event" alt="Public event" /></td>
<td><a href="instantmessagemodality-istypingchanged-event-microsoft-lync-model-conversation_2.md">IsTypingChanged</a></td>
<td>Raised when the istyping state changes.</td>
</tr>
<tr class="odd">
<td><img src="images/JJ266306.pubevent(Office.15).gif" title="Public event" alt="Public event" /></td>
<td><a href="modality-modalitystatechanged-event-microsoft-lync-model-conversation_2.md">ModalityStateChanged</a></td>
<td>Raised when modality state changes (Inherited from <a href="modality-class-microsoft-lync-model-conversation_2.md">Modality</a>.)</td>
</tr>
</tbody>
</table>


Top

## See also

#### Reference

[InstantMessageModality class](instantmessagemodality-class-microsoft-lync-model-conversation_2.md)

[Microsoft.Lync.Model.Conversation namespace](microsoft-lync-model-conversation-namespace_2.md)
