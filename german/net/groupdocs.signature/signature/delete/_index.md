---
title: "Löschen"
second_title: "GroupDocs.Signature für .NET API-Referenz"
description: "Löscht übergebene Signatur BaseSignaturegroupdocs.signature.domain/basesignature aus dem Dokument."
type: docs
weight: 110
url: /de/net/groupdocs.signature/signature/delete/
---
## Delete(BaseSignature) {#delete}

Löscht übergebene Signatur [`BaseSignature`](../../../groupdocs.signature.domain/basesignature) aus dem Dokument.

```csharp
public bool Delete(BaseSignature signature)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Signatur | BaseSignature | Signaturobjekt, das aus dem Dokument entfernt werden soll. |

### Rückgabewert

Gibt true zurück, wenn die Operation erfolgreich war.

### Hinweise

**Learn more**

* More about how to delete electronic signature from document in C#: [How to delete eSignature from document with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Siehe auch

* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Delete(List&lt;BaseSignature&gt;) {#delete_3}

Löscht übergebene Liste von Signaturen [`BaseSignature`](../../../groupdocs.signature.domain/basesignature) aus dem Dokument.

```csharp
public DeleteResult Delete(List<BaseSignature> signatures)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Signaturen | List`1 | Liste der Signaturen, die aus dem Dokument entfernt werden sollen. |

### Rückgabewert

Gibt DeleteResult [`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) mit einer Liste erfolgreich gelöschter Signaturen und fehlgeschlagener zurück.

### Hinweise

**Learn more**

* More about how to delete electronic signature from document in C#: [How to delete eSignature from document with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Siehe auch

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Delete(SignatureType) {#delete_2}

Löscht Signaturen eines bestimmten Typs [`SignatureType`](../../../groupdocs.signature.domain/signaturetype) aus dem Dokument. Nur Signaturen, die mit der Sign-Methode hinzugefügt und als Signaturen [`IsSignature`](../../../groupdocs.signature.domain/basesignature/issignature) markiert wurden, werden entfernt. Die folgenden Signaturtypen werden unterstützt: Text, Bild, Digital, Barcode, QR-Code

```csharp
public DeleteResult Delete(SignatureType signatureType)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| signatureType | SignatureType | Der Typ der Signaturen, die aus dem Dokument entfernt werden sollen. |

### Rückgabewert

Gibt DeleteResult [`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) mit einer Liste erfolgreich gelöschter Signaturen und fehlgeschlagener zurück.

### Hinweise

**Learn more**

* More about how to delete electronic signature from document in C#: [How to delete eSignatures with specific type from document with GroupDocs.Signature](https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+type/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Siehe auch

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Delete(List&lt;SignatureType&gt;) {#delete_4}

Löscht die Signaturen einer bestimmten Typenliste [`SignatureType`](../../../groupdocs.signature.domain/signaturetype) aus dem Dokument. Nur Signaturen, die mit der Sign-Methode hinzugefügt und als Signaturen [`IsSignature`](../../../groupdocs.signature.domain/basesignature/issignature) markiert wurden, werden entfernt. Die folgenden Signaturtypen werden unterstützt: Text, Bild, Digital, Barcode, QR-Code

```csharp
public DeleteResult Delete(List<SignatureType> signatureTypes)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| signatureTypes | List`1 | Die Liste der Signaturtypen, die aus dem Dokument entfernt werden sollen. |

### Rückgabewert

Gibt DeleteResult [`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) mit einer Liste erfolgreich gelöschter Signaturen und fehlgeschlagener zurück.

### Hinweise

**Learn more**

* More about how to delete electronic signature from document in C#: [How to delete eSignatures with specific type from document with GroupDocs.Signature](https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+types/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Siehe auch

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Delete(string) {#delete_1}

Löscht die Signatur anhand ihrer spezifischen Signatur‑Id aus dem Dokument.

```csharp
public bool Delete(string signatureId)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| signatureId | String | Die Id der Signatur, die aus dem Dokument entfernt werden soll. |

### Rückgabewert

Gibt true zurück, wenn die Operation erfolgreich war.

### Hinweise

**Learn more**

* More about how to delete electronic signature from document in C#: [How to delete eSignature from document with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Siehe auch

* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Delete(List&lt;string&gt;) {#delete_5}

Löscht übergebene Liste von Signaturen [`BaseSignature`](../../../groupdocs.signature.domain/basesignature) aus dem Dokument.

```csharp
public DeleteResult Delete(List<string> signatureIds)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| signatureIds | List`1 | Liste der Kennungen der Signaturen, die aus dem Dokument entfernt werden sollen. |

### Rückgabewert

Gibt DeleteResult [`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) mit einer Liste erfolgreich gelöschter Signaturen und fehlgeschlagener zurück.

### Hinweise

**Learn more**

* More about how to delete electronic signature from document in C#: [How to delete eSignature from document with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Siehe auch

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
