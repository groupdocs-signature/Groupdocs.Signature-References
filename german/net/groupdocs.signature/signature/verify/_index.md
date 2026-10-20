---
title: "Verifizieren"
second_title: "GroupDocs.Signature für .NET API-Referenz"
description: "Überprüft die Dokumentensignaturen mit den angegebenen VerifyOptions-Daten."
type: docs
weight: 180
url: /de/net/groupdocs.signature/signature/verify/
---
## Verify(VerifyOptions) {#verify}

Überprüft die Dokumentensignaturen mit den angegebenen VerifyOptions-Daten.

```csharp
public VerificationResult Verify(VerifyOptions verifyOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| verifyOptions | VerifyOptions | Die Optionen zur Signaturverifizierung. |

### Rückgabewert

Gibt eine Instanz von [`VerificationResult`](../../../groupdocs.signature.domain/verificationresult) zurück. Die Eigenschaft VerificationResult.IsValid gibt true zurück, wenn der Verifizierungsprozess erfolgreich war.

### Hinweise

**Learn more**

* More about electronically signed documents verification using GroupDocs.Signature: [How to verify document is electronically signed in C#](https://docs.groupdocs.com/display/signaturenet/Verify+document+for+signatures)

### Siehe auch

* class [VerificationResult](../../../groupdocs.signature.domain/verificationresult)
* class [VerifyOptions](../../../groupdocs.signature.options/verifyoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Verify(VerifyOptions, Func&lt;BaseSignature, bool&gt;) {#verify_2}

Überprüft die Dokumentensignaturen unter Verwendung der bereitgestellten Verifizierungsoptionen und filtert die Ergebnisse basierend auf dem angegebenen Prädikat. Diese Methode sucht zunächst nach Signaturen, die den Verifizierungsoptionen entsprechen, filtert sie mithilfe des Prädikats und verifiziert anschließend nur die gefilterten Signaturen.

```csharp
public List<BaseSignature> Verify(VerifyOptions verifyOptions, Func<BaseSignature, bool> predicate)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| verifyOptions | VerifyOptions | Die Optionen zur Signaturverifizierung. |
| Prädikat | Func`2 | Das Filterprädikat, um zu bestimmen, welche Signaturen verifiziert werden sollen. |

### Rückgabewert

Gibt eine Liste von [`BaseSignature`](../../../groupdocs.signature.domain/basesignature)-Instanzen zurück, die das bereitgestellte Prädikat erfüllen.

### Hinweise

**Learn more**

* More about electronically signed documents verification using GroupDocs.Signature: [How to verify document is electronically signed in C#](https://docs.groupdocs.com/display/signaturenet/Verify+document+for+signatures)

### Siehe auch

* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [VerifyOptions](../../../groupdocs.signature.options/verifyoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Verify(List&lt;VerifyOptions&gt;) {#verify_1}

Überprüft die Signaturen des Dokuments mit einer Liste von VerifyOptions-Daten.

```csharp
public VerificationResult Verify(List<VerifyOptions> verifyOptionsList)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| verifyOptionsList | List`1 | Die Sammlung von Signaturverifizierungsoptionen. Instanz von VerifyOptionsCollection. |

### Rückgabewert

Gibt eine Instanz von [`VerificationResult`](../../../groupdocs.signature.domain/verificationresult) zurück. Die Eigenschaft VerificationResult.IsValid gibt true zurück, wenn der Verifizierungsprozess erfolgreich war.

### Hinweise

**Learn more**

* More about electronically signed documents verification using GroupDocs.Signature: [How to verify document is electronically signed in C#](https://docs.groupdocs.com/display/signaturenet/Verify+document+for+signatures)

### Siehe auch

* class [VerificationResult](../../../groupdocs.signature.domain/verificationresult)
* class [VerifyOptions](../../../groupdocs.signature.options/verifyoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Verify(List&lt;VerifyOptions&gt;, Func&lt;BaseSignature, bool&gt;) {#verify_3}

Überprüft die Dokumentensignaturen unter Verwendung aller verfügbaren Verifizierungsoptionen und filtert die Ergebnisse basierend auf dem angegebenen Prädikat. Diese Methode sucht zunächst nach Signaturen, die den Verifizierungsoptionen entsprechen, filtert sie mithilfe des Prädikats und verifiziert anschließend nur die gefilterten Signaturen.

```csharp
public List<BaseSignature> Verify(List<VerifyOptions> verifyOptionsList, 
    Func<BaseSignature, bool> predicate)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| verifyOptionsList | List`1 | Die Sammlung von Signaturverifizierungsoptionen. Instanz von VerifyOptionsCollection. |
| Prädikat | Func`2 | Das Filterprädikat, um zu bestimmen, welche Signaturen verifiziert werden sollen. |

### Rückgabewert

Gibt eine Liste von [`BaseSignature`](../../../groupdocs.signature.domain/basesignature)-Instanzen zurück, die das bereitgestellte Prädikat erfüllen.

### Hinweise

**Learn more**

* More about electronically signed documents verification using GroupDocs.Signature: [How to verify document is electronically signed in C#](https://docs.groupdocs.com/display/signaturenet/Verify+document+for+signatures)

### Siehe auch

* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [VerifyOptions](../../../groupdocs.signature.options/verifyoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
