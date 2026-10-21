---
title: "FromExtension"
second_title: "GroupDocs.Signature per .NET Riferimento API"
description: "Mappa l'estensione del file al tipo di file."
type: docs
weight: 660
url: /it/net/groupdocs.signature.domain/filetype/fromextension/
---
## FileType.FromExtension method

Mappa l'estensione del file al tipo di file.

```csharp
public static FileType FromExtension(string extension)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| estensione | String | Estensione del file (incluso il punto "."). |

### Valore di ritorno

Quando il tipo di file è supportato lo restituisce, altrimenti restituisce il tipo di file predefinito [`Unknown`](../unknown).

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Generata quando *extension* è null o una stringa vuota. |

### Vedi anche

* class [FileType](../../filetype)
* namespace [GroupDocs.Signature.Domain](../../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.signature.dll -->
