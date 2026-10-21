---
title: "QrCodeVerifyOptions"
second_title: "GroupDocs.Signature per .NET Riferimento API"
description: "Mantiene le opzioni per verificare la firma QRcode del documento."
type: docs
weight: 1930
url: /it/net/groupdocs.signature.options/qrcodeverifyoptions/
---
## QrCodeVerifyOptions class

Mantiene le opzioni per verificare la firma QR-code del documento.

```csharp
public class QrCodeVerifyOptions : TextVerifyOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [QrCodeVerifyOptions](qrcodeverifyoptions#constructor)() | Crea l'opzione di verifica QrCodeVerifyOptions per le firme QR-Code. |
| [QrCodeVerifyOptions](qrcodeverifyoptions#constructor_1)(string) | Crea l'opzione di verifica QrCodeVerifyOptions per le firme QR-Code con il testo QR-Code da verificare. |
| [QrCodeVerifyOptions](qrcodeverifyoptions#constructor_2)(string, QrCodeType) | Crea l'opzione di verifica QrCodeVerifyOptions per le firme QR-Code con testo e tipo di codifica QR-Code da verificare. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AllPages](../../groupdocs.signature.options/verifyoptions/allpages) { get; set; } | Flag per verificare ogni pagina del documento. Il valore predefinito è true. |
| [DataEncryption](../../groupdocs.signature.options/qrcodeverifyoptions/dataencryption) { get; set; } | Ottiene o imposta l'implementazione dell'interfaccia [`IDataEncryption`](../../groupdocs.signature.domain.extensions/idataencryption) per codificare e decodificare le proprietà di testo della firma QR-Code. |
| [EncodeType](../../groupdocs.signature.options/qrcodeverifyoptions/encodetype) { get; set; } | Ottiene o imposta la verifica del tipo QR-code. Questa proprietà è opzionale. |
| [Extensions](../../groupdocs.signature.options/verifyoptions/extensions) { get; set; } | Estensioni aggiuntive per la verifica di opzioni di firma alternative. |
| [FormTextFieldTitle](../../groupdocs.signature.options/textverifyoptions/formtextfieldtitle) { get; set; } | Ottiene o imposta il titolo del campo modulo da verificare. Se questa proprietà è impostata, il testo verrà trovato solo nei campi modulo di tipo testo. |
| [FormTextFieldType](../../groupdocs.signature.options/textverifyoptions/formtextfieldtype) { get; set; } | Ottiene o imposta il tipo di campo modulo da verificare. Se questa proprietà è impostata, il testo verrà trovato solo nei campi modulo di testo. |
| [IsValid](../../groupdocs.signature.options/verifyoptions/isvalid) { get; } | Flag di proprietà valido. |
| [MatchType](../../groupdocs.signature.options/textverifyoptions/matchtype) { get; set; } | Ottiene o imposta la verifica del tipo di corrispondenza del testo. |
| virtual [PageNumber](../../groupdocs.signature.options/verifyoptions/pagenumber) { get; set; } | Numero di pagina del documento da verificare. Se la proprietà non è impostata, tutte le pagine del documento saranno verificate per la prima occorrenza. Il valore minimo è 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/verifyoptions/pagessetup) { get; set; } | Opzioni di pagina per specificare le pagine da verificare. |
| [ShapePosition](../../groupdocs.signature.options/verifyoptions/shapeposition) { get; set; } | Specifica la posizione della forma nel layout del documento. Per verificare le firme in intestazioni/piè di pagina. |
| [SignatureID](../../groupdocs.signature.options/textverifyoptions/signatureid) { get; set; } | Specificare un ID della firma di testo maggiore di zero se deve essere verificato. Questa proprietà è supportata solo per i documenti PDF. |
| [SignatureImplementation](../../groupdocs.signature.options/textverifyoptions/signatureimplementation) { get; set; } | Tipo di firma da verificare. |
| [Text](../../groupdocs.signature.options/textverifyoptions/text) { get; set; } | Specificare il testo della firma se deve essere verificato. |

### Osservazioni

**Learn more**

* Basic usage of verification for QR-code electronic signature by GroupDocs.Signature: [How to eVerification QR-code signatures in a document ](https://docs.groupdocs.com/display/signaturenet/Verify+QR-code+signatures+in+the+document)
* Advanced usage of settings of verification for QR-code electronic signature with GroupDocs.Signature: [Advanced usage of eVerification QR-code signatures in a document and additional settings](https://docs.groupdocs.com/display/signaturenet/Verify+QR-code+signatures)

### Vedi anche

* class [TextVerifyOptions](../textverifyoptions)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.signature.dll -->
