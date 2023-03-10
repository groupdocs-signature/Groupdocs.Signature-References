---
title: StampSignOptions
second_title: Referencia de API de GroupDocs.Signature para .NET
description: Representa las opciones de firma del sello.
type: docs
weight: 1710
url: /es/net/groupdocs.signature.options/stampsignoptions/
---
## StampSignOptions class

Representa las opciones de firma del sello.

```csharp
public class StampSignOptions : ImageSignOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [StampSignOptions](stampsignoptions#constructor)() | Inicializa una nueva instancia de la clase StampSignOptions con valores predeterminados. |
| [StampSignOptions](stampsignoptions#constructor_1)(int, int, int, int) | Inicializa una nueva instancia de la clase StampSignOptions con opciones de alineación. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| override [AllPages](../../groupdocs.signature.options/imagesignoptions/allpages) { get; set; } | Poner firma en todas las páginas del documento. Esta propiedad solo se puede utilizar para formatos de imagen de varios fotogramas (Tiff). |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | Aspecto de firma adicional. |
| [Background](../../groupdocs.signature.options/stampsignoptions/background) { get; set; } | Obtiene o establece el fondo del Sello. |
| [BackgroundColorCropType](../../groupdocs.signature.options/stampsignoptions/backgroundcolorcroptype) { get; set; } | Obtiene o establece el tipo de recorte de color de fondo de la firma. |
| [BackgroundImageCropType](../../groupdocs.signature.options/stampsignoptions/backgroundimagecroptype) { get; set; } | Obtiene o establece el tipo de recorte de la imagen de fondo de la firma. |
| [Border](../../groupdocs.signature.options/imagesignoptions/border) { get; set; } | Especificar configuración de borde |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | Obtener o establecer el tipo de documento de las opciones de firma[`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | Extensiones de firma. |
| [Height](../../groupdocs.signature.options/imagesignoptions/height) { get; set; } | Altura de la firma en la página del documento en valores de medida (píxeles, porcentajes o milímetros, consulte[`MeasureType`](../../groupdocs.signature.domain/measuretype) TamañoMedidaTipo). |
| [HorizontalAlignment](../../groupdocs.signature.options/imagesignoptions/horizontalalignment) { get; set; } | Alineación horizontal de la firma en la página del documento. |
| [ImageFilePath](../../groupdocs.signature.options/imagesignoptions/imagefilepath) { get; set; } | Obtiene o establece la ruta del archivo de imagen de la firma. Esta propiedad se usa solo si no se especifica ImageStream. |
| [ImageStream](../../groupdocs.signature.options/imagesignoptions/imagestream) { get; set; } | Obtiene o establece el flujo de imagen de firma. Si se especifica esta propiedad, siempre se usa en su lugar ImageFilePath. |
| [InnerLines](../../groupdocs.signature.options/stampsignoptions/innerlines) { get; } | Lista de líneas internas representadas como conjunto de rectángulos. |
| virtual [Left](../../groupdocs.signature.options/imagesignoptions/left) { get; set; } | Posición X izquierda de la firma en la página del documento en valores de medida (píxeles, porcentajes o milímetros, consulte[`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType). (funciona si no se especifica la alineación horizontal). |
| virtual [LocationMeasureType](../../groupdocs.signature.options/imagesignoptions/locationmeasuretype) { get; set; } | Tipo de medida (píxeles, porcentajes o milímetros) para las propiedades Izquierda y Superior. |
| virtual [Margin](../../groupdocs.signature.options/imagesignoptions/margin) { get; set; } | Obtiene o establece el espacio entre los bordes del Signo y del Documento. (funciona SOLO si se especifica la alineación horizontal o vertical). |
| virtual [MarginMeasureType](../../groupdocs.signature.options/imagesignoptions/marginmeasuretype) { get; set; } | Obtiene o establece el tipo de medida (píxeles, porcentajes o milímetros) para Margin. |
| [OuterLines](../../groupdocs.signature.options/stampsignoptions/outerlines) { get; } | Lista de líneas exteriores representadas como círculos concéntricos. |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | Obtiene o establece el número de página del documento para firmar. El valor mínimo y predeterminado es 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | Opciones para especificar páginas a firmar. |
| [Rectangle](../../groupdocs.signature.options/imagesignoptions/rectangle) { get; } | Rectángulo de área para colocar la imagen en el documento. |
| [RotationAngle](../../groupdocs.signature.options/imagesignoptions/rotationangle) { get; set; } | Ángulo de rotación de la firma en la página del documento (sentido horario). |
| [SignatureType](../../groupdocs.signature.options/signoptions/signaturetype) { get; } | Obtener el tipo de firma[`SignatureType`](../../groupdocs.signature.domain/signaturetype) |
| virtual [SizeMeasureType](../../groupdocs.signature.options/imagesignoptions/sizemeasuretype) { get; set; } | Tipo de medida (píxeles, porcentajes o milímetros) para las propiedades Ancho y Alto. |
| [StampType](../../groupdocs.signature.options/stampsignoptions/stamptype) { get; set; } | Obtiene o establece el tipo de sello. El valor predeterminado es Round. |
| [Stretch](../../groupdocs.signature.options/imagesignoptions/stretch) { get; set; } | Modo de extensión en la página del documento. |
| virtual [Top](../../groupdocs.signature.options/imagesignoptions/top) { get; set; } | Posición Y superior de la firma en la página del documento en valores de medida (píxeles, porcentajes o milímetros, consulte[`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType). (funciona si no se especifica la alineación vertical). |
| [Transparency](../../groupdocs.signature.options/imagesignoptions/transparency) { get; set; } | Obtiene o establece la transparencia de la firma (valor de 0,0 (opaco) a 1,0 (transparente)). El valor predeterminado es 0 (opaco). |
| [VerticalAlignment](../../groupdocs.signature.options/imagesignoptions/verticalalignment) { get; set; } | Alineación vertical de la firma en la página del documento. |
| [Width](../../groupdocs.signature.options/imagesignoptions/width) { get; set; } | Ancho de la firma en la página del documento en valores de medida (píxeles, porcentajes o milímetros)[`MeasureType`](../../groupdocs.signature.domain/measuretype) TamañoMedidaTipo). |
| [ZOrder](../../groupdocs.signature.options/signoptions/zorder) { get; set; } | Obtiene o establece la posición de orden Z de la firma de texto. Determina el orden de visualización de las firmas superpuestas. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Dispose](../../groupdocs.signature.options/imagesignoptions/dispose)() | Borra los recursos internos |

### Observaciones

**Aprende más**

* Uso básico de la creación de una firma electrónica de sello por parte de GroupDocs. Firma: [Cómo firmar un documento electrónico con la firma del sello](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Stamp+signature)
* Uso avanzado de configuración de Sello de firma electrónica con GroupDocs. Firma: [Uso avanzado de documentos de firma electrónica con firma de sello y configuraciones adicionales](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Stamp+signature+-+advanced)

### Ver también

* class [ImageSignOptions](../imagesignoptions)
* espacio de nombres [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* asamblea [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
