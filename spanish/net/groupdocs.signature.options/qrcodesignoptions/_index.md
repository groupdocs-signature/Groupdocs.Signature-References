---
title: "QrCodeSignOptions"
second_title: "Referencia de la API de GroupDocs.Signature para .NET"
description: "Representa las opciones de firma QRCode."
type: docs
weight: 1920
url: /es/net/groupdocs.signature.options/qrcodesignoptions/
---
## QrCodeSignOptions class

Representa las opciones de firma de código QR.

```csharp
public class QrCodeSignOptions : TextSignOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [QrCodeSignOptions](qrcodesignoptions#constructor)() | Inicializa una nueva instancia de la clase QRCodeSignOptions con valores predeterminados. |
| [QrCodeSignOptions](qrcodesignoptions#constructor_1)(string) | Inicializa una nueva instancia de la clase QRCodeSignOptions con texto. |
| [QrCodeSignOptions](qrcodesignoptions#constructor_2)(string, QrCodeType) | Inicializa una nueva instancia de la clase BarcodeSignOptions con texto. |

## Properties

| Nombre | Descripción |
| --- | --- |
| virtual [AllPages](../../groupdocs.signature.options/signoptions/allpages) { get; set; } | Coloca la firma en todas las páginas del documento. |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | Apariencia adicional de la firma. |
| [Background](../../groupdocs.signature.options/textsignoptions/background) { get; set; } | Obtiene o establece la configuración del fondo de la firma. |
| [Border](../../groupdocs.signature.options/textsignoptions/border) { get; set; } | Especificar la configuración del borde |
| [CodeTextAlignment](../../groupdocs.signature.options/qrcodesignoptions/codetextalignment) { get; set; } | Obtiene o establece la alineación del texto en la imagen QR-code resultante. El valor predeterminado es None. |
| [Data](../../groupdocs.signature.options/qrcodesignoptions/data) { get; set; } | Obtiene o establece un objeto personalizado para serializar al contenido QR-Code. |
| [DataEncryption](../../groupdocs.signature.options/qrcodesignoptions/dataencryption) { get; set; } | Obtiene o establece la implementación de la interfaz [`IDataEncryption`](../../groupdocs.signature.domain.extensions/idataencryption) para codificar y decodificar el texto o las propiedades de datos de la firma QR-Code. |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | Obtenga o establezca el Tipo de Documento de las Opciones de Firma [`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [EncodeType](../../groupdocs.signature.options/qrcodesignoptions/encodetype) { get; set; } | Obtiene o establece el tipo QR-Code. |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | Extensiones de firma. |
| [Font](../../groupdocs.signature.options/textsignoptions/font) { get; set; } | Obtiene o establece la fuente de la firma. |
| override [ForeColor](../../groupdocs.signature.options/qrcodesignoptions/forecolor) { get; set; } | Obtiene o establece el color de primer plano de las barras QR-Code. El uso de esta propiedad podría causar problemas con la verificación. Úsela con cuidado. |
| [FormTextFieldTitle](../../groupdocs.signature.options/textsignoptions/formtextfieldtitle) { get; set; } | Obtiene o establece el título del campo de formulario de texto para colocar la firma de texto en él. Esta propiedad solo se puede usar con SignatureImplementation = TextToFormField. |
| [FormTextFieldType](../../groupdocs.signature.options/textsignoptions/formtextfieldtype) { get; set; } | Obtiene o establece el tipo de campo de formulario para colocar la firma de texto en él. Esta propiedad solo se puede usar con SignatureImplementation = TextToFormField. El valor predeterminado es AllTextTypes. |
| [HashAlgorithm](../../groupdocs.signature.options/signoptions/hashalgorithm) { get; set; } | Obtiene o establece el algoritmo hash que se utilizará para operaciones criptográficas. Compatible exclusivamente con firmas digitales en archivos PDF. |
| [Height](../../groupdocs.signature.options/textsignoptions/height) { get; set; } | Altura de la firma en la página del documento en valores de medida (píxeles, porcentajes o milímetros, vea [`MeasureType`](../../groupdocs.signature.domain/measuretype) propiedad SizeMeasureType). |
| [HorizontalAlignment](../../groupdocs.signature.options/textsignoptions/horizontalalignment) { get; set; } | Alineación horizontal de la firma en la página del documento. |
| [InnerMargins](../../groupdocs.signature.options/qrcodesignoptions/innermargins) { get; set; } | Obtiene o establece el espacio entre los elementos QR-Code y los bordes de la imagen resultante. |
| [Left](../../groupdocs.signature.options/textsignoptions/left) { get; set; } | Posición X izquierda de la firma en la página del documento en valores de medida (píxeles, porcentajes o milímetros, ver [`MeasureType`](../../groupdocs.signature.domain/measuretype) propiedad LocationMeasureType). (funciona si no se especifica la alineación horizontal). |
| virtual [LocationMeasureType](../../groupdocs.signature.options/textsignoptions/locationmeasuretype) { get; set; } | Tipo de medida (píxeles, porcentajes o milímetros) para las propiedades Left y Top. |
| [LogoFilePath](../../groupdocs.signature.options/qrcodesignoptions/logofilepath) { get; set; } | Obtiene o establece el nombre de archivo de la imagen del logotipo QR-code. Esta propiedad se usa solo si LogoStream no está especificado. El uso de esta propiedad podría causar problemas con la verificación. Úsela con cuidado. |
| [LogoStream](../../groupdocs.signature.options/qrcodesignoptions/logostream) { get; set; } | Obtiene o establece el flujo de imagen del logotipo QR-code. Si se especifica esta propiedad, siempre se usa en lugar de LogoFilePath. El uso de esta propiedad podría causar problemas con la verificación. Úsela con cuidado. |
| virtual [Margin](../../groupdocs.signature.options/textsignoptions/margin) { get; set; } | Obtiene o establece el espacio entre la firma y los bordes del documento. (funciona SOLO si se especifican la alineación horizontal o vertical). |
| virtual [MarginMeasureType](../../groupdocs.signature.options/textsignoptions/marginmeasuretype) { get; set; } | Obtiene o establece el tipo de medida (píxeles, porcentajes o milímetros) para el margen. |
| [Native](../../groupdocs.signature.options/textsignoptions/native) { get; set; } | Obtiene o establece el atributo nativo. Si se establece, se pueden usar firmas específicas del documento. La marca de agua de texto nativa para documentos WordProcessing es diferente a la regular, por ejemplo. |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | Obtiene o establece el número de página del documento para la firma. El valor mínimo y predeterminado es 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | Opciones para especificar las páginas a firmar. |
| [ReturnContent](../../groupdocs.signature.options/qrcodesignoptions/returncontent) { get; set; } | Obtiene o establece la bandera para obtener el contenido de imagen QR-Code de una firma que se colocó en la página del documento. Si esta bandera se establece en true, el contenido de imagen de la firma QR-Code mantendrá los datos de imagen sin procesar en el formato requerido [`ReturnContentType`](./returncontenttype). Por defecto, esta opción está deshabilitada. |
| [ReturnContentType](../../groupdocs.signature.options/qrcodesignoptions/returncontenttype) { get; set; } | Especifica el tipo de archivo del contenido de imagen devuelto de la firma QR-Code cuando la propiedad ReturnContent está habilitada. Por defecto se establece en Null. Eso significa devolver el contenido de imagen QR-Code en su formato original. Este formato de imagen se especifica en [`Format`](../../groupdocs.signature.domain/qrcodesignature/format). Los valores compatibles posibles son: FileType.JPEG, FileType.PNG, FileType.BMP. Si el formato proporcionado no es compatible, se devolverá el contenido de imagen QR-Code en formato .png. |
| [RotationAngle](../../groupdocs.signature.options/textsignoptions/rotationangle) { get; set; } | Ángulo de rotación de la firma en la página del documento (en sentido horario). |
| [ShapePosition](../../groupdocs.signature.options/textsignoptions/shapeposition) { get; set; } | Define dónde debe presentarse la forma en el diseño del documento. Disponible solo para documentos Word. |
| [ShapeType](../../groupdocs.signature.options/textsignoptions/shapetype) { get; set; } | Obtiene o establece el tipo de forma para colocar texto. Esta propiedad solo se puede usar con SignatureImplementation = TextStamp. El valor por defecto es Rectangle. |
| [SignatureID](../../groupdocs.signature.options/textsignoptions/signatureid) { get; set; } | Obtiene o establece el ID único de la firma. Puede usarse en opciones de verificación de firma. La propiedad es compatible solo con documentos Pdf. |
| [SignatureImplementation](../../groupdocs.signature.options/textsignoptions/signatureimplementation) { get; set; } | Obtiene o establece el tipo de implementación de firma de texto. |
| [SignatureType](../../groupdocs.signature.options/signoptions/signaturetype) { get; } | Obtenga el Tipo de Firma [`SignatureType`](../../groupdocs.signature.domain/signaturetype) |
| virtual [SizeMeasureType](../../groupdocs.signature.options/textsignoptions/sizemeasuretype) { get; set; } | Tipo de medida (píxeles, porcentajes o milímetros) para las propiedades Width y Height. |
| [Stretch](../../groupdocs.signature.options/textsignoptions/stretch) { get; set; } | Modo de estiramiento en la página del documento. |
| [Text](../../groupdocs.signature.options/textsignoptions/text) { get; set; } | Obtiene o establece el texto de la firma. |
| [TextHorizontalAlignment](../../groupdocs.signature.options/textsignoptions/texthorizontalalignment) { get; set; } | Alineación horizontal del texto dentro de una firma. Esta característica solo es compatible con implementaciones de firma de Imagen y Anotación (ver [`TextSignatureImplementation`](../../groupdocs.signature.domain/textsignatureimplementation) propiedad SignatureImplementation). |
| [TextVerticalAlignment](../../groupdocs.signature.options/textsignoptions/textverticalalignment) { get; set; } | Alineación vertical del texto dentro de una firma. Esta característica solo es compatible con la implementación de firma de Imagen (ver [`TextSignatureImplementation`](../../groupdocs.signature.domain/textsignatureimplementation) propiedad SignatureImplementation). |
| [Top](../../groupdocs.signature.options/textsignoptions/top) { get; set; } | Posición Y superior de la firma en la página del documento en valores de medida (píxeles, porcentajes o milímetros, ver [`MeasureType`](../../groupdocs.signature.domain/measuretype) propiedad LocationMeasureType). (funciona si no se especifica la alineación vertical). |
| [Transparency](../../groupdocs.signature.options/textsignoptions/transparency) { get; set; } | Obtiene o establece la transparencia de la firma (valor de 0.0 (opaco) a 1.0 (transparente)). El valor predeterminado es 0 (opaco). |
| [VerticalAlignment](../../groupdocs.signature.options/textsignoptions/verticalalignment) { get; set; } | Alineación vertical de la firma en la página del documento. |
| [Width](../../groupdocs.signature.options/textsignoptions/width) { get; set; } | Ancho de la firma en la página del documento en valores de medida (píxeles, porcentajes o milímetros, ver [`MeasureType`](../../groupdocs.signature.domain/measuretype) propiedad SizeMeasureType). |
| [ZOrder](../../groupdocs.signature.options/signoptions/zorder) { get; set; } | Obtiene o establece la posición Z-order de la firma de texto. Determina el orden de visualización de firmas superpuestas. |

### Observaciones

**Learn more**

* Basic usage of creating QR-Code electronic signature by GroupDocs.Signature: [How to eSign document with QR-Code signature](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+QR-code+signature)
* Advanced usage of settings of QR-Code electronic signature with GroupDocs.Signature: [Advanced usage to eSign document with QR-Code signature and additional settings](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+QR-code+signature+-+advanced)

### Ver también

* class [TextSignOptions](../textsignoptions)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.signature.dll -->
