---
title: "DigitalVerifyOptions"
second_title: "GroupDocs.Signature per .NET Riferimento API"
description: "Conserva le opzioni per verificare la firma digitale del documento."
type: docs
weight: 1570
url: /it/net/groupdocs.signature.options/digitalverifyoptions/
---
## DigitalVerifyOptions class

Conserva le opzioni per verificare la firma digitale del documento.

```csharp
public class DigitalVerifyOptions : VerifyOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [DigitalVerifyOptions](digitalverifyoptions#constructor)() | Crea un'opzione di verifica digitale con valori predefiniti. |
| [DigitalVerifyOptions](digitalverifyoptions#constructor_1)(Stream) | Crea un'opzione di verifica digitale con lo stream del certificato fornito. |
| [DigitalVerifyOptions](digitalverifyoptions#constructor_2)(string) | Crea un'opzione di verifica digitale con il percorso file del certificato digitale fornito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AllPages](../../groupdocs.signature.options/verifyoptions/allpages) { get; set; } | Flag per verificare ogni pagina del documento. Il valore predefinito è true. |
| [Certificate](../../groupdocs.signature.options/digitalverifyoptions/certificate) { get; } | Ottieni il certificato X509Certificate2 dal percorso file del certificato o dallo stream. |
| [CertificateFilePath](../../groupdocs.signature.options/digitalverifyoptions/certificatefilepath) { get; set; } | Percorso file del certificato digitale. |
| [CertificateStream](../../groupdocs.signature.options/digitalverifyoptions/certificatestream) { get; set; } | Stream del certificato digitale. |
| [Comments](../../groupdocs.signature.options/digitalverifyoptions/comments) { get; set; } | Commenti della firma digitale da convalidare. |
| [Contact](../../groupdocs.signature.options/digitalverifyoptions/contact) { get; set; } | Contatto della firma da convalidare. |
| [Extensions](../../groupdocs.signature.options/verifyoptions/extensions) { get; set; } | Estensioni aggiuntive per la verifica di opzioni di firma alternative. |
| [IssuerName](../../groupdocs.signature.options/digitalverifyoptions/issuername) { get; set; } | Nome dell'emittente del certificato da convalidare. Il valore è sensibile al maiuscolo/minuscolo. Se questa proprietà è impostata, la verifica controllerà se il nome dell'emittente della firma contiene o è uguale al valore fornito. |
| [IsValid](../../groupdocs.signature.options/verifyoptions/isvalid) { get; } | Flag di proprietà valido. |
| [Location](../../groupdocs.signature.options/digitalverifyoptions/location) { get; set; } | Posizione della firma da convalidare. |
| virtual [PageNumber](../../groupdocs.signature.options/verifyoptions/pagenumber) { get; set; } | Numero di pagina del documento da verificare. Se la proprietà non è impostata, tutte le pagine del documento saranno verificate per la prima occorrenza. Il valore minimo è 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/verifyoptions/pagessetup) { get; set; } | Opzioni di pagina per specificare le pagine da verificare. |
| [Password](../../groupdocs.signature.options/digitalverifyoptions/password) { get; set; } | Password del certificato digitale, se necessaria. |
| [Reason](../../groupdocs.signature.options/digitalverifyoptions/reason) { get; set; } | Motivo della firma digitale da convalidare. |
| [ShapePosition](../../groupdocs.signature.options/verifyoptions/shapeposition) { get; set; } | Specifica la posizione della forma nel layout del documento. Per verificare le firme in intestazioni/piè di pagina. |
| [SignDateTimeFrom](../../groupdocs.signature.options/digitalverifyoptions/signdatetimefrom) { get; set; } | Intervallo di data e ora della firma digitale da convalidare. Il valore nullo verrà ignorato. |
| [SignDateTimeTo](../../groupdocs.signature.options/digitalverifyoptions/signdatetimeto) { get; set; } | Intervallo di data e ora della firma digitale da convalidare. Il valore nullo verrà ignorato. |
| [SubjectName](../../groupdocs.signature.options/digitalverifyoptions/subjectname) { get; set; } | Nome distinto del soggetto del certificato da convalidare. Il valore è sensibile al maiuscolo/minuscolo. Se questa proprietà è impostata, la verifica controllerà se il nome del soggetto della firma contiene o è uguale al valore fornito. |

### Osservazioni

**Learn more**

* Basic usage of verification for Digital electronic signature by GroupDocs.Signature: [How to eVerification Digital signatures in a document ](https://docs.groupdocs.com/display/signaturenet/Verify+Digital+signatures+in+the+document)
* Advanced usage of settings of verification for Digital electronic signature with GroupDocs.Signature: [Advanced usage of eVerification Digital signatures in a document and additional settings]()

### Vedi anche

* class [VerifyOptions](../verifyoptions)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.signature.dll -->
