---
title: "DocumentInfo"
second_title: "GroupDocs.Signature per .NET Riferimento API"
description: "Definisce le proprietà della descrizione del documento."
type: docs
weight: 160
url: /it/net/groupdocs.signature.domain/documentinfo/
---
## DocumentInfo class

Definisce le proprietà della descrizione del documento.

```csharp
public class DocumentInfo : IDocumentInfo
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [DocumentInfo](documentinfo)() | Inizializza una nuova istanza della classe [`DocumentInfo`](../documentinfo). |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [BarcodeSignatures](../../groupdocs.signature.domain/documentinfo/barcodesignatures) { get; } | Raccolta di firme barcode del documento aggiunte o aggiornate dai metodi [`Signature`](../../groupdocs.signature/signature). |
| [DigitalSignatures](../../groupdocs.signature.domain/documentinfo/digitalsignatures) { get; } | Raccolta di firme digitali del documento aggiunte o aggiornate dai metodi [`Signature`](../../groupdocs.signature/signature). |
| [Documents](../../groupdocs.signature.domain/documentinfo/documents) { get; } | Raccolta di tutti i documenti esistenti all'interno dei file di archivio. Questa proprietà è supportata solo per i tipi di documento Archive. |
| [FileType](../../groupdocs.signature.domain/documentinfo/filetype) { get; set; } | Tipo di formato file. |
| [FormFields](../../groupdocs.signature.domain/documentinfo/formfields) { get; } | Raccolta di tutti i campi modulo supportati esistenti nel documento. Questa proprietà è supportata solo per i tipi di documento Pdf e Word Processing. |
| [FormFieldSignatures](../../groupdocs.signature.domain/documentinfo/formfieldsignatures) { get; } | Raccolta di firme di campi modulo del documento aggiunte o aggiornate dai metodi [`Signature`](../../groupdocs.signature/signature). |
| [ImageSignatures](../../groupdocs.signature.domain/documentinfo/imagesignatures) { get; } | Raccolta di firme immagine del documento aggiunte o aggiornate dai metodi [`Signature`](../../groupdocs.signature/signature). |
| [MaxPageHeight](../../groupdocs.signature.domain/documentinfo/maxpageheight) { get; set; } | Specifica l'altezza massima della pagina. |
| [MetadataSignatures](../../groupdocs.signature.domain/documentinfo/metadatasignatures) { get; } | Raccolta di firme di metadati del documento. |
| [PageCount](../../groupdocs.signature.domain/documentinfo/pagecount) { get; set; } | Conteggio delle pagine del documento. |
| [Pages](../../groupdocs.signature.domain/documentinfo/pages) { get; set; } | Raccolta di descrizioni delle pagine del documento. |
| [ProcessLogs](../../groupdocs.signature.domain/documentinfo/processlogs) { get; } | Raccolta di processi di cronologia del documento come Firma, Aggiornamento, Eliminazione. |
| [QrCodeSignatures](../../groupdocs.signature.domain/documentinfo/qrcodesignatures) { get; } | Raccolta di firme QR-code del documento aggiunte o aggiornate dai metodi [`Signature`](../../groupdocs.signature/signature). |
| [Signatures](../../groupdocs.signature.domain/documentinfo/signatures) { get; } | Raccolta di firme di tutti i tipi di documento [`BaseSignature`](../basesignature). |
| [Size](../../groupdocs.signature.domain/documentinfo/size) { get; set; } | Dimensione del documento in byte. |
| [TextSignatures](../../groupdocs.signature.domain/documentinfo/textsignatures) { get; } | Raccolta di firme di testo del documento. |
| [WidthForMaxHeight](../../groupdocs.signature.domain/documentinfo/widthformaxheight) { get; set; } | Specifica la larghezza per l'altezza massima della pagina. |

### Vedi anche

* interface [IDocumentInfo](../idocumentinfo)
* namespace [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.signature.dll -->
