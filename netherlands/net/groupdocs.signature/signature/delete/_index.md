---
title: "Verwijderen"
second_title: "GroupDocs.Signature for .NET API-referentie"
description: "Verwijdert de meegegeven handtekening BaseSignaturegroupdocs.signature.domain/basesignature uit het document."
type: docs
weight: 110
url: /nl/net/groupdocs.signature/signature/delete/
---
## Delete(BaseSignature) {#delete}

Verwijdert de meegegeven handtekening [`BaseSignature`](../../../groupdocs.signature.domain/basesignature) uit het document.

```csharp
public bool Delete(BaseSignature signature)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| handtekening | BaseSignature | Handtekeningobject dat moet worden verwijderd uit het document. |

### Retourwaarde

Retourneert true als de bewerking succesvol was.

### Opmerkingen

**Learn more**

* More about how to delete electronic signature from document in C#: [How to delete eSignature from document with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Zie ook

* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Delete(List&lt;BaseSignature&gt;) {#delete_3}

Verwijdert de meegegeven lijst van handtekeningen [`BaseSignature`](../../../groupdocs.signature.domain/basesignature) uit het document.

```csharp
public DeleteResult Delete(List<BaseSignature> signatures)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| handtekeningen | List`1 | Lijst van handtekeningen om te verwijderen uit het document. |

### Retourwaarde

Retourneert DeleteResult [`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) met een lijst van succesvol verwijderde handtekeningen en mislukte.

### Opmerkingen

**Learn more**

* More about how to delete electronic signature from document in C#: [How to delete eSignature from document with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Zie ook

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Delete(SignatureType) {#delete_2}

Verwijdert handtekeningen van een bepaald type [`SignatureType`](../../../groupdocs.signature.domain/signaturetype) uit het document. Alleen handtekeningen die zijn toegevoegd door de Sign-methode en gemarkeerd zijn als Handtekeningen [`IsSignature`](../../../groupdocs.signature.domain/basesignature/issignature) worden verwijderd. De volgende handtekeningtypes worden ondersteund: Text, Image, Digital, Barcode, QR-Code

```csharp
public DeleteResult Delete(SignatureType signatureType)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| signatureType | SignatureType | Het type handtekeningen dat moet worden verwijderd uit het document. |

### Retourwaarde

Retourneert DeleteResult [`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) met een lijst van succesvol verwijderde handtekeningen en mislukte.

### Opmerkingen

**Learn more**

* More about how to delete electronic signature from document in C#: [How to delete eSignatures with specific type from document with GroupDocs.Signature](https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+type/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Zie ook

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Delete(List&lt;SignatureType&gt;) {#delete_4}

Verwijdert de handtekeningen van de opgegeven typenlijst [`SignatureType`](../../../groupdocs.signature.domain/signaturetype) uit het document. Alleen handtekeningen die zijn toegevoegd door de Sign-methode en gemarkeerd zijn als Handtekeningen [`IsSignature`](../../../groupdocs.signature.domain/basesignature/issignature) worden verwijderd. De volgende handtekeningtypes worden ondersteund: Text, Image, Digital, Barcode, QR-Code

```csharp
public DeleteResult Delete(List<SignatureType> signatureTypes)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| signatureTypes | List`1 | De lijst van handtekeningtypes die moeten worden verwijderd uit het document. |

### Retourwaarde

Retourneert DeleteResult [`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) met een lijst van succesvol verwijderde handtekeningen en mislukte.

### Opmerkingen

**Learn more**

* More about how to delete electronic signature from document in C#: [How to delete eSignatures with specific type from document with GroupDocs.Signature](https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+types/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Zie ook

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Delete(string) {#delete_1}

Verwijdert een handtekening op basis van zijn specifieke handtekening‑Id uit het document.

```csharp
public bool Delete(string signatureId)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| signatureId | String | De Id van de handtekening die uit het document moet worden verwijderd. |

### Retourwaarde

Retourneert true als de bewerking succesvol was.

### Opmerkingen

**Learn more**

* More about how to delete electronic signature from document in C#: [How to delete eSignature from document with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Zie ook

* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Delete(List&lt;string&gt;) {#delete_5}

Verwijdert de meegegeven lijst van handtekeningen [`BaseSignature`](../../../groupdocs.signature.domain/basesignature) uit het document.

```csharp
public DeleteResult Delete(List<string> signatureIds)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| signatureIds | List`1 | Lijst van de identifiers van de handtekeningen die uit het document moeten worden verwijderd. |

### Retourwaarde

Retourneert DeleteResult [`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) met een lijst van succesvol verwijderde handtekeningen en mislukte.

### Opmerkingen

**Learn more**

* More about how to delete electronic signature from document in C#: [How to delete eSignature from document with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Zie ook

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
