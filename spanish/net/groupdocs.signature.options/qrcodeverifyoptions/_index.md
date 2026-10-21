---
title: "QrCodeVerifyOptions"
second_title: "Referencia de la API de GroupDocs.Signature para .NET"
description: "Mantiene opciones para verificar la firma QRcode del documento."
type: docs
weight: 1930
url: /es/net/groupdocs.signature.options/qrcodeverifyoptions/
---
## QrCodeVerifyOptions class

Mantiene opciones para verificar la firma de código QR del documento.

```csharp
public class QrCodeVerifyOptions : TextVerifyOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [QrCodeVerifyOptions](qrcodeverifyoptions#constructor)() | Crea la opción de verificación QrCodeVerifyOptions para firmas de código QR. |
| [QrCodeVerifyOptions](qrcodeverifyoptions#constructor_1)(string) | Crea la opción de verificación QrCodeVerifyOptions para firmas de código QR con texto de código QR a verificar. |
| [QrCodeVerifyOptions](qrcodeverifyoptions#constructor_2)(string, QrCodeType) | Crea la opción de verificación QrCodeVerifyOptions para firmas QR-Code con texto y tipo de codificación QR-Code para verificar. |

## Properties

| Nombre | Descripción |
| --- | --- |
| [AllPages](../../groupdocs.signature.options/verifyoptions/allpages) { get; set; } | Indicador para verificar cada página del documento. Por defecto el valor es true. |
| [DataEncryption](../../groupdocs.signature.options/qrcodeverifyoptions/dataencryption) { get; set; } | Obtiene o establece la implementación de la interfaz [`IDataEncryption`](../../groupdocs.signature.domain.extensions/idataencryption) para codificar y decodificar las propiedades de Texto de la Firma QR-Code. |
| [EncodeType](../../groupdocs.signature.options/qrcodeverifyoptions/encodetype) { get; set; } | Obtiene o establece la verificación del Tipo QR-code. Esta propiedad es opcional. |
| [Extensions](../../groupdocs.signature.options/verifyoptions/extensions) { get; set; } | Extensiones adicionales para la verificación de opciones de firma alternativas. |
| [FormTextFieldTitle](../../groupdocs.signature.options/textverifyoptions/formtextfieldtitle) { get; set; } | Obtiene o establece el título del campo de formulario para verificarlo. Si esta propiedad está establecida, el texto se encontrará solo en los campos de formulario de texto. |
| [FormTextFieldType](../../groupdocs.signature.options/textverifyoptions/formtextfieldtype) { get; set; } | Obtiene o establece el tipo de campo de formulario para verificarlo. Si esta propiedad se establece, el texto solo se encontrará en campos de formulario de texto. |
| [IsValid](../../groupdocs.signature.options/verifyoptions/isvalid) { get; } | Indicador de propiedad válida. |
| [MatchType](../../groupdocs.signature.options/textverifyoptions/matchtype) { get; set; } | Obtiene o establece la verificación del tipo de coincidencia de texto. |
| virtual [PageNumber](../../groupdocs.signature.options/verifyoptions/pagenumber) { get; set; } | Número de página del documento a verificar. Si la propiedad no está establecida, se verificarán todas las páginas del documento para la primera aparición. El valor mínimo es 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/verifyoptions/pagessetup) { get; set; } | Opciones de página para especificar las páginas a verificar. |
| [ShapePosition](../../groupdocs.signature.options/verifyoptions/shapeposition) { get; set; } | Especifica la posición de la forma en el diseño del documento. Para verificar firmas en encabezados/pies de página. |
| [SignatureID](../../groupdocs.signature.options/textverifyoptions/signatureid) { get; set; } | Especifique un ID de firma de texto mayor que cero si debe verificarse. Esta propiedad solo es compatible con documentos PDF. |
| [SignatureImplementation](../../groupdocs.signature.options/textverifyoptions/signatureimplementation) { get; set; } | Tipo de firma a verificar. |
| [Text](../../groupdocs.signature.options/textverifyoptions/text) { get; set; } | Especifique el texto de la firma si debe verificarse. |

### Observaciones

**Learn more**

* Basic usage of verification for QR-code electronic signature by GroupDocs.Signature: [How to eVerification QR-code signatures in a document ](https://docs.groupdocs.com/display/signaturenet/Verify+QR-code+signatures+in+the+document)
* Advanced usage of settings of verification for QR-code electronic signature with GroupDocs.Signature: [Advanced usage of eVerification QR-code signatures in a document and additional settings](https://docs.groupdocs.com/display/signaturenet/Verify+QR-code+signatures)

### Ver también

* class [TextVerifyOptions](../textverifyoptions)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.signature.dll -->
