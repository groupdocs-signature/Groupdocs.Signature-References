---
title: "ImageDigitalVerifyOptions"
second_title: "Referencia de la API de GroupDocs.Signature para .NET"
description: "Mantiene opciones para verificar firmas digitales en imágenes rasterizadas."
type: docs
weight: 1640
url: /es/net/groupdocs.signature.options/imagedigitalverifyoptions/
---
## ImageDigitalVerifyOptions class

Mantiene opciones para verificar firmas digitales en imágenes rasterizadas.

```csharp
public class ImageDigitalVerifyOptions : VerifyOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [ImageDigitalVerifyOptions](imagedigitalverifyoptions)() | Inicializa una nueva instancia de la clase ImageDigitalVerifyOptions para verificar firmas digitales (esteganografía) en imágenes raster. |

## Properties

| Nombre | Descripción |
| --- | --- |
| [AllPages](../../groupdocs.signature.options/verifyoptions/allpages) { get; set; } | Indicador para verificar cada página del documento. Por defecto el valor es true. |
| [DetectedProbability](../../groupdocs.signature.options/imagedigitalverifyoptions/detectedprobability) { get; } | Almacena la probabilidad devuelta por AnalyzePercentageDigitalSignature (0-100). |
| [DetectionThresholdPercent](../../groupdocs.signature.options/imagedigitalverifyoptions/detectionthresholdpercent) { get; set; } | Porcentaje de umbral de detección para extracción parcial (0-100). El valor predeterminado es 75. |
| [Extensions](../../groupdocs.signature.options/verifyoptions/extensions) { get; set; } | Extensiones adicionales para la verificación de opciones de firma alternativas. |
| [IsValid](../../groupdocs.signature.options/verifyoptions/isvalid) { get; } | Indicador de propiedad válida. |
| virtual [PageNumber](../../groupdocs.signature.options/verifyoptions/pagenumber) { get; set; } | Número de página del documento a verificar. Si la propiedad no está establecida, se verificarán todas las páginas del documento para la primera aparición. El valor mínimo es 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/verifyoptions/pagessetup) { get; set; } | Opciones de página para especificar las páginas a verificar. |
| [Password](../../groupdocs.signature.options/imagedigitalverifyoptions/password) { get; set; } | Contraseña que se utilizó para incrustar la firma. |
| [ShapePosition](../../groupdocs.signature.options/verifyoptions/shapeposition) { get; set; } | Especifica la posición de la forma en el diseño del documento. Para verificar firmas en encabezados/pies de página. |
| [UseFullDataExtraction](../../groupdocs.signature.options/imagedigitalverifyoptions/usefulldataextraction) { get; set; } | Cuando es verdadero, realiza una extracción completa de datos (AnalyzePercentageDigitalSignature) para máxima precisión. |

### Ver también

* class [VerifyOptions](../verifyoptions)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.signature.dll -->
