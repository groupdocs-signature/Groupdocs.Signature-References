---
title: "DoPaletteCorrection"
second_title: "Referencia de la API de GroupDocs.Signature para .NET"
description: "Obtiene o establece un valor que indica si se aplica la corrección de paleta."
type: docs
weight: 40
url: /es/net/groupdocs.signature.options/gifsaveoptions/dopalettecorrection/
---
## GifSaveOptions.DoPaletteCorrection property

Obtiene o establece un valor que indica si se aplica la corrección de paleta.

```csharp
public bool DoPaletteCorrection { get; set; }
```

### Observaciones

La corrección de paleta significa que siempre que la imagen se exporta a GIF, los colores de la imagen fuente serán analizados para crear la paleta que mejor coincida (en caso de que la Paleta de la imagen no exista o no esté especificada en las opciones). El proceso de análisis lleva algo de tiempo, sin embargo la imagen resultante tendrá la paleta de colores que mejor coincida y el resultado será visualmente mejor.

### Ver también

* class [GifSaveOptions](../../gifsaveoptions)
* namespace [GroupDocs.Signature.Options](../../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.signature.dll -->
