---
title: IDocumentInfo
second_title: Riferimento API GroupDocs.Signature per .NET
description: Definisce le proprietà della descrizione del documento.
type: docs
weight: 490
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
| [BarcodeSignatures](../../groupdocs.signature.domain/idocumentinfo/barcodesignatures) { get; } | Raccolta delle firme dei codici a barre dei documenti aggiunte o aggiornate da[`Signature`](../../groupdocs.signature/signature) metodi. |
| [DigitalSignatures](../../groupdocs.signature.domain/idocumentinfo/digitalsignatures) { get; } | Raccolta delle firme digitali dei documenti aggiunte o aggiornate da[`Signature`](../../groupdocs.signature/signature) metodi. |
| [FileType](../../groupdocs.signature.domain/idocumentinfo/filetype) { get; set; } | Tipo formato file |
| [FormFields](../../groupdocs.signature.domain/idocumentinfo/formfields) { get; } | Raccolta di tutti i campi modulo supportati esistenti nel documento. Questa proprietà è supportata solo per i tipi di documento Pdf ed Elaborazione testi. |
| [FormFieldSignatures](../../groupdocs.signature.domain/idocumentinfo/formfieldsignatures) { get; } | Raccolta documenti Form Field firme aggiunte o aggiornate da[`Signature`](../../groupdocs.signature/signature) metodi. |
| [ImageSignatures](../../groupdocs.signature.domain/idocumentinfo/imagesignatures) { get; } | Raccolta di firme di immagini di documenti aggiunte o aggiornate da[`Signature`](../../groupdocs.signature/signature) metodi. |
| [MaxPageHeight](../../groupdocs.signature.domain/idocumentinfo/maxpageheight) { get; set; } | Specifica l'altezza massima della pagina. |
| [PageCount](../../groupdocs.signature.domain/idocumentinfo/pagecount) { get; set; } | Conteggio delle pagine del documento. |
| [Pages](../../groupdocs.signature.domain/idocumentinfo/pages) { get; set; } | Raccolta delle descrizioni delle pagine del documento. |
| [ProcessLogs](../../groupdocs.signature.domain/idocumentinfo/processlogs) { get; } | Raccolta dei log del processo di cronologia dei documenti. |
| [QrCodeSignatures](../../groupdocs.signature.domain/idocumentinfo/qrcodesignatures) { get; } | Raccolta delle firme del codice QR del documento aggiunte o aggiornate da[`Signature`](../../groupdocs.signature/signature) metodi. |
| [Signatures](../../groupdocs.signature.domain/idocumentinfo/signatures) { get; } | Raccolta di documenti di tutti i tipi di firme[`BaseSignature`](../basesignature) . |
| [Size](../../groupdocs.signature.domain/idocumentinfo/size) { get; set; } | Dimensioni del documento in byte. |
| [TextSignatures](../../groupdocs.signature.domain/idocumentinfo/textsignatures) { get; } | Raccolta di firme di testo del documento aggiunte o aggiornate da[`Signature`](../../groupdocs.signature/signature) metodi. |
| [WidthForMaxHeight](../../groupdocs.signature.domain/idocumentinfo/widthformaxheight) { get; set; } | Specifica la larghezza per l'altezza massima della pagina. |

### Guarda anche

* spazio dei nomi [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assemblea [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->