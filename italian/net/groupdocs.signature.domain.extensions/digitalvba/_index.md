---
title: "DigitalVBA"
second_title: "GroupDocs.Signature per .NET Riferimento API"
description: "Rappresenta la firma digitale per i progetti VBA di fogli di calcolo. Fornisce la possibilità di firmare il progetto VBA in formati di documento di fogli di calcolo specifici come Xlsm o Xltm. Se diverse estensioni DigitalVBA vengono aggiunte a DigitalSignOptions.Extensions, solo la prima è coinvolta nella firma del documento."
type: docs
weight: 240
url: /it/net/groupdocs.signature.domain.extensions/digitalvba/
---
## DigitalVBA class

Rappresenta la firma digitale per i progetti VBA di fogli di calcolo. Fornisce la possibilità di firmare il progetto VBA in formati di documento di fogli di calcolo specifici come Xlsm o Xltm. Se diverse estensioni DigitalVBA vengono aggiunte a DigitalSignOptions.Extensions, solo la prima è coinvolta nella firma del documento.

```csharp
public class DigitalVBA : SignatureExtension
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [DigitalVBA](digitalvba#constructor)(Stream, string) | Inizializza una nuova istanza della classe DigitalVBA con flusso di certificato. |
| [DigitalVBA](digitalvba#constructor_1)(string, string) | Inizializza una nuova istanza della classe DigitalVBA con file di certificato. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [CertificateFilePath](../../groupdocs.signature.domain.extensions/digitalvba/certificatefilepath) { get; } | Restituisce il percorso del file del certificato digitale. Questa proprietà è usata solo se CertificateStream non è specificato. |
| [CertificateStream](../../groupdocs.signature.domain.extensions/digitalvba/certificatestream) { get; } | Restituisce il flusso del certificato digitale. Se questa proprietà è specificata, viene sempre usata al posto di CertificateFilePath. |
| [Comments](../../groupdocs.signature.domain.extensions/digitalvba/comments) { get; set; } | Restituisce o imposta i commenti della firma. |
| [Password](../../groupdocs.signature.domain.extensions/digitalvba/password) { get; set; } | Restituisce o imposta la password del certificato digitale. |
| [SignOnlyVBAProject](../../groupdocs.signature.domain.extensions/digitalvba/signonlyvbaproject) { get; set; } | Restituisce o imposta l'impostazione per la firma solo del progetto VBA. Se impostato su true, il documento SpreadSheet non sarà firmato, ma il progetto VBA sarà firmato. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| virtual [Clone](../../groupdocs.signature.domain.extensions/signatureextension/clone)() | Ottiene una copia di questo oggetto. |

### Vedi anche

* class [SignatureExtension](../signatureextension)
* namespace [GroupDocs.Signature.Domain.Extensions](../../groupdocs.signature.domain.extensions)
* assembly [GroupDocs.Signature](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.signature.dll -->
