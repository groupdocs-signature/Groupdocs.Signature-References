---
title: "PngFilterType"
second_title: "GroupDocs.Signature per .NET Riferimento API"
description: "Rappresenta il tipo di filtro dell'immagine PNG."
type: docs
weight: 1810
url: /it/net/groupdocs.signature.options/pngfiltertype/
---
## PngFilterType enumeration

Rappresenta il tipo di filtro dell'immagine PNG.

```csharp
public enum PngFilterType
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| None | `0` | Il null-filter, significa nessuna filtrazione per le righe dei dati immagine. |
| Sub | `1` | Il sub filter, significa che verrà applicata una filtrazione sottrattiva ai dati immagine. |
| Up | `2` | Il up filter, significa che verrà applicato un filtro di sottrazione riga per riga. |
| Avg | `3` | Il avg filter, significa che verrà applicato un filtro medio ai dati immagine. |
| Paeth | `4` | Il filtro predittore di percorso. |
| Adaptive | `5` | La filtrazione adattiva, significa che il processo di salvataggio sceglierà il filtro più adatto per ogni riga di dati. Migliore compressione, tempo di esecuzione più lento. |

### Vedi anche

* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.signature.dll -->
