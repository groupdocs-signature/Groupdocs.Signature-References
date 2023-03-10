---
title: Delete
second_title: GroupDocs.Signature voor .NET API-referentie
description: Verwijdert doorgegeven handtekeningBaseSignaturegroupdocs.signature.domain/basesignature uit het document.
type: docs
weight: 110
url: /nl/net/groupdocs.signature/signature/delete/
---
## Delete(BaseSignature) {#delete}

Verwijdert doorgegeven handtekening[`BaseSignature`](../../../groupdocs.signature.domain/basesignature) uit het document.

```csharp
public bool Delete(BaseSignature signature)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| signature | BaseSignature | Handtekeningobject dat uit het document moet worden verwijderd. |

### Winstwaarde

Retourneert waar als de bewerking is geslaagd.

### Opmerkingen

**Kom meer te weten**

* Meer informatie over het verwijderen van elektronische handtekeningen uit documenten in C#: [Hoe eSignature uit een document te verwijderen met GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Geavanceerd gebruik van het verwijderen van e-handtekeningen van documenten: [Hoe verschillende soorten e-handtekeningen uit een document in C# te verwijderen](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Zie ook

* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* naamruimte [GroupDocs.Signature](../../signature)
* montage [GroupDocs.Signature](../../../)

---

## Delete(List&lt;BaseSignature&gt;) {#delete_3}

Verwijdert goedgekeurde lijst met handtekeningen[`BaseSignature`](../../../groupdocs.signature.domain/basesignature) uit het document.

```csharp
public DeleteResult Delete(List<BaseSignature> signatures)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| signatures | List`1 | Lijst met handtekeningen die uit het document moeten worden verwijderd. |

### Winstwaarde

Retourneert DeleteResult[`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) met een lijst met succesvol verwijderde en mislukte handtekeningen.

### Opmerkingen

**Kom meer te weten**

* Meer informatie over het verwijderen van elektronische handtekeningen uit documenten in C#: [Hoe eSignature uit een document te verwijderen met GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Geavanceerd gebruik van het verwijderen van e-handtekeningen van documenten: [Hoe verschillende soorten e-handtekeningen uit een document in C# te verwijderen](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Zie ook

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* naamruimte [GroupDocs.Signature](../../signature)
* montage [GroupDocs.Signature](../../../)

---

## Delete(SignatureType) {#delete_2}

Verwijdert handtekeningen van het bepaalde type[`SignatureType`](../../../groupdocs.signature.domain/signaturetype) uit het document. Alleen handtekeningen die zijn toegevoegd met de tekenmethode en zijn gemarkeerd als handtekeningen[`IsSignature`](../../../groupdocs.signature.domain/basesignature/issignature) wordt verwijderd. De volgende typen handtekeningen worden ondersteund: Tekst, Afbeelding, Digitaal, Barcode, QR-Code

```csharp
public DeleteResult Delete(SignatureType signatureType)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| signatureType | SignatureType | Het type handtekeningen dat uit het document moet worden verwijderd. |

### Winstwaarde

Retourneert DeleteResult[`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) met een lijst met succesvol verwijderde en mislukte handtekeningen.

### Opmerkingen

**Kom meer te weten**

* Meer informatie over het verwijderen van elektronische handtekeningen uit documenten in C#: [Hoe eSignatures met een specifiek type uit een document te verwijderen met GroupDocs.Signature](https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+type/)
* Geavanceerd gebruik van het verwijderen van e-handtekeningen van documenten: [Hoe verschillende soorten e-handtekeningen uit een document in C# te verwijderen](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Zie ook

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [Signature](../../signature)
* naamruimte [GroupDocs.Signature](../../signature)
* montage [GroupDocs.Signature](../../../)

---

## Delete(List&lt;SignatureType&gt;) {#delete_4}

Verwijdert de handtekeningen van de lijst met bepaalde typen[`SignatureType`](../../../groupdocs.signature.domain/signaturetype) uit het document. Alleen handtekeningen die zijn toegevoegd met de tekenmethode en zijn gemarkeerd als handtekeningen[`IsSignature`](../../../groupdocs.signature.domain/basesignature/issignature) wordt verwijderd. De volgende typen handtekeningen worden ondersteund: Tekst, Afbeelding, Digitaal, Barcode, QR-Code

```csharp
public DeleteResult Delete(List<SignatureType> signatureTypes)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| signatureTypes | List`1 | De lijst met typen handtekeningen die uit het document moeten worden verwijderd. |

### Winstwaarde

Retourneert DeleteResult[`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) met een lijst met succesvol verwijderde en mislukte handtekeningen.

### Opmerkingen

**Kom meer te weten**

* Meer informatie over het verwijderen van elektronische handtekeningen uit documenten in C#: [Hoe eSignatures met een specifiek type uit een document te verwijderen met GroupDocs.Signature](https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+types/)
* Geavanceerd gebruik van het verwijderen van e-handtekeningen van documenten: [Hoe verschillende soorten e-handtekeningen uit een document in C# te verwijderen](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Zie ook

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [Signature](../../signature)
* naamruimte [GroupDocs.Signature](../../signature)
* montage [GroupDocs.Signature](../../../)

---

## Delete(string) {#delete_1}

Verwijdert handtekening door zijn specifieke handtekening-ID uit het document.

```csharp
public bool Delete(string signatureId)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| signatureId | String | De id van de handtekening die uit het document moet worden verwijderd. |

### Winstwaarde

Retourneert waar als de bewerking is geslaagd.

### Opmerkingen

**Kom meer te weten**

* Meer informatie over het verwijderen van elektronische handtekeningen uit documenten in C#: [Hoe eSignature uit een document te verwijderen met GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Geavanceerd gebruik van het verwijderen van e-handtekeningen van documenten: [Hoe verschillende soorten e-handtekeningen uit een document in C# te verwijderen](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Zie ook

* class [Signature](../../signature)
* naamruimte [GroupDocs.Signature](../../signature)
* montage [GroupDocs.Signature](../../../)

---

## Delete(List&lt;string&gt;) {#delete_5}

Verwijdert goedgekeurde lijst met handtekeningen[`BaseSignature`](../../../groupdocs.signature.domain/basesignature) uit het document.

```csharp
public DeleteResult Delete(List<string> signatureIds)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| signatureIds | List`1 | Lijst met de identificatoren van de handtekeningen die uit het document moeten worden verwijderd. |

### Winstwaarde

Retourneert DeleteResult[`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) met een lijst met succesvol verwijderde en mislukte handtekeningen.

### Opmerkingen

**Kom meer te weten**

* Meer informatie over het verwijderen van elektronische handtekeningen uit documenten in C#: [Hoe eSignature uit een document te verwijderen met GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Geavanceerd gebruik van het verwijderen van e-handtekeningen van documenten: [Hoe verschillende soorten e-handtekeningen uit een document in C# te verwijderen](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Zie ook

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* class [Signature](../../signature)
* naamruimte [GroupDocs.Signature](../../signature)
* montage [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
