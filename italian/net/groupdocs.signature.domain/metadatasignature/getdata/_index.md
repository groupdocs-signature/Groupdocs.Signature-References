---
title: "GetData"
second_title: "GroupDocs.Signature per .NET Riferimento API"
description: "Ottieni l'oggetto dal valore Metadata Signature durante la deserializzazione."
type: docs
weight: 70
url: /it/net/groupdocs.signature.domain/metadatasignature/getdata/
---
## GetData&lt;T&gt;() {#getdata}

Ottieni l'oggetto dal valore Metadata Signature durante la deserializzazione.

```csharp
public T GetData<T>()
    where T : class
```

| Parametro | Descrizione |
| --- | --- |
| T | Tipo di oggetto da deserializzare dal valore Metadata |

### Valore di ritorno

Istanza dell'oggetto T

### Vedi anche

* class [MetadataSignature](../../metadatasignature)
* namespace [GroupDocs.Signature.Domain](../../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../../)

---

## GetData&lt;T&gt;(IDataEncryption) {#getdata_1}

Ottieni l'oggetto dal testo Metadata Signature durante la deserializzazione.

```csharp
public T GetData<T>(IDataEncryption dataEncryption)
    where T : class
```

| Parametro | Descrizione |
| --- | --- |
| T | Tipo di oggetto da deserializzare dal valore Metadata |
| dataEncryption | Imposta implementazione personalizzata della crittografia dei dati |

### Vedi anche

* interface [IDataEncryption](../../../groupdocs.signature.domain.extensions/idataencryption)
* class [MetadataSignature](../../metadatasignature)
* namespace [GroupDocs.Signature.Domain](../../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.signature.dll -->
