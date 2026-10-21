---
title: "PixelAspectRatio"
second_title: "Referencia de la API de GroupDocs.Signature para .NET"
description: "Obtiene o establece la relación de aspecto de píxel del GIF."
type: docs
weight: 80
url: /es/net/groupdocs.signature.options/gifsaveoptions/pixelaspectratio/
---
## GifSaveOptions.PixelAspectRatio property

Obtiene o establece la relación de aspecto de píxel del GIF.

```csharp
public byte PixelAspectRatio { get; set; }
```

### Observaciones

Pixel Aspect Ratio - Factor utilizado para calcular una aproximación de la relación de aspecto del píxel en la imagen original. Si el valor del campo no es 0, esta aproximación de la relación de aspecto se calcula basándose en la fórmula: Aspect Ratio = (Pixel Aspect Ratio + 15) / 64 El Pixel Aspect Ratio se define como el cociente del ancho del píxel sobre su altura. El rango de valores en este campo permite especificar el píxel más ancho de 4:1 al píxel más alto de 1:4 en incrementos de 1/64. Valores: 0 - No se proporciona información de relación de aspecto. 1..255 - Valor utilizado en el cálculo.

### Ver también

* class [GifSaveOptions](../../gifsaveoptions)
* namespace [GroupDocs.Signature.Options](../../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.signature.dll -->
