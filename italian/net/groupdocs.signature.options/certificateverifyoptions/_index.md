---
title: "CertificateVerifyOptions"
second_title: "GroupDocs.Signature per .NET Riferimento API"
description: "Conserva le opzioni per verificare i documenti del certificato."
type: docs
weight: 1500
url: /it/net/groupdocs.signature.options/certificateverifyoptions/
---
## CertificateVerifyOptions class

Conserva le opzioni per verificare i documenti del certificato.

```csharp
public class CertificateVerifyOptions : VerifyOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [CertificateVerifyOptions](certificateverifyoptions#constructor)() | Inizializza una nuova istanza di TextVerifyOptions con i valori predefiniti. |
| [CertificateVerifyOptions](certificateverifyoptions#constructor_1)(string) | Inizializza una nuova istanza di CertificateVerifyOptions con il soggetto da verificare. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AllPages](../../groupdocs.signature.options/verifyoptions/allpages) { get; set; } | Flag per verificare ogni pagina del documento. Il valore predefinito è true. |
| [Expired](../../groupdocs.signature.options/certificateverifyoptions/expired) { get; } | Indica se il certificato è scaduto in base al risultato della convalida. La proprietà è di sola lettura. |
| [Extensions](../../groupdocs.signature.options/verifyoptions/extensions) { get; set; } | Estensioni aggiuntive per la verifica di opzioni di firma alternative. |
| [Issuer](../../groupdocs.signature.options/certificateverifyoptions/issuer) { get; set; } | Specifica l'emittente del certificato se deve essere verificato. |
| [IsValid](../../groupdocs.signature.options/verifyoptions/isvalid) { get; } | Flag di proprietà valido. |
| [MatchType](../../groupdocs.signature.options/certificateverifyoptions/matchtype) { get; set; } | Ottiene o imposta la verifica del tipo di corrispondenza del testo. |
| virtual [PageNumber](../../groupdocs.signature.options/verifyoptions/pagenumber) { get; set; } | Numero di pagina del documento da verificare. Se la proprietà non è impostata, tutte le pagine del documento saranno verificate per la prima occorrenza. Il valore minimo è 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/verifyoptions/pagessetup) { get; set; } | Opzioni di pagina per specificare le pagine da verificare. |
| [PerformChainValidation](../../groupdocs.signature.options/certificateverifyoptions/performchainvalidation) { get; set; } | Ottieni o imposta se il processo di verifica deve fornire la convalida della catena X.509 usando la politica di convalida di base. Per impostazione predefinita questo valore è true. |
| [SerialNumber](../../groupdocs.signature.options/certificateverifyoptions/serialnumber) { get; set; } | Specifica il numero di serie del certificato se deve essere verificato. |
| [ShapePosition](../../groupdocs.signature.options/verifyoptions/shapeposition) { get; set; } | Specifica la posizione della forma nel layout del documento. Per verificare le firme in intestazioni/piè di pagina. |
| [Subject](../../groupdocs.signature.options/certificateverifyoptions/subject) { get; set; } | Specifica il soggetto del certificato se deve essere verificato. |
| [Thumbprint](../../groupdocs.signature.options/certificateverifyoptions/thumbprint) { get; set; } | Specifica l'impronta digitale del certificato se deve essere verificato. |

### Osservazioni

**Learn more**

* Basic usage of certificate documents by GroupDocs.Signature: [Preview Digital Certificates properties](https://docs.groupdocs.com/signature/net/preview-certificate-properties/)

### Vedi anche

* class [VerifyOptions](../verifyoptions)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.signature.dll -->
