---
title: PdfDigitalSignatureAppearance
second_title: GroupDocs.Signature for .NET API Reference
description: Describes appearance of Digital Signature are on PDF documents.
type: docs
weight: 1130
url: /net/groupdocs.signature.options.appearances/pdfdigitalsignatureappearance/
---
## PdfDigitalSignatureAppearance class

Describes appearance of Digital Signature are on PDF documents.

```csharp
public sealed class PdfDigitalSignatureAppearance : SignatureAppearance
```

## Constructors

| Name | Description |
| --- | --- |
| [PdfDigitalSignatureAppearance](pdfdigitalsignatureappearance)() | Creates signature appearance object with default values. |

## Properties

| Name | Description |
| --- | --- |
| [Background](../../groupdocs.signature.options.appearances/pdfdigitalsignatureappearance/background) { get; set; } | Get or set background color of signature appearance. By default the value is SystemColors.Windows |
| [ContactInfoLabel](../../groupdocs.signature.options.appearances/pdfdigitalsignatureappearance/contactinfolabel) { get; set; } | Gets or sets contact info label. Default value: "Contact". if this value is empty then no contact label will appear on digital signature area. |
| [DateSignedAtLabel](../../groupdocs.signature.options.appearances/pdfdigitalsignatureappearance/datesignedatlabel) { get; set; } | Gets or sets date signed label. Default value: "Date". |
| [DigitalSignedLabel](../../groupdocs.signature.options.appearances/pdfdigitalsignatureappearance/digitalsignedlabel) { get; set; } | Gets or sets digital signed label. Default value: "Digitally signed by". |
| [FontFamilyName](../../groupdocs.signature.options.appearances/pdfdigitalsignatureappearance/fontfamilyname) { get; set; } | Gets or sets the Font family name to display the labels. Default value is "Arial". |
| [FontSize](../../groupdocs.signature.options.appearances/pdfdigitalsignatureappearance/fontsize) { get; set; } | Gets or sets the Font size to display the labels. Default value is 10. |
| [Foreground](../../groupdocs.signature.options.appearances/pdfdigitalsignatureappearance/foreground) { get; set; } | Get or set foreground text color of signature appearance. By default the value is Color.FromArgb(76, 100, 255) |
| [LocationLabel](../../groupdocs.signature.options.appearances/pdfdigitalsignatureappearance/locationlabel) { get; set; } | Gets or sets location label. Default value: "Location". if this value is empty then no location label will appear on digital signature area. |
| [ReasonLabel](../../groupdocs.signature.options.appearances/pdfdigitalsignatureappearance/reasonlabel) { get; set; } | Gets or sets reason label. Default value: "Reason". if this value is empty then no reason label will appear on digital signature area. |

### Remarks

**Learn more**

* See more simple examples on creating digital electronic signatures with GroupDocs.Signature: [Advanced signing document with Digital electronic signatures](https://docs.groupdocs.com/signature/net/sign-document-with-digital-signature-advanced/)
* See more advanced examples of settings of various electronic signature with GroupDocs.Signature: [Advanced electronic signatures properties](https://docs.groupdocs.com/signature/net/sign-documents-with-extra-digital-signature-properties/)

### See Also

* class [SignatureAppearance](../signatureappearance)
* namespace [GroupDocs.Signature.Options.Appearances](../../groupdocs.signature.options.appearances)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->