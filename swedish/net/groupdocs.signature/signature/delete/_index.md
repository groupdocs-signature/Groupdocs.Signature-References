---
title: "Ta bort"
second_title: "GroupDocs.Signature för .NET API-referens"
description: "Tar bort den angivna signaturen BaseSignaturegroupdocs.signature.domain/basesignature från dokumentet."
type: docs
weight: 110
url: /sv/net/groupdocs.signature/signature/delete/
---
## Delete(BaseSignature) {#delete}

Tar bort den angivna signaturen [`BaseSignature`](../../../groupdocs.signature.domain/basesignature) från dokumentet.

```csharp
public bool Delete(BaseSignature signature)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| signatur | BaseSignature | Signaturobjekt som ska tas bort från dokumentet. |

### Returvärde

Returnerar true om operationen lyckades.

### Anmärkningar

**Learn more**

* More about how to delete electronic signature from document in C#: [How to delete eSignature from document with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Se även

* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Delete(List&lt;BaseSignature&gt;) {#delete_3}

Tar bort den angivna listan av signaturer [`BaseSignature`](../../../groupdocs.signature.domain/basesignature) från dokumentet.

```csharp
public DeleteResult Delete(List<BaseSignature> signatures)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| signaturer | List`1 | Lista över signaturer att ta bort från dokumentet. |

### Returvärde

Returnerar DeleteResult [`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) med en lista över signaturer som raderats framgångsrikt och misslyckade.

### Anmärkningar

**Learn more**

* More about how to delete electronic signature from document in C#: [How to delete eSignature from document with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Se även

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Delete(SignatureType) {#delete_2}

Tar bort signaturer av en viss typ [`SignatureType`](../../../groupdocs.signature.domain/signaturetype) från dokumentet. Endast signaturer som lagts till med Sign‑metoden och som markerats som Signaturer [`IsSignature`](../../../groupdocs.signature.domain/basesignature/issignature) kommer att tas bort. Följande signaturtyper stöds: Text, Bild, Digital, Streckkod, QR‑Kod

```csharp
public DeleteResult Delete(SignatureType signatureType)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| signatureType | SignatureType | Typen av signaturer som ska tas bort från dokumentet. |

### Returvärde

Returnerar DeleteResult [`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) med en lista över signaturer som raderats framgångsrikt och misslyckade.

### Anmärkningar

**Learn more**

* More about how to delete electronic signature from document in C#: [How to delete eSignatures with specific type from document with GroupDocs.Signature](https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+type/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Se även

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Delete(List&lt;SignatureType&gt;) {#delete_4}

Tar bort signaturerna av den angivna listan av typer [`SignatureType`](../../../groupdocs.signature.domain/signaturetype) från dokumentet. Endast signaturer som lagts till med Sign‑metoden och som markerats som Signaturer [`IsSignature`](../../../groupdocs.signature.domain/basesignature/issignature) kommer att tas bort. Följande signaturtyper stöds: Text, Bild, Digital, Streckkod, QR‑Kod

```csharp
public DeleteResult Delete(List<SignatureType> signatureTypes)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| signatureTypes | List`1 | Listan över signaturtyper som ska tas bort från dokumentet. |

### Returvärde

Returnerar DeleteResult [`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) med en lista över signaturer som raderats framgångsrikt och misslyckade.

### Anmärkningar

**Learn more**

* More about how to delete electronic signature from document in C#: [How to delete eSignatures with specific type from document with GroupDocs.Signature](https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+types/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Se även

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Delete(string) {#delete_1}

Tar bort signaturen med dess specifika signatur‑Id från dokumentet.

```csharp
public bool Delete(string signatureId)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| signatureId | Sträng | Id för signaturen som ska tas bort från dokumentet. |

### Returvärde

Returnerar true om operationen lyckades.

### Anmärkningar

**Learn more**

* More about how to delete electronic signature from document in C#: [How to delete eSignature from document with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Se även

* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Delete(List&lt;string&gt;) {#delete_5}

Tar bort den angivna listan av signaturer [`BaseSignature`](../../../groupdocs.signature.domain/basesignature) från dokumentet.

```csharp
public DeleteResult Delete(List<string> signatureIds)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| signatureIds | List`1 | Lista över identifierarna för signaturerna som ska tas bort från dokumentet. |

### Returvärde

Returnerar DeleteResult [`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) med en lista över signaturer som raderats framgångsrikt och misslyckade.

### Anmärkningar

**Learn more**

* More about how to delete electronic signature from document in C#: [How to delete eSignature from document with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Se även

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
