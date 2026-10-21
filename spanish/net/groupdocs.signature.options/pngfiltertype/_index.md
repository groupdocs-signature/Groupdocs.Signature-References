---
title: "PngFilterType"
second_title: "Referencia de la API de GroupDocs.Signature para .NET"
description: "Representa el tipo de filtro de imagen PNG."
type: docs
weight: 1810
url: /es/net/groupdocs.signature.options/pngfiltertype/
---
## PngFilterType enumeration

Representa el tipo de filtro de imagen PNG.

```csharp
public enum PngFilterType
```

### Values

| Nombre | Value | Descripción |
| --- | --- | --- |
| None | `0` | El filtro nulo, significa que no hay filtrado para las filas de datos de imagen. |
| Sub | `1` | El filtro sub, significa que se aplicará filtrado sustractivo a los datos de imagen. |
| Up | `2` | El filtro up, significa que se aplicará un filtro de sustracción fila por fila. |
| Avg | `3` | El filtro avg, significa que se aplicará un filtro promedio a los datos de imagen. |
| Paeth | `4` | El filtro predictor de ruta. |
| Adaptive | `5` | El filtrado adaptativo, significa que el proceso de guardado elegirá el filtro más adecuado para cada fila de datos. Mejor compresión, tiempo de ejecución más lento. |

### Ver también

* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.signature.dll -->
