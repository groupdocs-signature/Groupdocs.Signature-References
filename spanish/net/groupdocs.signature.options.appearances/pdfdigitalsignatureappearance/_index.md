---
title: "PdfDigitalSignatureAppearance"
second_title: "Referencia de la API de GroupDocs.Signature para .NET"
description: "Describe la apariencia de la Firma Digital en documentos PDF."
type: docs
weight: 1400
url: /es/net/groupdocs.signature.options.appearances/pdfdigitalsignatureappearance/
---
## PdfDigitalSignatureAppearance class

Describe la apariencia de la Firma Digital en documentos PDF.

```csharp
public sealed class PdfDigitalSignatureAppearance : SignatureAppearance
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [PdfDigitalSignatureAppearance](pdfdigitalsignatureappearance)() | Crea un objeto de apariencia de firma con valores predeterminados. |

## Properties

| Nombre | Descripción |
| --- | --- |
| [Background](../../groupdocs.signature.options.appearances/pdfdigitalsignatureappearance/background) { get; set; } | Obtiene o establece el color de fondo de la apariencia de la firma. Por defecto, el valor es SystemColors.Windows |
| [ContactInfoLabel](../../groupdocs.signature.options.appearances/pdfdigitalsignatureappearance/contactinfolabel) { get; set; } | Obtiene o establece la etiqueta de información de contacto. Valor predeterminado: "Contact". Si este valor está vacío, no aparecerá ninguna etiqueta de contacto en el área de firma digital. |
| [DateSignedAtLabel](../../groupdocs.signature.options.appearances/pdfdigitalsignatureappearance/datesignedatlabel) { get; set; } | Obtiene o establece la etiqueta de fecha de firma. Valor predeterminado: "Date". |
| [DigitalSignedLabel](../../groupdocs.signature.options.appearances/pdfdigitalsignatureappearance/digitalsignedlabel) { get; set; } | Obtiene o establece la etiqueta de firmado digitalmente. Valor predeterminado: "Digitally signed by". |
| [FontFamilyName](../../groupdocs.signature.options.appearances/pdfdigitalsignatureappearance/fontfamilyname) { get; set; } | Obtiene o establece el nombre de la familia de fuentes para mostrar las etiquetas. El valor predeterminado es "Arial". |
| [FontSize](../../groupdocs.signature.options.appearances/pdfdigitalsignatureappearance/fontsize) { get; set; } | Obtiene o establece el tamaño de la fuente para mostrar las etiquetas. El valor predeterminado es 10. |
| [Foreground](../../groupdocs.signature.options.appearances/pdfdigitalsignatureappearance/foreground) { get; set; } | Obtiene o establece el color del texto en primer plano de la apariencia de la firma. Por defecto, el valor es Color.FromArgb(76, 100, 255) |
| [IsForegroundImage](../../groupdocs.signature.options.appearances/pdfdigitalsignatureappearance/isforegroundimage) { get; set; } | Obtiene o establece un valor que indica si la imagen en la apariencia de la firma se dibuja como una imagen en primer plano. Valor predeterminado: false. |
| [LocationLabel](../../groupdocs.signature.options.appearances/pdfdigitalsignatureappearance/locationlabel) { get; set; } | Obtiene o establece la etiqueta de ubicación. Valor predeterminado: "Location". Si este valor está vacío, no aparecerá ninguna etiqueta de ubicación en el área de firma digital. |
| [ReasonLabel](../../groupdocs.signature.options.appearances/pdfdigitalsignatureappearance/reasonlabel) { get; set; } | Obtiene o establece la etiqueta de motivo. Valor predeterminado: "Reason". Si este valor está vacío, no aparecerá ninguna etiqueta de motivo en el área de firma digital. |

### Observaciones

**Learn more**

* See more simple examples on creating digital electronic signatures with GroupDocs.Signature: [Advanced signing document with Digital electronic signatures](https://docs.groupdocs.com/signature/net/sign-document-with-digital-signature-advanced/)
* See more advanced examples of settings of various electronic signature with GroupDocs.Signature: [Advanced electronic signatures properties](https://docs.groupdocs.com/signature/net/sign-documents-with-extra-digital-signature-properties/)

### Ver también

* class [SignatureAppearance](../signatureappearance)
* namespace [GroupDocs.Signature.Options.Appearances](../../groupdocs.signature.options.appearances)
* assembly [GroupDocs.Signature](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.signature.dll -->
