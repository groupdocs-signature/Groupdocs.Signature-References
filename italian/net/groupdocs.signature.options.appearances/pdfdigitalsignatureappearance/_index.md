---
title: "PdfDigitalSignatureAppearance"
second_title: "GroupDocs.Signature per .NET Riferimento API"
description: "Descrive l'aspetto della firma digitale nei documenti PDF."
type: docs
weight: 1400
url: /it/net/groupdocs.signature.options.appearances/pdfdigitalsignatureappearance/
---
## PdfDigitalSignatureAppearance class

Descrive l'aspetto della firma digitale nei documenti PDF.

```csharp
public sealed class PdfDigitalSignatureAppearance : SignatureAppearance
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [PdfDigitalSignatureAppearance](pdfdigitalsignatureappearance)() | Crea l'oggetto di aspetto della firma con i valori predefiniti. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Background](../../groupdocs.signature.options.appearances/pdfdigitalsignatureappearance/background) { get; set; } | Ottieni o imposta il colore di sfondo dell'aspetto della firma. Per impostazione predefinita il valore è SystemColors.Windows |
| [ContactInfoLabel](../../groupdocs.signature.options.appearances/pdfdigitalsignatureappearance/contactinfolabel) { get; set; } | Ottiene o imposta l'etichetta delle informazioni di contatto. Valore predefinito: "Contact". Se questo valore è vuoto, nessuna etichetta di contatto verrà visualizzata nell'area della firma digitale. |
| [DateSignedAtLabel](../../groupdocs.signature.options.appearances/pdfdigitalsignatureappearance/datesignedatlabel) { get; set; } | Ottiene o imposta l'etichetta della data di firma. Valore predefinito: "Date". |
| [DigitalSignedLabel](../../groupdocs.signature.options.appearances/pdfdigitalsignatureappearance/digitalsignedlabel) { get; set; } | Ottiene o imposta l'etichetta di firma digitale. Valore predefinito: "Digitally signed by". |
| [FontFamilyName](../../groupdocs.signature.options.appearances/pdfdigitalsignatureappearance/fontfamilyname) { get; set; } | Ottiene o imposta il nome della famiglia di caratteri per visualizzare le etichette. Il valore predefinito è "Arial". |
| [FontSize](../../groupdocs.signature.options.appearances/pdfdigitalsignatureappearance/fontsize) { get; set; } | Ottiene o imposta la dimensione del carattere per visualizzare le etichette. Il valore predefinito è 10. |
| [Foreground](../../groupdocs.signature.options.appearances/pdfdigitalsignatureappearance/foreground) { get; set; } | Ottieni o imposta il colore del testo in primo piano dell'aspetto della firma. Per impostazione predefinita il valore è Color.FromArgb(76, 100, 255) |
| [IsForegroundImage](../../groupdocs.signature.options.appearances/pdfdigitalsignatureappearance/isforegroundimage) { get; set; } | Ottiene o imposta un valore che indica se l'immagine nell'aspetto della firma è disegnata come immagine in primo piano. Valore predefinito: false. |
| [LocationLabel](../../groupdocs.signature.options.appearances/pdfdigitalsignatureappearance/locationlabel) { get; set; } | Ottiene o imposta l'etichetta della posizione. Valore predefinito: "Location". Se questo valore è vuoto, nessuna etichetta di posizione verrà visualizzata nell'area della firma digitale. |
| [ReasonLabel](../../groupdocs.signature.options.appearances/pdfdigitalsignatureappearance/reasonlabel) { get; set; } | Ottiene o imposta l'etichetta del motivo. Valore predefinito: "Reason". Se questo valore è vuoto, nessuna etichetta del motivo verrà visualizzata nell'area della firma digitale. |

### Osservazioni

**Learn more**

* See more simple examples on creating digital electronic signatures with GroupDocs.Signature: [Advanced signing document with Digital electronic signatures](https://docs.groupdocs.com/signature/net/sign-document-with-digital-signature-advanced/)
* See more advanced examples of settings of various electronic signature with GroupDocs.Signature: [Advanced electronic signatures properties](https://docs.groupdocs.com/signature/net/sign-documents-with-extra-digital-signature-properties/)

### Vedi anche

* class [SignatureAppearance](../signatureappearance)
* namespace [GroupDocs.Signature.Options.Appearances](../../groupdocs.signature.options.appearances)
* assembly [GroupDocs.Signature](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.signature.dll -->
