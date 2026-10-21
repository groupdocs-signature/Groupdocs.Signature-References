---
title: "JpegCompressionMode"
second_title: "GroupDocs.Signature per .NET Riferimento API"
description: "Specifica le modalità di compressione JPEG."
type: docs
weight: 1690
url: /it/net/groupdocs.signature.options/jpegcompressionmode/
---
## JpegCompressionMode enumeration

Specifica le modalità di compressione JPEG.

```csharp
public enum JpegCompressionMode
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| Baseline | `0` | La compressione di base. |
| Progressive | `1` | La compressione progressiva. |
| Lossless | `2` | La compressione senza perdita. Usa questo tipo di compressione con attenzione perché molti visualizzatori di immagini non lo supportano. Se lo usi, prova ad assegnare la proprietà [`ColorType`](../jpegsaveoptions/colortype) a valori Grayscale o Rgb. |
| JpegLs | `3` | La compressione JPEG-LS. Usa questo tipo di compressione con attenzione perché molti visualizzatori di immagini non lo supportano. Se lo usi, prova ad assegnare la proprietà [`ColorType`](../jpegsaveoptions/colortype) al valore Grayscale. |

### Vedi anche

* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.signature.dll -->
