---
title: "PreviewOptions"
second_title: "GroupDocs.Signature per .NET Riferimento API"
description: "Inizializza l'oggetto PreviewOptions."
type: docs
weight: 10
url: /it/net/groupdocs.signature.options/previewoptions/previewoptions/
---
## PreviewOptions(CreateDocPageStream, int, params int[]) {#constructor}

Inizializza l'oggetto PreviewOptions.

```csharp
public PreviewOptions(CreateDocPageStream createPageStream, int resolution = 96, 
    params int[] pageNumbers)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| createPageStream | CreateDocPageStream | Delegate che definisce il metodo per creare lo stream di anteprima della pagina del documento di output. |
| resolution | Int32 | Risoluzione delle immagini di anteprima in DPI (opzionale). |
| pageNumbers | Int32[] | Numeri di pagina desiderati |

### Vedi anche

* delegate [CreateDocPageStream](../../previewoptions.createdocpagestream)
* class [PreviewOptions](../../previewoptions)
* namespace [GroupDocs.Signature.Options](../../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../../)

---

## PreviewOptions(CreateDocPageStream, ReleaseDocPageStream, int, params int[]) {#constructor_1}

Inizializza l'oggetto PreviewOptions.

```csharp
public PreviewOptions(CreateDocPageStream createPageStream, ReleaseDocPageStream releasePageStream, 
    int resolution = 96, params int[] pageNumbers)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| createPageStream | CreateDocPageStream | Delegate che definisce il metodo per creare lo stream di anteprima della pagina del documento di output. |
| releasePageStream | ReleaseDocPageStream | Delegato che definisce il metodo per rilasciare lo stream di anteprima della pagina del documento di output. |
| resolution | Int32 | Risoluzione delle immagini di anteprima in DPI (opzionale). |
| pageNumbers | Int32[] | Numeri di pagina desiderati |

### Vedi anche

* delegate [CreateDocPageStream](../../previewoptions.createdocpagestream)
* delegate [ReleaseDocPageStream](../../previewoptions.releasedocpagestream)
* class [PreviewOptions](../../previewoptions)
* namespace [GroupDocs.Signature.Options](../../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.signature.dll -->
