---
title: TextSignOptions
second_title: Referencia de API de GroupDocs.Signature para .NET
description: Representa las opciones de firma de texto.
type: docs
weight: 1730
url: /es/net/groupdocs.signature.options/textsignoptions/
---
## TextSignOptions class

Representa las opciones de firma de texto.

```csharp
public class TextSignOptions : SignOptions, IAlignment, IRectangle, IRotation, ITransparency
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [TextSignOptions](textsignoptions#constructor)() | Inicializa una nueva instancia de la clase TextSignOptions con valores predeterminados. |
| [TextSignOptions](textsignoptions#constructor_1)(string) | Inicializa una nueva instancia de la clase TextSignOptions con text. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| virtual [AllPages](../../groupdocs.signature.options/signoptions/allpages) { get; set; } | Poner firma en todas las páginas del documento. |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | Aspecto de firma adicional. |
| [Background](../../groupdocs.signature.options/textsignoptions/background) { get; set; } | Obtiene o establece la configuración de fondo de la firma. |
| [Border](../../groupdocs.signature.options/textsignoptions/border) { get; set; } | Especificar configuración de borde |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | Obtener o establecer el tipo de documento de las opciones de firma[`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | Extensiones de firma. |
| [Font](../../groupdocs.signature.options/textsignoptions/font) { get; set; } | Obtiene o establece la fuente de la firma. |
| virtual [ForeColor](../../groupdocs.signature.options/textsignoptions/forecolor) { get; set; } | Obtiene o establece el color de frente de la firma. |
| [FormTextFieldTitle](../../groupdocs.signature.options/textsignoptions/formtextfieldtitle) { get; set; } | Obtiene o establece el título del campo de formulario de texto para colocar la firma de texto en él. Esta propiedad solo se puede usar con SignatureImplementation = TextToFormField. |
| [FormTextFieldType](../../groupdocs.signature.options/textsignoptions/formtextfieldtype) { get; set; } | Obtiene o establece el tipo de campo de formulario para colocar la firma de texto en él. Esta propiedad solo se puede usar con SignatureImplementation = TextToFormField. El valor predeterminado es AllTextTypes. |
| [Height](../../groupdocs.signature.options/textsignoptions/height) { get; set; } | Altura de la firma en la página del documento en valores de medida (píxeles, porcentajes o milímetros, consulte[`MeasureType`](../../groupdocs.signature.domain/measuretype) propiedad SizeMeasureType). |
| [HorizontalAlignment](../../groupdocs.signature.options/textsignoptions/horizontalalignment) { get; set; } | Alineación horizontal de la firma en la página del documento. |
| [Left](../../groupdocs.signature.options/textsignoptions/left) { get; set; } | Posición X izquierda de la firma en la página del documento en valores de medida (píxeles, porcentajes o milímetros, consulte[`MeasureType`](../../groupdocs.signature.domain/measuretype) Propiedad LocationMeasureType). (funciona si no se especifica la alineación horizontal). |
| virtual [LocationMeasureType](../../groupdocs.signature.options/textsignoptions/locationmeasuretype) { get; set; } | Tipo de medida (píxeles, porcentajes o milímetros) para las propiedades Izquierda y Superior. |
| virtual [Margin](../../groupdocs.signature.options/textsignoptions/margin) { get; set; } | Obtiene o establece el espacio entre los bordes del Signo y del Documento. (funciona SOLO si se especifica la alineación horizontal o vertical). |
| virtual [MarginMeasureType](../../groupdocs.signature.options/textsignoptions/marginmeasuretype) { get; set; } | Obtiene o establece el tipo de medida (píxeles, porcentajes o milímetros) para Margin. |
| [Native](../../groupdocs.signature.options/textsignoptions/native) { get; set; } | Obtiene o establece el atributo nativo. Si se establece, se pueden usar firmas específicas del documento. La marca de agua de texto nativo para documentos de procesamiento de textos es diferente a la normal, por ejemplo. |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | Obtiene o establece el número de página del documento para firmar. El valor mínimo y predeterminado es 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | Opciones para especificar páginas a firmar. |
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

* Uso básico de creación de firma electrónica de texto por GroupDocs. Firma: [Cómo firmar electrónicamente un documento con firma de texto](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Text+signature)
* Uso avanzado de configuración de Firma electrónica Texto con GroupDocs. Firma: [Uso avanzado para firmar documentos electrónicos con firma de texto y configuraciones adicionales](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Text+signature+-+advanced)

### Ver también

* class [SignOptions](../signoptions)
* interface [IAlignment](../../groupdocs.signature.domain/ialignment)
* interface [IRectangle](../../groupdocs.signature.domain/irectangle)
* interface [IRotation](../../groupdocs.signature.domain/irotation)
* interface [ITransparency](../../groupdocs.signature.domain/itransparency)
* espacio de nombres [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* asamblea [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
