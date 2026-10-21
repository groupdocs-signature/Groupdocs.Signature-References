---
title: "Verify"
second_title: "GroupDocs.Signature for .NET API-referentie"
description: "Verifieert de handtekeningen van het document met de opgegeven VerifyOptions-gegevens."
type: docs
weight: 180
url: /nl/net/groupdocs.signature/signature/verify/
---
## Verify(VerifyOptions) {#verify}

Verifieert de handtekeningen van het document met de opgegeven VerifyOptions-gegevens.

```csharp
public VerificationResult Verify(VerifyOptions verifyOptions)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| verifyOptions | VerifyOptions | De verificatie‑opties voor de handtekening. |

### Retourwaarde

Retourneert een instantie van [`VerificationResult`](../../../groupdocs.signature.domain/verificationresult). Eigenschap VerificationResult.IsValid retourneert true als het verificatieproces succesvol was.

### Opmerkingen

**Learn more**

* More about electronically signed documents verification using GroupDocs.Signature: [How to verify document is electronically signed in C#](https://docs.groupdocs.com/display/signaturenet/Verify+document+for+signatures)

### Zie ook

* class [VerificationResult](../../../groupdocs.signature.domain/verificationresult)
* class [VerifyOptions](../../../groupdocs.signature.options/verifyoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Verify(VerifyOptions, Func&lt;BaseSignature, bool&gt;) {#verify_2}

Verifieert de handtekeningen van het document met de opgegeven verificatieopties en filtert de resultaten op basis van het opgegeven predicaat. Deze methode zoekt eerst naar handtekeningen die overeenkomen met de verificatieopties, filtert ze met het predicaat, en verifieert vervolgens alleen die gefilterde handtekeningen.

```csharp
public List<BaseSignature> Verify(VerifyOptions verifyOptions, Func<BaseSignature, bool> predicate)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| verifyOptions | VerifyOptions | De verificatie‑opties voor de handtekening. |
| predicate | Func`2 | De filter‑predicaat om te bepalen welke handtekeningen moeten worden geverifieerd. |

### Retourwaarde

Retourneert een lijst van [`BaseSignature`](../../../groupdocs.signature.domain/basesignature) instanties die voldoen aan het opgegeven predicaat.

### Opmerkingen

**Learn more**

* More about electronically signed documents verification using GroupDocs.Signature: [How to verify document is electronically signed in C#](https://docs.groupdocs.com/display/signaturenet/Verify+document+for+signatures)

### Zie ook

* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [VerifyOptions](../../../groupdocs.signature.options/verifyoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Verify(List&lt;VerifyOptions&gt;) {#verify_1}

Verifieert de handtekeningen van het document met een lijst van VerifyOptions-gegevens.

```csharp
public VerificationResult Verify(List<VerifyOptions> verifyOptionsList)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| verifyOptionsList | List`1 | De collectie van verificatie‑opties voor handtekeningen. Een instantie van VerifyOptionsCollection. |

### Retourwaarde

Retourneert een instantie van [`VerificationResult`](../../../groupdocs.signature.domain/verificationresult). Eigenschap VerificationResult.IsValid retourneert true als het verificatieproces succesvol was.

### Opmerkingen

**Learn more**

* More about electronically signed documents verification using GroupDocs.Signature: [How to verify document is electronically signed in C#](https://docs.groupdocs.com/display/signaturenet/Verify+document+for+signatures)

### Zie ook

* class [VerificationResult](../../../groupdocs.signature.domain/verificationresult)
* class [VerifyOptions](../../../groupdocs.signature.options/verifyoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Verify(List&lt;VerifyOptions&gt;, Func&lt;BaseSignature, bool&gt;) {#verify_3}

Verifieert de handtekeningen van het document met behulp van alle beschikbare verificatieopties en filtert de resultaten op basis van het opgegeven predicaat. Deze methode zoekt eerst naar handtekeningen die overeenkomen met de verificatieopties, filtert ze met het predicaat, en verifieert vervolgens alleen die gefilterde handtekeningen.

```csharp
public List<BaseSignature> Verify(List<VerifyOptions> verifyOptionsList, 
    Func<BaseSignature, bool> predicate)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| verifyOptionsList | List`1 | De collectie van verificatie‑opties voor handtekeningen. Een instantie van VerifyOptionsCollection. |
| predicate | Func`2 | De filter‑predicaat om te bepalen welke handtekeningen moeten worden geverifieerd. |

### Retourwaarde

Retourneert een lijst van [`BaseSignature`](../../../groupdocs.signature.domain/basesignature) instanties die voldoen aan het opgegeven predicaat.

### Opmerkingen

**Learn more**

* More about electronically signed documents verification using GroupDocs.Signature: [How to verify document is electronically signed in C#](https://docs.groupdocs.com/display/signaturenet/Verify+document+for+signatures)

### Zie ook

* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [VerifyOptions](../../../groupdocs.signature.options/verifyoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
