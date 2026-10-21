---
title: "BarcodeVerifyOptions"
second_title: "Referencia de la API de GroupDocs.Signature para .NET"
description: "Representa las opciones de verificación de código de barras."
type: docs
weight: 1460
url: /es/net/groupdocs.signature.options/barcodeverifyoptions/
---
## BarcodeVerifyOptions class

Representa las opciones de verificación de código de barras.

```csharp
public class BarcodeVerifyOptions : TextVerifyOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [BarcodeVerifyOptions](barcodeverifyoptions#constructor)() | Crea la opción de verificación predeterminada para la firma de código de barras. |
| [BarcodeVerifyOptions](barcodeverifyoptions#constructor_1)(BarcodeType) | Crea la opción de verificación predeterminada con verificación de tipo de código de barras |
| [BarcodeVerifyOptions](barcodeverifyoptions#constructor_2)(string) | Crea la opción de verificación predeterminada con texto de verificación |
| [BarcodeVerifyOptions](barcodeverifyoptions#constructor_3)(string, BarcodeType) | Crea la opción de verificación predeterminada con verificación de tipo de código de barras y texto |

## Properties

| Nombre | Descripción |
| --- | --- |
| [AllPages](../../groupdocs.signature.options/verifyoptions/allpages) { get; set; } | Indicador para verificar cada página del documento. Por defecto el valor es true. |
| [EncodeType](../../groupdocs.signature.options/barcodeverifyoptions/encodetype) { get; set; } | Obtiene o establece la verificación del tipo de código de barras. |
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

* Basic usage of verification for Barcode electronic signature by GroupDocs.Signature: [How to eVerification Barcode signatures in a document ](https://docs.groupdocs.com/display/signaturenet/Verify+Barcode+signatures+in+the+document)
* Advanced usage of settings of verification for Barcode electronic signature with GroupDocs.Signature: [Advanced usage of eVerification Barcode signatures in a document and additional settings]()

### Ver también

* class [TextVerifyOptions](../textverifyoptions)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.signature.dll -->
