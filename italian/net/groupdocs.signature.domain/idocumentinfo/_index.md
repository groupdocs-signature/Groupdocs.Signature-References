---
title: "IDocumentInfo"
second_title: "GroupDocs.Signature per .NET Riferimento API"
description: "Definisce le proprietà della descrizione del documento."
type: docs
weight: 680
url: /it/net/groupdocs.signature.domain/idocumentinfo/
---
## IDocumentInfo interface

Definisce le proprietà della descrizione del documento.

```csharp
public interface IDocumentInfo
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [BarcodeSignatures](../../groupdocs.signature.domain/idocumentinfo/barcodesignatures) { get; } | Raccolta di firme barcode del documento aggiunte o aggiornate dai metodi [`Signature`](../../groupdocs.signature/signature). |
| [DigitalSignatures](../../groupdocs.signature.domain/idocumentinfo/digitalsignatures) { get; } | Raccolta di firme digitali del documento aggiunte o aggiornate dai metodi [`Signature`](../../groupdocs.signature/signature). |
| [Documents](../../groupdocs.signature.domain/idocumentinfo/documents) { get; } | Raccolta di tutti i documenti esistenti all'interno dei file di archivio. Questa proprietà è supportata solo per i tipi di documento Archive. |
| [FileType](../../groupdocs.signature.domain/idocumentinfo/filetype) { get; set; } | Tipo di formato file |
| [FormFields](../../groupdocs.signature.domain/idocumentinfo/formfields) { get; } | Raccolta di tutti i campi modulo supportati esistenti nel documento. Questa proprietà è supportata solo per i tipi di documento Pdf e Word Processing. |
| [FormFieldSignatures](../../groupdocs.signature.domain/idocumentinfo/formfieldsignatures) { get; } | Raccolta di firme di campi modulo del documento aggiunte o aggiornate dai metodi [`Signature`](../../groupdocs.signature/signature). |
| [ImageSignatures](../../groupdocs.signature.domain/idocumentinfo/imagesignatures) { get; } | Raccolta di firme immagine del documento aggiunte o aggiornate dai metodi [`Signature`](../../groupdocs.signature/signature). |
| [MaxPageHeight](../../groupdocs.signature.domain/idocumentinfo/maxpageheight) { get; set; } | Specifica l'altezza massima della pagina. |
| [MetadataSignatures](../../groupdocs.signature.domain/idocumentinfo/metadatasignatures) { get; } | Raccolta di firme di metadati del documento. |
| [PageCount](../../groupdocs.signature.domain/idocumentinfo/pagecount) { get; set; } | Conteggio delle pagine del documento. |
| [Pages](../../groupdocs.signature.domain/idocumentinfo/pages) { get; set; } | Raccolta di descrizioni delle pagine del documento. |
| [ProcessLogs](../../groupdocs.signature.domain/idocumentinfo/processlogs) { get; } | Raccolta dei log di processo della cronologia del documento. |
| [QrCodeSignatures](../../groupdocs.signature.domain/idocumentinfo/qrcodesignatures) { get; } | Raccolta di firme QR-code del documento aggiunte o aggiornate dai metodi [`Signature`](../../groupdocs.signature/signature). |
| [Signatures](../../groupdocs.signature.domain/idocumentinfo/signatures) { get; } | Raccolta di firme di tutti i tipi di documento [`BaseSignature`](../basesignature). |
| [Size](../../groupdocs.signature.domain/idocumentinfo/size) { get; set; } | Dimensione del documento in byte. |
| [TextSignatures](../../groupdocs.signature.domain/idocumentinfo/textsignatures) { get; } | Raccolta di firme di testo del documento aggiunte o aggiornate dai metodi [`Signature`](../../groupdocs.signature/signature). |
| [WidthForMaxHeight](../../groupdocs.signature.domain/idocumentinfo/widthformaxheight) { get; set; } | Specifica la larghezza per l'altezza massima della pagina. |

### Vedi anche

* namespace [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.signature.dll -->
