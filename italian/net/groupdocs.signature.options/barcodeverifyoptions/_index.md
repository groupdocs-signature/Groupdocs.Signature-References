---
title: "BarcodeVerifyOptions"
second_title: "GroupDocs.Signature per .NET Riferimento API"
description: "Rappresenta le opzioni di verifica Barcode."
type: docs
weight: 1460
url: /it/net/groupdocs.signature.options/barcodeverifyoptions/
---
## BarcodeVerifyOptions class

Rappresenta le opzioni di verifica Barcode.

```csharp
public class BarcodeVerifyOptions : TextVerifyOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [BarcodeVerifyOptions](barcodeverifyoptions#constructor)() | Crea l'opzione di verifica predefinita per la firma Barcode. |
| [BarcodeVerifyOptions](barcodeverifyoptions#constructor_1)(BarcodeType) | Crea l'opzione di verifica predefinita con verifica del tipo Barcode |
| [BarcodeVerifyOptions](barcodeverifyoptions#constructor_2)(string) | Crea l'opzione di verifica predefinita con testo di verifica |
| [BarcodeVerifyOptions](barcodeverifyoptions#constructor_3)(string, BarcodeType) | Crea l'opzione di verifica predefinita con verifica del tipo Barcode e testo |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AllPages](../../groupdocs.signature.options/verifyoptions/allpages) { get; set; } | Flag per verificare ogni pagina del documento. Il valore predefinito è true. |
| [EncodeType](../../groupdocs.signature.options/barcodeverifyoptions/encodetype) { get; set; } | Ottiene o imposta la verifica del tipo Barcode. |
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

* Basic usage of verification for Barcode electronic signature by GroupDocs.Signature: [How to eVerification Barcode signatures in a document ](https://docs.groupdocs.com/display/signaturenet/Verify+Barcode+signatures+in+the+document)
* Advanced usage of settings of verification for Barcode electronic signature with GroupDocs.Signature: [Advanced usage of eVerification Barcode signatures in a document and additional settings]()

### Vedi anche

* class [TextVerifyOptions](../textverifyoptions)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.signature.dll -->
