---
title: Delete
second_title: GroupDocs.Signature for .NET API Reference
description: Deletes passed signature BaseSignaturegroupdocs.signature.domain/basesignature from the document.
type: docs
weight: 110
url: /net/groupdocs.signature/signature/delete/
---
## Delete(BaseSignature) {#delete}

Deletes passed signature [`BaseSignature`](../../../groupdocs.signature.domain/basesignature) from the document.

```csharp
public bool Delete(BaseSignature signature)
```

| Parameter | Type | Description |
| --- | --- | --- |
| signature | BaseSignature | Signature object to be removed from the document. |

### Return Value

Returns true if operation was successful.

### Remarks

**Learn more**

* More about how to delete electronic signature from document in C#: [How to delete eSignature from document with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### See Also

* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Delete(List&lt;BaseSignature&gt;) {#delete_3}

Deletes passed list of signatures [`BaseSignature`](../../../groupdocs.signature.domain/basesignature) from the document.

```csharp
public DeleteResult Delete(List<BaseSignature> signatures)
```

| Parameter | Type | Description |
| --- | --- | --- |
| signatures | List`1 | List of signatures to remove from the document. |

### Return Value

Returns DeleteResult [`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.

### Remarks

**Learn more**

* More about how to delete electronic signature from document in C#: [How to delete eSignature from document with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### See Also

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Delete(SignatureType) {#delete_2}

Deletes signatures of the certain type [`SignatureType`](../../../groupdocs.signature.domain/signaturetype) from the document. Only signatures that were added by Sign method and marked as Signatures [`IsSignature`](../../../groupdocs.signature.domain/basesignature/issignature) will be removed. Following signature types are supported: Text, Image, Digital, Barcode, QR-Code

```csharp
public DeleteResult Delete(SignatureType signatureType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| signatureType | SignatureType | The type of signatures to be removed from the document. |

### Return Value

Returns DeleteResult [`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.

### Remarks

**Learn more**

* More about how to delete electronic signature from document in C#: [How to delete eSignatures with specific type from document with GroupDocs.Signature](https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+type/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### See Also

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Delete(List&lt;SignatureType&gt;) {#delete_4}

Deletes the signatures of the certain types list [`SignatureType`](../../../groupdocs.signature.domain/signaturetype) from the document. Only signatures that were added by Sign method and marked as Signatures [`IsSignature`](../../../groupdocs.signature.domain/basesignature/issignature) will be removed. Following signature types are supported: Text, Image, Digital, Barcode, QR-Code

```csharp
public DeleteResult Delete(List<SignatureType> signatureTypes)
```

| Parameter | Type | Description |
| --- | --- | --- |
| signatureTypes | List`1 | The list of signatures types to be removed from the document. |

### Return Value

Returns DeleteResult [`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.

### Remarks

**Learn more**

* More about how to delete electronic signature from document in C#: [How to delete eSignatures with specific type from document with GroupDocs.Signature](https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+types/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### See Also

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Delete(string) {#delete_1}

Deletes signature by its specific signature Id from the document.

```csharp
public bool Delete(string signatureId)
```

| Parameter | Type | Description |
| --- | --- | --- |
| signatureId | String | The Id of the signature to be removed from the document. |

### Return Value

Returns true if operation was successful.

### Remarks

**Learn more**

* More about how to delete electronic signature from document in C#: [How to delete eSignature from document with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### See Also

* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Delete(List&lt;string&gt;) {#delete_5}

Deletes passed list of signatures [`BaseSignature`](../../../groupdocs.signature.domain/basesignature) from the document.

```csharp
public DeleteResult Delete(List<string> signatureIds)
```

| Parameter | Type | Description |
| --- | --- | --- |
| signatureIds | List`1 | List of the identifiers of the signatures to be removed from the document. |

### Return Value

Returns DeleteResult [`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.

### Remarks

**Learn more**

* More about how to delete electronic signature from document in C#: [How to delete eSignature from document with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### See Also

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
