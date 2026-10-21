---
title: "JpegCompressionMode"
second_title: "Referencia de la API de GroupDocs.Signature para .NET"
description: "Especifica modos de compresión JPEG."
type: docs
weight: 1690
url: /es/net/groupdocs.signature.options/jpegcompressionmode/
---
## JpegCompressionMode enumeration

Especifica modos de compresión JPEG.

```csharp
public enum JpegCompressionMode
```

### Values

| Nombre | Value | Descripción |
| --- | --- | --- |
| Baseline | `0` | La compresión básica. |
| Progressive | `1` | La compresión progresiva. |
| Lossless | `2` | La compresión sin pérdida. Use este tipo de compresión con cuidado porque muchos visores de imágenes no lo admiten. Si lo usa, intente asignar la propiedad [`ColorType`](../jpegsaveoptions/colortype) a valores Grayscale o Rgb. |
| JpegLs | `3` | La compresión JPEG-LS. Use este tipo de compresión con cuidado porque muchos visores de imágenes no lo admiten. Si lo usa, intente asignar la propiedad [`ColorType`](../jpegsaveoptions/colortype) al valor Grayscale. |

### Ver también

* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.signature.dll -->
