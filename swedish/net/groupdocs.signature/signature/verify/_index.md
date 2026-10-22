---
title: "Verifiera"
second_title: "GroupDocs.Signature för .NET API-referens"
description: "Verifierar dokumentets signaturer med angivna VerifyOptions-data."
type: docs
weight: 180
url: /sv/net/groupdocs.signature/signature/verify/
---
## Verify(VerifyOptions) {#verify}

Verifierar dokumentets signaturer med angivna VerifyOptions-data.

```csharp
public VerificationResult Verify(VerifyOptions verifyOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| verifyOptions | VerifyOptions | Alternativen för signaturverifiering. |

### Returvärde

Returnerar en instans av [`VerificationResult`](../../../groupdocs.signature.domain/verificationresult). Egenskapen VerificationResult.IsValid returnerar true om verifieringsprocessen var framgångsrik.

### Anmärkningar

**Learn more**

* More about electronically signed documents verification using GroupDocs.Signature: [How to verify document is electronically signed in C#](https://docs.groupdocs.com/display/signaturenet/Verify+document+for+signatures)

### Se även

* class [VerificationResult](../../../groupdocs.signature.domain/verificationresult)
* class [VerifyOptions](../../../groupdocs.signature.options/verifyoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Verify(VerifyOptions, Func&lt;BaseSignature, bool&gt;) {#verify_2}

Verifierar dokumentets signaturer med de angivna verifieringsalternativen och filtrerar resultaten baserat på det angivna predikatet. Denna metod söker först efter signaturer som matchar verifieringsalternativen, filtrerar dem med predikatet och verifierar sedan endast de filtrerade signaturerna.

```csharp
public List<BaseSignature> Verify(VerifyOptions verifyOptions, Func<BaseSignature, bool> predicate)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| verifyOptions | VerifyOptions | Alternativen för signaturverifiering. |
| predikat | Func`2 | Filterpredikatet för att bestämma vilka signaturer som ska verifieras. |

### Returvärde

Returnerar en lista med [`BaseSignature`](../../../groupdocs.signature.domain/basesignature)-instanser som uppfyller det angivna predikatet.

### Anmärkningar

**Learn more**

* More about electronically signed documents verification using GroupDocs.Signature: [How to verify document is electronically signed in C#](https://docs.groupdocs.com/display/signaturenet/Verify+document+for+signatures)

### Se även

* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [VerifyOptions](../../../groupdocs.signature.options/verifyoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Verify(List&lt;VerifyOptions&gt;) {#verify_1}

Verifierar dokumentets signaturer med en lista av VerifyOptions-data.

```csharp
public VerificationResult Verify(List<VerifyOptions> verifyOptionsList)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| verifyOptionsList | List`1 | Samlingen av alternativ för signaturverifiering. Instans av VerifyOptionsCollection. |

### Returvärde

Returnerar en instans av [`VerificationResult`](../../../groupdocs.signature.domain/verificationresult). Egenskapen VerificationResult.IsValid returnerar true om verifieringsprocessen var framgångsrik.

### Anmärkningar

**Learn more**

* More about electronically signed documents verification using GroupDocs.Signature: [How to verify document is electronically signed in C#](https://docs.groupdocs.com/display/signaturenet/Verify+document+for+signatures)

### Se även

* class [VerificationResult](../../../groupdocs.signature.domain/verificationresult)
* class [VerifyOptions](../../../groupdocs.signature.options/verifyoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Verify(List&lt;VerifyOptions&gt;, Func&lt;BaseSignature, bool&gt;) {#verify_3}

Verifierar dokumentets signaturer med alla tillgängliga verifieringsalternativ och filtrerar resultaten baserat på det angivna predikatet. Denna metod söker först efter signaturer som matchar verifieringsalternativen, filtrerar dem med predikatet och verifierar sedan endast de filtrerade signaturerna.

```csharp
public List<BaseSignature> Verify(List<VerifyOptions> verifyOptionsList, 
    Func<BaseSignature, bool> predicate)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| verifyOptionsList | List`1 | Samlingen av alternativ för signaturverifiering. Instans av VerifyOptionsCollection. |
| predikat | Func`2 | Filterpredikatet för att bestämma vilka signaturer som ska verifieras. |

### Returvärde

Returnerar en lista med [`BaseSignature`](../../../groupdocs.signature.domain/basesignature)-instanser som uppfyller det angivna predikatet.

### Anmärkningar

**Learn more**

* More about electronically signed documents verification using GroupDocs.Signature: [How to verify document is electronically signed in C#](https://docs.groupdocs.com/display/signaturenet/Verify+document+for+signatures)

### Se även

* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [VerifyOptions](../../../groupdocs.signature.options/verifyoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
