---
title: Item
second_title: Riferimento API GroupDocs.Signature per .NET
description: Restituisce un oggetto MetadataSignature in base al nome della proprietà.
type: docs
weight: 30
url: /it/net/groupdocs.signature.domain/metadatasignaturecollection/item/
---
## MetadataSignatureCollection indexer (1 of 2)

Restituisce un oggetto MetadataSignature in base al nome della proprietà.

```csharp
public MetadataSignature this[string name] { get; }
```

| Parametro | Descrizione |
| --- | --- |
| name | Il nome senza distinzione tra maiuscole e minuscole della proprietà da recuperare. |

### Valore di ritorno

Restituisce una firma dei metadati[`MetadataSignature`](../../metadatasignature) oggetto dal nome della proprietà.

### Osservazioni

Restituisce null se non viene trovata una proprietà con il nome specificato.

### Guarda anche

* class [MetadataSignature](../../metadatasignature)
* class [MetadataSignatureCollection](../../metadatasignaturecollection)
* spazio dei nomi [GroupDocs.Signature.Domain](../../metadatasignaturecollection)
* assemblea [GroupDocs.Signature](../../../)

---

## MetadataSignatureCollection indexer (2 of 2)

Restituisce un oggetto MetadataSignature per indice.

```csharp
public MetadataSignature this[int index] { get; }
```

| Parametro | Descrizione |
| --- | --- |
| index | Indice in base zero della firma dei metadati da recuperare. |

### Valore di ritorno

Restituisce una firma dei metadati[`MetadataSignature`](../../metadatasignature) oggetto dall'indice di raccolta.

### Osservazioni

Restituisce null se non esiste una proprietà con l'indice specificato.

### Guarda anche

* class [MetadataSignature](../../metadatasignature)
* class [MetadataSignatureCollection](../../metadatasignaturecollection)
* spazio dei nomi [GroupDocs.Signature.Domain](../../metadatasignaturecollection)
* assemblea [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->