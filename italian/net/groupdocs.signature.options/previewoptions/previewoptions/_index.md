---
title: PreviewOptions
second_title: Riferimento API GroupDocs.Signature per .NET
description: Inizializza loggetto PreviewOptions.
type: docs
weight: 10
url: /it/net/groupdocs.signature.options/previewoptions/previewoptions/
---
## PreviewOptions(CreatePageStream, params int[]) {#constructor_1}

Inizializza l'oggetto PreviewOptions.

```csharp
public PreviewOptions(CreatePageStream createPageStream, params int[] pageNumbers)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| createPageStream | CreatePageStream | Delegato che definisce il metodo per creare il flusso di anteprima della pagina di output. |
| pageNumbers | Int32[] | Numeri di pagina desiderati |

### Guarda anche

* delegate [CreatePageStream](../../createpagestream)
* class [PreviewOptions](../../previewoptions)
* spazio dei nomi [GroupDocs.Signature.Options](../../previewoptions)
* assemblea [GroupDocs.Signature](../../../)

---

## PreviewOptions(CreatePageStream, ReleasePageStream, params int[]) {#constructor}

Inizializza l'oggetto PreviewOptions.

```csharp
public PreviewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream, 
    params int[] pageNumbers)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| createPageStream | CreatePageStream | Delegato che definisce il metodo per creare il flusso di anteprima della pagina di output. |
| releasePageStream | ReleasePageStream | Delegato che definisce il metodo per rilasciare il flusso di anteprima della pagina di output. |
| pageNumbers | Int32[] | Numeri di pagina desiderati |

### Guarda anche

* delegate [CreatePageStream](../../createpagestream)
* delegate [ReleasePageStream](../../releasepagestream)
* class [PreviewOptions](../../previewoptions)
* spazio dei nomi [GroupDocs.Signature.Options](../../previewoptions)
* assemblea [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
