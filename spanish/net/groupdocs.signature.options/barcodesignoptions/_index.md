---
title: BarcodeSignOptions
second_title: Referencia de API de GroupDocs.Signature para .NET
description: Representa las opciones de firma de código de barras.
type: docs
weight: 1190
url: /es/net/groupdocs.signature.options/barcodesignoptions/
---
## BarcodeSignOptions class

Representa las opciones de firma de código de barras.

```csharp
public class BarcodeSignOptions : TextSignOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [BarcodeSignOptions](barcodesignoptions#constructor)() | Inicializa una nueva instancia de la clase BarcodeSignOptions con valores predeterminados. |
| [BarcodeSignOptions](barcodesignoptions#constructor_1)(string) | Inicializa una nueva instancia de la clase BarcodeSignOptions con texto. |
| [BarcodeSignOptions](barcodesignoptions#constructor_2)(string, BarcodeType) | Inicializa una nueva instancia de la clase BarcodeSignOptions con texto. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| virtual [AllPages](../../groupdocs.signature.options/signoptions/allpages) { get; set; } | Poner firma en todas las páginas del documento. |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | Aspecto de firma adicional. |
| [Background](../../groupdocs.signature.options/textsignoptions/background) { get; set; } | Obtiene o establece la configuración de fondo de la firma. |
| [Border](../../groupdocs.signature.options/textsignoptions/border) { get; set; } | Especificar configuración de borde |
| [CodeTextAlignment](../../groupdocs.signature.options/barcodesignoptions/codetextalignment) { get; set; } | Obtiene o establece la alineación del texto en la imagen de código de barras resultante. El valor predeterminado es Ninguno. |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | Obtener o establecer el tipo de documento de las opciones de firma[`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [EncodeType](../../groupdocs.signature.options/barcodesignoptions/encodetype) { get; set; } | Obtiene o establece el tipo de código de barras. |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | Extensiones de firma. |
| [Font](../../groupdocs.signature.options/textsignoptions/font) { get; set; } | Obtiene o establece la fuente de la firma. |
| override [ForeColor](../../groupdocs.signature.options/barcodesignoptions/forecolor) { get; set; } | Obtiene o establece el color de primer plano de las barras de código de barras El uso de esta propiedad podría causar problemas con la verificación. Úselo con cuidado. |
| [FormTextFieldTitle](../../groupdocs.signature.options/textsignoptions/formtextfieldtitle) { get; set; } | Obtiene o establece el título del campo de formulario de texto para colocar la firma de texto en él. Esta propiedad solo se puede usar con SignatureImplementation = TextToFormField. |
| [FormTextFieldType](../../groupdocs.signature.options/textsignoptions/formtextfieldtype) { get; set; } | Obtiene o establece el tipo de campo de formulario para colocar la firma de texto en él. Esta propiedad solo se puede usar con SignatureImplementation = TextToFormField. El valor predeterminado es AllTextTypes. |
| [Height](../../groupdocs.signature.options/textsignoptions/height) { get; set; } | Altura de la firma en la página del documento en valores de medida (píxeles, porcentajes o milímetros, consulte[`MeasureType`](../../groupdocs.signature.domain/measuretype) propiedad SizeMeasureType). |
| [HorizontalAlignment](../../groupdocs.signature.options/textsignoptions/horizontalalignment) { get; set; } | Alineación horizontal de la firma en la página del documento. |
| [InnerMargins](../../groupdocs.signature.options/barcodesignoptions/innermargins) { get; set; } | Obtiene o establece el espacio entre los elementos del código de barras y los bordes de la imagen de resultado. |
| [Left](../../groupdocs.signature.options/textsignoptions/left) { get; set; } | Posición X izquierda de la firma en la página del documento en valores de medida (píxeles, porcentajes o milímetros, consulte[`MeasureType`](../../groupdocs.signature.domain/measuretype) Propiedad LocationMeasureType). (funciona si no se especifica la alineación horizontal). |
| virtual [LocationMeasureType](../../groupdocs.signature.options/textsignoptions/locationmeasuretype) { get; set; } | Tipo de medida (píxeles, porcentajes o milímetros) para las propiedades Izquierda y Superior. |
| virtual [Margin](../../groupdocs.signature.options/textsignoptions/margin) { get; set; } | Obtiene o establece el espacio entre los bordes del Signo y del Documento. (funciona SOLO si se especifica la alineación horizontal o vertical). |
| virtual [MarginMeasureType](../../groupdocs.signature.options/textsignoptions/marginmeasuretype) { get; set; } | Obtiene o establece el tipo de medida (píxeles, porcentajes o milímetros) para Margin. |
| [Native](../../groupdocs.signature.options/textsignoptions/native) { get; set; } | Obtiene o establece el atributo nativo. Si se establece, se pueden usar firmas específicas del documento. La marca de agua de texto nativo para documentos de procesamiento de textos es diferente a la normal, por ejemplo. |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | Obtiene o establece el número de página del documento para firmar. El valor mínimo y predeterminado es 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | Opciones para especificar páginas a firmar. |
| [ReturnContent](../../groupdocs.signature.options/barcodesignoptions/returncontent) { get; set; } | Obtiene o establece el indicador para obtener el contenido de la imagen del código de barras de una firma que se colocó en la página del documento. Si este indicador se establece como verdadero, el contenido de la imagen de la firma del código de barras mantendrá los datos de imagen sin procesar en el formato requerido[`ReturnContentType`](./returncontenttype) . Por defecto esta opción está deshabilitada. |
| [ReturnContentType](../../groupdocs.signature.options/barcodesignoptions/returncontenttype) { get; set; } | Especifica el tipo de archivo del contenido de imagen devuelto de la firma de código de barras cuando la propiedad ReturnContent está habilitada. De forma predeterminada, se establece en Nulo. Eso significa devolver el contenido de la imagen del código de barras en formato original. Este formato de imagen se especifica en[`Format`](../../groupdocs.signature.domain/barcodesignature/format) Los posibles valores admitidos son: FileType.JPEG, FileType.PNG, FileType.BMP. Si el formato proporcionado no es compatible, se devolverá el contenido de la imagen del código de barras en formato .png. |
| [RotationAngle](../../groupdocs.signature.options/textsignoptions/rotationangle) { get; set; } | Ángulo de rotación de la firma en la página del documento (sentido horario). |
| [ShapeType](../../groupdocs.signature.options/textsignoptions/shapetype) { get; set; } | Obtiene o establece el tipo de forma para poner texto. Esta propiedad solo se puede usar con SignatureImplementation = TextStamp. El valor por defecto es Rectangle. |
| [SignatureID](../../groupdocs.signature.options/textsignoptions/signatureid) { get; set; } | Obtiene o establece el ID exclusivo de la firma. Se puede utilizar en las opciones de verificación de firma. La propiedad solo se admite para documentos PDF. |
| [SignatureImplementation](../../groupdocs.signature.options/textsignoptions/signatureimplementation) { get; set; } | Obtiene o establece el tipo de implementación de la firma de texto. |
| [SignatureType](../../groupdocs.signature.options/signoptions/signaturetype) { get; } | Obtener el tipo de firma[`SignatureType`](../../groupdocs.signature.domain/signaturetype) |
| virtual [SizeMeasureType](../../groupdocs.signature.options/textsignoptions/sizemeasuretype) { get; set; } | Tipo de medida (píxeles, porcentajes o milímetros) para las propiedades Ancho y Alto. |
| [Stretch](../../groupdocs.signature.options/textsignoptions/stretch) { get; set; } | Modo de extensión en la página del documento. |
| [Text](../../groupdocs.signature.options/textsignoptions/text) { get; set; } | Obtiene o establece el texto de la firma. |
| [TextHorizontalAlignment](../../groupdocs.signature.options/textsignoptions/texthorizontalalignment) { get; set; } | Alineación horizontal del texto dentro de una firma. Esta función solo se admite para implementaciones de firmas de imágenes y anotaciones (consulte[`TextSignatureImplementation`](../../groupdocs.signature.domain/textsignatureimplementation) Propiedad SignatureImplementation). |
| [TextVerticalAlignment](../../groupdocs.signature.options/textsignoptions/textverticalalignment) { get; set; } | Alineación vertical del texto dentro de una firma. Esta función solo se admite para la implementación de firma de imagen (consulte[`TextSignatureImplementation`](../../groupdocs.signature.domain/textsignatureimplementation) propiedad SignatureImplementation). |
| [Top](../../groupdocs.signature.options/textsignoptions/top) { get; set; } | Posición Y superior de la firma en la página del documento en valores de medida (píxeles, porcentajes o milímetros, consulte[`MeasureType`](../../groupdocs.signature.domain/measuretype)Propiedad LocationMeasureType). (funciona si no se especifica la alineación vertical). |
| [Transparency](../../groupdocs.signature.options/textsignoptions/transparency) { get; set; } | Obtiene o establece la transparencia de la firma (valor de 0,0 (opaco) a 1,0 (transparente)). El valor predeterminado es 0 (opaco). |
| [VerticalAlignment](../../groupdocs.signature.options/textsignoptions/verticalalignment) { get; set; } | Alineación vertical de la firma en la página del documento. |
| [Width](../../groupdocs.signature.options/textsignoptions/width) { get; set; } | Ancho de la firma en la página del documento en valores de medida (píxeles, porcentajes o milímetros, consulte[`MeasureType`](../../groupdocs.signature.domain/measuretype) propiedad SizeMeasureType). |
| [ZOrder](../../groupdocs.signature.options/signoptions/zorder) { get; set; } | Obtiene o establece la posición de orden Z de la firma de texto. Determina el orden de visualización de las firmas superpuestas. |

### Observaciones

**Aprende más**

* Uso básico de la creación de firma electrónica de código de barras por GroupDocs. Firma: [Cómo firmar un documento con firma de código de barras](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Barcode+signature)
* Uso avanzado de configuración de firma electrónica Barcode con GroupDocs.Firma: [Uso avanzado de documentos de firma electrónica con firma de código de barras y configuraciones adicionales](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Barcode+signature+and+additional+settings)

### Ver también

* class [TextSignOptions](../textsignoptions)
* espacio de nombres [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* asamblea [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
