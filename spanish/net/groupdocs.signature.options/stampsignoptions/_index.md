---
title: "StampSignOptions"
second_title: "Referencia de la API de GroupDocs.Signature para .NET"
description: "Representa las opciones de firma de sello."
type: docs
weight: 2000
url: /es/net/groupdocs.signature.options/stampsignoptions/
---
## StampSignOptions class

Representa las opciones de firma de sello.

```csharp
public class StampSignOptions : ImageSignOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [StampSignOptions](stampsignoptions#constructor)() | Inicializa una nueva instancia de la clase StampSignOptions con valores predeterminados. |
| [StampSignOptions](stampsignoptions#constructor_1)(int, int, int, int) | Inicializa una nueva instancia de la clase StampSignOptions con opciones de alineación. |

## Properties

| Nombre | Descripción |
| --- | --- |
| virtual [AllPages](../../groupdocs.signature.options/signoptions/allpages) { get; set; } | Coloca la firma en todas las páginas del documento. |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | Apariencia adicional de la firma. |
| [Background](../../groupdocs.signature.options/stampsignoptions/background) { get; set; } | Obtiene o establece el fondo del sello. |
| [BackgroundColorCropType](../../groupdocs.signature.options/stampsignoptions/backgroundcolorcroptype) { get; set; } | Obtiene o establece el tipo de recorte de color de fondo de la firma. |
| [BackgroundImageCropType](../../groupdocs.signature.options/stampsignoptions/backgroundimagecroptype) { get; set; } | Obtiene o establece el tipo de recorte de imagen de fondo de la firma. |
| [Border](../../groupdocs.signature.options/imagesignoptions/border) { get; set; } | Especificar la configuración del borde |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | Obtenga o establezca el Tipo de Documento de las Opciones de Firma [`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | Extensiones de firma. |
| [HashAlgorithm](../../groupdocs.signature.options/signoptions/hashalgorithm) { get; set; } | Obtiene o establece el algoritmo hash que se utilizará para operaciones criptográficas. Compatible exclusivamente con firmas digitales en archivos PDF. |
| [Height](../../groupdocs.signature.options/imagesignoptions/height) { get; set; } | Altura de la firma en la página del documento en valores de medida (píxeles, porcentajes o milímetros, vea [`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType). |
| [HorizontalAlignment](../../groupdocs.signature.options/imagesignoptions/horizontalalignment) { get; set; } | Alineación horizontal de la firma en la página del documento. |
| [ImageFilePath](../../groupdocs.signature.options/imagesignoptions/imagefilepath) { get; set; } | Obtiene o establece la ruta del archivo de imagen de la firma. Esta propiedad se usa solo si ImageStream no está especificado. |
| [ImageStream](../../groupdocs.signature.options/imagesignoptions/imagestream) { get; set; } | Obtiene o establece el flujo de imagen de la firma. Si se especifica esta propiedad, siempre se usa en lugar de ImageFilePath. |
| [InnerLines](../../groupdocs.signature.options/stampsignoptions/innerlines) { get; } | Lista de líneas internas renderizadas como conjunto de rectángulos. |
| virtual [Left](../../groupdocs.signature.options/imagesignoptions/left) { get; set; } | Posición X izquierda de la Firma en la página del documento en valores de medida (píxeles, porcentajes o milímetros, ver [`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType). (funciona si la alineación horizontal no está especificada). |
| virtual [LocationMeasureType](../../groupdocs.signature.options/imagesignoptions/locationmeasuretype) { get; set; } | Tipo de medida (píxeles, porcentajes o milímetros) para las propiedades Left y Top. |
| virtual [Margin](../../groupdocs.signature.options/imagesignoptions/margin) { get; set; } | Obtiene o establece el espacio entre la firma y los bordes del documento. (funciona SOLO si se especifican la alineación horizontal o vertical). |
| virtual [MarginMeasureType](../../groupdocs.signature.options/imagesignoptions/marginmeasuretype) { get; set; } | Obtiene o establece el tipo de medida (píxeles, porcentajes o milímetros) para el margen. |
| [OuterLines](../../groupdocs.signature.options/stampsignoptions/outerlines) { get; } | Lista de líneas externas renderizadas como círculos concéntricos. |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | Obtiene o establece el número de página del documento para la firma. El valor mínimo y predeterminado es 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | Opciones para especificar las páginas a firmar. |
| [Rectangle](../../groupdocs.signature.options/imagesignoptions/rectangle) { get; } | Rectángulo del área donde colocar la imagen en el documento. |
| [RotationAngle](../../groupdocs.signature.options/imagesignoptions/rotationangle) { get; set; } | Ángulo de rotación de la firma en la página del documento (en sentido horario). |
| [ShapePosition](../../groupdocs.signature.options/imagesignoptions/shapeposition) { get; set; } | Define dónde debe presentarse la forma en el diseño del documento. Disponible solo para documentos Word. |
| [SignatureType](../../groupdocs.signature.options/signoptions/signaturetype) { get; } | Obtenga el Tipo de Firma [`SignatureType`](../../groupdocs.signature.domain/signaturetype) |
| virtual [SizeMeasureType](../../groupdocs.signature.options/imagesignoptions/sizemeasuretype) { get; set; } | Tipo de medida (píxeles, porcentajes o milímetros) para las propiedades Width y Height. |
| [StampType](../../groupdocs.signature.options/stampsignoptions/stamptype) { get; set; } | Obtiene o establece el tipo de sello. El valor predeterminado es Redondo. |
| [Stretch](../../groupdocs.signature.options/imagesignoptions/stretch) { get; set; } | Modo de estiramiento en la página del documento. |
| virtual [Top](../../groupdocs.signature.options/imagesignoptions/top) { get; set; } | Posición Y superior de la Firma en la página del documento en valores de medida (píxeles, porcentajes o milímetros, ver [`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType). (funciona si la alineación vertical no está especificada). |
| [Transparency](../../groupdocs.signature.options/imagesignoptions/transparency) { get; set; } | Obtiene o establece la transparencia de la firma (valor de 0.0 (opaco) a 1.0 (transparente)). El valor predeterminado es 0 (opaco). |
| [VerticalAlignment](../../groupdocs.signature.options/imagesignoptions/verticalalignment) { get; set; } | Alineación vertical de la firma en la página del documento. |
| [Width](../../groupdocs.signature.options/imagesignoptions/width) { get; set; } | Ancho de la Firma en la página del documento en valores de medida (píxeles, porcentajes o milímetros [`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType). |
| [ZOrder](../../groupdocs.signature.options/signoptions/zorder) { get; set; } | Obtiene o establece la posición Z-order de la firma de texto. Determina el orden de visualización de firmas superpuestas. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Dispose](../../groupdocs.signature.options/imagesignoptions/dispose)() | Limpia los recursos internos |

### Observaciones

**Learn more**

* Basic usage of creating Stamp electronic signature by GroupDocs.Signature: [How to eSign document with Stamp signature](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Stamp+signature)
* Advanced usage of settings of Stamp electronic signature with GroupDocs.Signature: [Advanced usage to eSign document with Stamp signature and additional settings](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Stamp+signature+-+advanced)

### Ver también

* class [ImageSignOptions](../imagesignoptions)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.signature.dll -->
