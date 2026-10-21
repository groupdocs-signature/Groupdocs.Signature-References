---
title: "DigitalSignOptions"
second_title: "Referencia de la API de GroupDocs.Signature para .NET"
description: "Representa las opciones de firma digital."
type: docs
weight: 1560
url: /es/net/groupdocs.signature.options/digitalsignoptions/
---
## DigitalSignOptions class

Representa las opciones de firma digital.

```csharp
public class DigitalSignOptions : ImageSignOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [DigitalSignOptions](digitalsignoptions#constructor)() | Inicializa una nueva instancia de la clase DigitalSignOptions con valores predeterminados. |
| [DigitalSignOptions](digitalsignoptions#constructor_1)(Stream) | Inicializa una nueva instancia de la clase DigitalSignOptions con un flujo de certificado. |
| [DigitalSignOptions](digitalsignoptions#constructor_4)(string) | Inicializa una nueva instancia de la clase DigitalSignOptions con un archivo de certificado. |
| [DigitalSignOptions](digitalsignoptions#constructor_2)(Stream, Stream) | Inicializa una nueva instancia de la clase DigitalSignOptions con un flujo de certificado y un flujo de imagen. |
| [DigitalSignOptions](digitalsignoptions#constructor_3)(Stream, string) | Inicializa una nueva instancia de la clase DigitalSignOptions con un flujo de certificado y un archivo de imagen. |
| [DigitalSignOptions](digitalsignoptions#constructor_5)(string, Stream) | Inicializa una nueva instancia de la clase DigitalSignOptions con un archivo de certificado y un flujo de imagen. |
| [DigitalSignOptions](digitalsignoptions#constructor_6)(string, string) | Inicializa una nueva instancia de la clase DigitalSignOptions con un archivo de certificado y un archivo de imagen. |

## Properties

| Nombre | Descripción |
| --- | --- |
| [AllowExpired](../../groupdocs.signature.options/digitalsignoptions/allowexpired) { get; set; } | Obtiene o establece una bandera que permite firmar con un certificado cuyo período de validez ha finalizado. El valor predeterminado es false: firmar con un certificado expirado lanza [`GroupDocsSignatureException`](../../groupdocs.signature/groupdocssignatureexception), y el documento no se firma. |
| [AllowNotYetValid](../../groupdocs.signature.options/digitalsignoptions/allownotyetvalid) { get; set; } | Obtiene o establece una bandera que permite firmar con un certificado cuyo período de validez aún no ha comenzado. El valor predeterminado es false: firmar con dicho certificado lanza [`GroupDocsSignatureException`](../../groupdocs.signature/groupdocssignatureexception), y el documento no se firma. |
| virtual [AllPages](../../groupdocs.signature.options/signoptions/allpages) { get; set; } | Coloca la firma en todas las páginas del documento. |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | Apariencia adicional de la firma. |
| [Border](../../groupdocs.signature.options/imagesignoptions/border) { get; set; } | Especificar la configuración del borde |
| [CertificateFilePath](../../groupdocs.signature.options/digitalsignoptions/certificatefilepath) { get; set; } | Obtiene o establece la ruta del archivo del certificado digital. Esta propiedad se usa solo si CertificateStream no está especificado. |
| [CertificateStream](../../groupdocs.signature.options/digitalsignoptions/certificatestream) { get; set; } | Obtiene o establece el flujo del certificado digital. Si se especifica esta propiedad, siempre se usa en lugar de CertificateFilePath. |
| [Contact](../../groupdocs.signature.options/digitalsignoptions/contact) { get; set; } | Obtiene o establece el contacto de la firma. |
| [CustomSignHash](../../groupdocs.signature.options/digitalsignoptions/customsignhash) { get; set; } | Obtiene o establece una función de firma hash personalizada, que permite a los usuarios implementar su propia lógica de firma digital. Esto permite firmar con certificados externos y admite diferentes algoritmos hash. |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | Obtenga o establezca el Tipo de Documento de las Opciones de Firma [`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | Extensiones de firma. |
| [HashAlgorithm](../../groupdocs.signature.options/signoptions/hashalgorithm) { get; set; } | Obtiene o establece el algoritmo hash que se utilizará para operaciones criptográficas. Compatible exclusivamente con firmas digitales en archivos PDF. |
| [Height](../../groupdocs.signature.options/imagesignoptions/height) { get; set; } | Altura de la firma en la página del documento en valores de medida (píxeles, porcentajes o milímetros, vea [`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType). |
| [HorizontalAlignment](../../groupdocs.signature.options/imagesignoptions/horizontalalignment) { get; set; } | Alineación horizontal de la firma en la página del documento. |
| [ImageFilePath](../../groupdocs.signature.options/imagesignoptions/imagefilepath) { get; set; } | Obtiene o establece la ruta del archivo de imagen de la firma. Esta propiedad se usa solo si ImageStream no está especificado. |
| [ImageStream](../../groupdocs.signature.options/imagesignoptions/imagestream) { get; set; } | Obtiene o establece el flujo de imagen de la firma. Si se especifica esta propiedad, siempre se usa en lugar de ImageFilePath. |
| virtual [Left](../../groupdocs.signature.options/imagesignoptions/left) { get; set; } | Posición X izquierda de la Firma en la página del documento en valores de medida (píxeles, porcentajes o milímetros, ver [`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType). (funciona si la alineación horizontal no está especificada). |
| [Location](../../groupdocs.signature.options/digitalsignoptions/location) { get; set; } | Obtiene o establece la ubicación de la firma. |
| virtual [LocationMeasureType](../../groupdocs.signature.options/imagesignoptions/locationmeasuretype) { get; set; } | Tipo de medida (píxeles, porcentajes o milímetros) para las propiedades Left y Top. |
| virtual [Margin](../../groupdocs.signature.options/imagesignoptions/margin) { get; set; } | Obtiene o establece el espacio entre la firma y los bordes del documento. (funciona SOLO si se especifican la alineación horizontal o vertical). |
| virtual [MarginMeasureType](../../groupdocs.signature.options/imagesignoptions/marginmeasuretype) { get; set; } | Obtiene o establece el tipo de medida (píxeles, porcentajes o milímetros) para el margen. |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | Obtiene o establece el número de página del documento para la firma. El valor mínimo y predeterminado es 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | Opciones para especificar las páginas a firmar. |
| [Password](../../groupdocs.signature.options/digitalsignoptions/password) { get; set; } | Obtiene o establece la contraseña del certificado digital. |
| [Reason](../../groupdocs.signature.options/digitalsignoptions/reason) { get; set; } | Obtiene o establece la razón de la firma. |
| [Rectangle](../../groupdocs.signature.options/imagesignoptions/rectangle) { get; } | Rectángulo del área donde colocar la imagen en el documento. |
| [RotationAngle](../../groupdocs.signature.options/imagesignoptions/rotationangle) { get; set; } | Ángulo de rotación de la firma en la página del documento (en sentido horario). |
| [ShapePosition](../../groupdocs.signature.options/imagesignoptions/shapeposition) { get; set; } | Define dónde debe presentarse la forma en el diseño del documento. Disponible solo para documentos Word. |
| [Signature](../../groupdocs.signature.options/digitalsignoptions/signature) { get; set; } | Obtiene o establece las propiedades de la firma digital del documento. Para firmar documentos Pdf es posible establecer propiedades avanzadas utilizando una instancia de [`PdfDigitalSignature`](../../groupdocs.signature.domain/pdfdigitalsignature) |
| [SignatureType](../../groupdocs.signature.options/signoptions/signaturetype) { get; } | Obtenga el Tipo de Firma [`SignatureType`](../../groupdocs.signature.domain/signaturetype) |
| virtual [SizeMeasureType](../../groupdocs.signature.options/imagesignoptions/sizemeasuretype) { get; set; } | Tipo de medida (píxeles, porcentajes o milímetros) para las propiedades Width y Height. |
| [Stretch](../../groupdocs.signature.options/imagesignoptions/stretch) { get; set; } | Modo de estiramiento en la página del documento. |
| virtual [Top](../../groupdocs.signature.options/imagesignoptions/top) { get; set; } | Posición Y superior de la Firma en la página del documento en valores de medida (píxeles, porcentajes o milímetros, ver [`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType). (funciona si la alineación vertical no está especificada). |
| [Transparency](../../groupdocs.signature.options/imagesignoptions/transparency) { get; set; } | Obtiene o establece la transparencia de la firma (valor de 0.0 (opaco) a 1.0 (transparente)). El valor predeterminado es 0 (opaco). |
| [UseLtv](../../groupdocs.signature.options/digitalsignoptions/useltv) { get; set; } | Obtiene/establece la bandera de validación ltv (Validación a Largo Plazo). |
| [VerticalAlignment](../../groupdocs.signature.options/imagesignoptions/verticalalignment) { get; set; } | Alineación vertical de la firma en la página del documento. |
| [Visible](../../groupdocs.signature.options/digitalsignoptions/visible) { get; set; } | Obtiene o establece la visibilidad de la firma. |
| [Width](../../groupdocs.signature.options/imagesignoptions/width) { get; set; } | Ancho de la Firma en la página del documento en valores de medida (píxeles, porcentajes o milímetros [`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType). |
| [XAdESType](../../groupdocs.signature.options/digitalsignoptions/xadestype) { get; set; } | Tipo XAdES [`XAdESType`](./xadestype). El valor predeterminado es None (XAdES está desactivado). En este momento el tipo de firma XAdES solo es compatible con documentos de Spreadsheet. |
| [ZOrder](../../groupdocs.signature.options/signoptions/zorder) { get; set; } | Obtiene o establece la posición Z-order de la firma de texto. Determina el orden de visualización de firmas superpuestas. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Dispose](../../groupdocs.signature.options/imagesignoptions/dispose)() | Limpia los recursos internos |

### Observaciones

**Learn more**

* Basic usage of creating Digital electronic signature by GroupDocs.Signature: [How to eSign document with Digital signature](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Digital+signature)
* Advanced usage of settings of Digital electronic signature with GroupDocs.Signature: [Advanced usage to eSign document with Digital signature and additional settings](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Digital+signature+-+advanced)

### Ver también

* class [ImageSignOptions](../imagesignoptions)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.signature.dll -->
