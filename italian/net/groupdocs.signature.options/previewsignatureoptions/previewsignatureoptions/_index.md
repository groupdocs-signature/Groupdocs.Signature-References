---
title: "PreviewSignatureOptions"
second_title: "GroupDocs.Signature per .NET Riferimento API"
description: "Inizializza l'oggetto PreviewSignatureOptions."
type: docs
weight: 10
url: /it/net/groupdocs.signature.options/previewsignatureoptions/previewsignatureoptions/
---
## PreviewSignatureOptions(SignOptions, CreateSignatureStream) {#constructor}

Inizializza l'oggetto PreviewSignatureOptions.

```csharp
public PreviewSignatureOptions(SignOptions signOptions, CreateSignatureStream createSignatureStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| signOptions | SignOptions | Le opzioni di firma per le quali generare l'anteprima. |
| createSignatureStream | CreateSignatureStream | Delegato che definisce il metodo per creare lo stream di anteprima della firma di output. |

### Vedi anche

* class [SignOptions](../../signoptions)
* delegate [CreateSignatureStream](../../createsignaturestream)
* class [PreviewSignatureOptions](../../previewsignatureoptions)
* namespace [GroupDocs.Signature.Options](../../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../../)

---

## PreviewSignatureOptions(SignOptions, CreateSignatureStream, ReleaseSignatureStream) {#constructor_1}

Inizializza l'oggetto PreviewSignatureOptions.

```csharp
public PreviewSignatureOptions(SignOptions signOptions, 
    CreateSignatureStream createSignatureStream, ReleaseSignatureStream releaseSignatureStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| signOptions | SignOptions | Le opzioni di firma per le quali generare l'anteprima. |
| createSignatureStream | CreateSignatureStream | Delegato che definisce il metodo per creare lo stream di anteprima della firma di output. |
| releaseSignatureStream | ReleaseSignatureStream | Delegato che definisce il metodo per rilasciare lo stream di anteprima della firma di output. |

### Vedi anche

* class [SignOptions](../../signoptions)
* delegate [CreateSignatureStream](../../createsignaturestream)
* delegate [ReleaseSignatureStream](../../releasesignaturestream)
* class [PreviewSignatureOptions](../../previewsignatureoptions)
* namespace [GroupDocs.Signature.Options](../../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.signature.dll -->
