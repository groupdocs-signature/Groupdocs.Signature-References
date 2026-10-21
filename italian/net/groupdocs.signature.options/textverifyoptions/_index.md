---
title: "TextVerifyOptions"
second_title: "GroupDocs.Signature per .NET Riferimento API"
description: "Mantiene le opzioni per verificare la firma Text del documento."
type: docs
weight: 2030
url: /it/net/groupdocs.signature.options/textverifyoptions/
---
## TextVerifyOptions class

Mantiene le opzioni per verificare la firma Text del documento.

```csharp
public class TextVerifyOptions : VerifyOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [TextVerifyOptions](textverifyoptions#constructor)() | Inizializza una nuova istanza di TextVerifyOptions con i valori predefiniti. |
| [TextVerifyOptions](textverifyoptions#constructor_1)(string) | Inizializza una nuova istanza di TextVerifyOptions con il testo di verifica. |
| [TextVerifyOptions](textverifyoptions#constructor_2)(string, TextSignatureImplementation) | Inizializza una nuova istanza di TextVerifyOptions con la proprietà Text da verificare e l'implementazione della firma. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AllPages](../../groupdocs.signature.options/verifyoptions/allpages) { get; set; } | Flag per verificare ogni pagina del documento. Il valore predefinito è true. |
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

* Basic usage of verification for Barcode electronic signature by GroupDocs.Signature: [How to eVerification Barcode signatures in a document ](https://docs.groupdocs.com/display/signaturenet/Verify+Text+signatures+in+the+document)
* Advanced usage of settings of verification for Barcode electronic signature with GroupDocs.Signature: [Advanced usage of eVerification Barcode signatures in a document and additional settings](https://docs.groupdocs.com/display/signaturenet/Verify+Text+signatures)

### Vedi anche

* class [VerifyOptions](../verifyoptions)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.signature.dll -->
