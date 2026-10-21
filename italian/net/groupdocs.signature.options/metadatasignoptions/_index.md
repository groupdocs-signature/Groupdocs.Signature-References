---
title: "MetadataSignOptions"
second_title: "GroupDocs.Signature per .NET Riferimento API"
description: "Rappresenta le opzioni della firma Metadata."
type: docs
weight: 1740
url: /it/net/groupdocs.signature.options/metadatasignoptions/
---
## MetadataSignOptions class

Rappresenta le opzioni della firma Metadata.

```csharp
public class MetadataSignOptions : SignOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [MetadataSignOptions](metadatasignoptions#constructor)() | Inizializza una nuova istanza della classe MetadataSignOptions con valori predefiniti. |
| [MetadataSignOptions](metadatasignoptions#constructor_1)(IEnumerable&lt;MetadataSignature&gt;) | Inizializza una nuova istanza della classe MetadataSignOptions con i metadati. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| virtual [AllPages](../../groupdocs.signature.options/signoptions/allpages) { get; set; } | Applica la firma su tutte le pagine del documento. |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | Aspetto aggiuntivo della firma. |
| [DataEncryption](../../groupdocs.signature.options/metadatasignoptions/dataencryption) { get; set; } | Ottiene o imposta l'implementazione dell'interfaccia [`IDataEncryption`](../../groupdocs.signature.domain.extensions/idataencryption) per crittografare tutte le firme Metadata all'interno di questa raccolta di opzioni. Se questo valore è impostato, tutte le firme aggiunte utilizzeranno questa crittografia per impostazione predefinita o la propria DataEncryption se è stata assegnata. |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | Ottieni o imposta il Tipo di Documento delle Opzioni di Firma [`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | Estensioni della firma. |
| [HashAlgorithm](../../groupdocs.signature.options/signoptions/hashalgorithm) { get; set; } | Ottiene o imposta l'algoritmo di hash da utilizzare per le operazioni crittografiche. Supportato esclusivamente per firme digitali nei file PDF. |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | Ottiene o imposta il numero di pagina del documento per la firma. Il valore minimo e predefinito è 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | Opzioni per specificare le pagine da firmare. |
| [Signatures](../../groupdocs.signature.options/metadatasignoptions/signatures) { get; set; } | Ottiene o imposta i metadati della firma. |
| [SignatureType](../../groupdocs.signature.options/signoptions/signaturetype) { get; } | Ottieni il Tipo di Firma [`SignatureType`](../../groupdocs.signature.domain/signaturetype) |
| [ZOrder](../../groupdocs.signature.options/signoptions/zorder) { get; set; } | Ottiene o imposta la posizione Z-order della firma testuale. Determina l'ordine di visualizzazione delle firme sovrapposte. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Add](../../groupdocs.signature.options/metadatasignoptions/add)(MetadataSignature) | Aggiungi un'istanza esistente di MetadataSignature alla raccolta. |
| [AddImageSignature](../../groupdocs.signature.options/metadatasignoptions/addimagesignature)(ushort, object) | Crea una nuova ImageMetadataSignature con gli argomenti forniti e la aggiunge alla raccolta. |
| [AddPdfSignature](../../groupdocs.signature.options/metadatasignoptions/addpdfsignature)(string, object, string) | Crea una nuova PdfMetadataSignature con gli argomenti forniti e la aggiunge alla raccolta. |

### Osservazioni

**Learn more**

* Basic usage of creating Metadata electronic signature by GroupDocs.Signature: [How to eSign document with Metadata signature](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Metadata+signature)
* Advanced usage of settings of Metadata electronic signature with GroupDocs.Signature: [Advanced usage to eSign document with Metadata signature and additional settings](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Metadata+signature+-+advanced)

### Vedi anche

* class [SignOptions](../signoptions)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.signature.dll -->
