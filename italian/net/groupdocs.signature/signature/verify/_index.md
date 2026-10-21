---
title: "Verifica"
second_title: "GroupDocs.Signature per .NET Riferimento API"
description: "Verifica le firme del documento con i dati VerifyOptions forniti."
type: docs
weight: 180
url: /it/net/groupdocs.signature/signature/verify/
---
## Verify(VerifyOptions) {#verify}

Verifica le firme del documento con i dati VerifyOptions forniti.

```csharp
public VerificationResult Verify(VerifyOptions verifyOptions)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| verifyOptions | VerifyOptions | Le opzioni di verifica della firma. |

### Valore di ritorno

Restituisce un'istanza di [`VerificationResult`](../../../groupdocs.signature.domain/verificationresult). La proprietà VerificationResult.IsValid restituisce true se il processo di verifica è stato completato con successo.

### Osservazioni

**Learn more**

* More about electronically signed documents verification using GroupDocs.Signature: [How to verify document is electronically signed in C#](https://docs.groupdocs.com/display/signaturenet/Verify+document+for+signatures)

### Vedi anche

* class [VerificationResult](../../../groupdocs.signature.domain/verificationresult)
* class [VerifyOptions](../../../groupdocs.signature.options/verifyoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Verify(VerifyOptions, Func&lt;BaseSignature, bool&gt;) {#verify_2}

Verifica le firme del documento utilizzando le opzioni di verifica fornite e filtra i risultati in base al predicato specificato. Questo metodo prima ricerca le firme che corrispondono alle opzioni di verifica, le filtra usando il predicato e poi verifica solo le firme filtrate.

```csharp
public List<BaseSignature> Verify(VerifyOptions verifyOptions, Func<BaseSignature, bool> predicate)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| verifyOptions | VerifyOptions | Le opzioni di verifica della firma. |
| predicate | Func`2 | Il predicato di filtro per determinare quali firme devono essere verificate. |

### Valore di ritorno

Restituisce un elenco di istanze di [`BaseSignature`](../../../groupdocs.signature.domain/basesignature) che soddisfano il predicato fornito.

### Osservazioni

**Learn more**

* More about electronically signed documents verification using GroupDocs.Signature: [How to verify document is electronically signed in C#](https://docs.groupdocs.com/display/signaturenet/Verify+document+for+signatures)

### Vedi anche

* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [VerifyOptions](../../../groupdocs.signature.options/verifyoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Verify(List&lt;VerifyOptions&gt;) {#verify_1}

Verifica le firme del documento con un elenco di dati VerifyOptions.

```csharp
public VerificationResult Verify(List<VerifyOptions> verifyOptionsList)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| verifyOptionsList | List`1 | La raccolta delle opzioni di verifica della firma. Istanza di VerifyOptionsCollection. |

### Valore di ritorno

Restituisce un'istanza di [`VerificationResult`](../../../groupdocs.signature.domain/verificationresult). La proprietà VerificationResult.IsValid restituisce true se il processo di verifica è stato completato con successo.

### Osservazioni

**Learn more**

* More about electronically signed documents verification using GroupDocs.Signature: [How to verify document is electronically signed in C#](https://docs.groupdocs.com/display/signaturenet/Verify+document+for+signatures)

### Vedi anche

* class [VerificationResult](../../../groupdocs.signature.domain/verificationresult)
* class [VerifyOptions](../../../groupdocs.signature.options/verifyoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Verify(List&lt;VerifyOptions&gt;, Func&lt;BaseSignature, bool&gt;) {#verify_3}

Verifica le firme del documento utilizzando tutte le opzioni di verifica disponibili e filtra i risultati in base al predicato specificato. Questo metodo prima ricerca le firme che corrispondono alle opzioni di verifica, le filtra usando il predicato e poi verifica solo le firme filtrate.

```csharp
public List<BaseSignature> Verify(List<VerifyOptions> verifyOptionsList, 
    Func<BaseSignature, bool> predicate)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| verifyOptionsList | List`1 | La raccolta delle opzioni di verifica della firma. Istanza di VerifyOptionsCollection. |
| predicate | Func`2 | Il predicato di filtro per determinare quali firme devono essere verificate. |

### Valore di ritorno

Restituisce un elenco di istanze di [`BaseSignature`](../../../groupdocs.signature.domain/basesignature) che soddisfano il predicato fornito.

### Osservazioni

**Learn more**

* More about electronically signed documents verification using GroupDocs.Signature: [How to verify document is electronically signed in C#](https://docs.groupdocs.com/display/signaturenet/Verify+document+for+signatures)

### Vedi anche

* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [VerifyOptions](../../../groupdocs.signature.options/verifyoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.signature.dll -->
