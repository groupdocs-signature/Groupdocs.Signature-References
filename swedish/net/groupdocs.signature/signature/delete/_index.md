---
title: Delete
second_title: GroupDocs.Signature för .NET API-referens
description: Tar bort godkänd signaturBaseSignaturegroupdocs.signature.domain/basesignature från dokumentet.
type: docs
weight: 110
url: /sv/net/groupdocs.signature/signature/delete/
---
## Delete(BaseSignature) {#delete}

Tar bort godkänd signatur[`BaseSignature`](../../../groupdocs.signature.domain/basesignature) från dokumentet.

```csharp
public bool Delete(BaseSignature signature)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| signature | BaseSignature | Signaturobjekt som ska tas bort från dokumentet. |

### Returvärde

Returnerar sant om åtgärden lyckades.

### Anmärkningar

**Läs mer**

* Mer om hur man tar bort elektronisk signatur från dokument i C#: [Hur man tar bort eSignature från dokument med GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Avancerade användningsfall för att ta bort dokument e-signaturer: [Hur man tar bort olika typer av e-signaturer från dokument i C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Se även

* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namnutrymme [GroupDocs.Signature](../../signature)
* hopsättning [GroupDocs.Signature](../../../)

---

## Delete(List&lt;BaseSignature&gt;) {#delete_3}

Tar bort godkänd lista med signaturer[`BaseSignature`](../../../groupdocs.signature.domain/basesignature) från dokumentet.

```csharp
public DeleteResult Delete(List<BaseSignature> signatures)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| signatures | List`1 | Lista över signaturer att ta bort från dokumentet. |

### Returvärde

Returnerar DeleteResult[`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) med lista över framgångsrika borttagna signaturer och misslyckade.

### Anmärkningar

**Läs mer**

* Mer om hur man tar bort elektronisk signatur från dokument i C#: [Hur man tar bort eSignature från dokument med GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Avancerade användningsfall för att ta bort dokument e-signaturer: [Hur man tar bort olika typer av e-signaturer från dokument i C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Se även

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namnutrymme [GroupDocs.Signature](../../signature)
* hopsättning [GroupDocs.Signature](../../../)

---

## Delete(SignatureType) {#delete_2}

Tar bort signaturer av en viss typ[`SignatureType`](../../../groupdocs.signature.domain/signaturetype) från dokumentet. Endast signaturer som lagts till med Sign-metoden och markerade som Signaturer[`IsSignature`](../../../groupdocs.signature.domain/basesignature/issignature) kommer att tas bort. Följande signaturtyper stöds: Text, Bild, Digital, Streckkod, QR-Code

```csharp
public DeleteResult Delete(SignatureType signatureType)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| signatureType | SignatureType | Typen av signaturer som ska tas bort från dokumentet. |

### Returvärde

Returnerar DeleteResult[`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) med lista över framgångsrika borttagna signaturer och misslyckade.

### Anmärkningar

**Läs mer**

* Mer om hur man tar bort elektronisk signatur från dokument i C#: [Hur man tar bort eSignaturer med specifik typ från dokument med GroupDocs.Signature](https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+type/)
* Avancerade användningsfall för att ta bort dokument e-signaturer: [Hur man tar bort olika typer av e-signaturer från dokument i C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Se även

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [Signature](../../signature)
* namnutrymme [GroupDocs.Signature](../../signature)
* hopsättning [GroupDocs.Signature](../../../)

---

## Delete(List&lt;SignatureType&gt;) {#delete_4}

Tar bort signaturerna för listan med vissa typer[`SignatureType`](../../../groupdocs.signature.domain/signaturetype) från dokumentet. Endast signaturer som lagts till med Sign-metoden och markerade som Signaturer[`IsSignature`](../../../groupdocs.signature.domain/basesignature/issignature) kommer att tas bort. Följande signaturtyper stöds: Text, Bild, Digital, Streckkod, QR-Code

```csharp
public DeleteResult Delete(List<SignatureType> signatureTypes)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| signatureTypes | List`1 | Listan över signaturtyper som ska tas bort från dokumentet. |

### Returvärde

Returnerar DeleteResult[`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) med lista över framgångsrika borttagna signaturer och misslyckade.

### Anmärkningar

**Läs mer**

* Mer om hur man tar bort elektronisk signatur från dokument i C#: [Hur man tar bort eSignaturer med specifik typ från dokument med GroupDocs.Signature](https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+types/)
* Avancerade användningsfall för att ta bort dokument e-signaturer: [Hur man tar bort olika typer av e-signaturer från dokument i C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Se även

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [Signature](../../signature)
* namnutrymme [GroupDocs.Signature](../../signature)
* hopsättning [GroupDocs.Signature](../../../)

---

## Delete(string) {#delete_1}

Tar bort signatur med dess specifika signatur-ID från dokumentet.

```csharp
public bool Delete(string signatureId)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| signatureId | String | Id för signaturen som ska tas bort från dokumentet. |

### Returvärde

Returnerar sant om åtgärden lyckades.

### Anmärkningar

**Läs mer**

* Mer om hur man tar bort elektronisk signatur från dokument i C#: [Hur man tar bort eSignature från dokument med GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Avancerade användningsfall för att ta bort dokument e-signaturer: [Hur man tar bort olika typer av e-signaturer från dokument i C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Se även

* class [Signature](../../signature)
* namnutrymme [GroupDocs.Signature](../../signature)
* hopsättning [GroupDocs.Signature](../../../)

---

## Delete(List&lt;string&gt;) {#delete_5}

Tar bort godkänd lista med signaturer[`BaseSignature`](../../../groupdocs.signature.domain/basesignature) från dokumentet.

```csharp
public DeleteResult Delete(List<string> signatureIds)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| signatureIds | List`1 | Lista över identifierarna för de signaturer som ska tas bort från dokumentet. |

### Returvärde

Returnerar DeleteResult[`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) med lista över framgångsrika borttagna signaturer och misslyckade.

### Anmärkningar

**Läs mer**

* Mer om hur man tar bort elektronisk signatur från dokument i C#: [Hur man tar bort eSignature från dokument med GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Avancerade användningsfall för att ta bort dokument e-signaturer: [Hur man tar bort olika typer av e-signaturer från dokument i C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Se även

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* class [Signature](../../signature)
* namnutrymme [GroupDocs.Signature](../../signature)
* hopsättning [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
