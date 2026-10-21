---
title: "TextureBrush"
second_title: "Referencia de la API de GroupDocs.Signature para .NET"
description: "Representa un pincel de textura."
type: docs
weight: 570
url: /es/net/groupdocs.signature.domain.extensions/texturebrush/
---
## TextureBrush class

Representa un pincel de textura.

```csharp
public class TextureBrush : Brush
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [TextureBrush](texturebrush#constructor)() | Inicializa una nueva instancia de la clase TextureBrush con valores predeterminados. |
| [TextureBrush](texturebrush#constructor_1)(Stream) | Inicializa una nueva instancia de la clase TextureBrush con la opción de flujo de imagen. |
| [TextureBrush](texturebrush#constructor_2)(string) | Inicializa una nueva instancia de la clase TextureBrush con archivo de imagen. |

## Properties

| Nombre | Descripción |
| --- | --- |
| [ImageFilePath](../../groupdocs.signature.domain.extensions/texturebrush/imagefilepath) { get; set; } | Obtiene o establece la ruta del archivo de imagen de textura. Esta propiedad se usa solo si ImageStream no está especificado. |
| [ImageStream](../../groupdocs.signature.domain.extensions/texturebrush/imagestream) { get; set; } | Obtiene o establece el flujo de imagen de textura. Si se especifica esta propiedad, siempre se usa en lugar de ImageFilePath. |

### Ver también

* class [Brush](../brush)
* namespace [GroupDocs.Signature.Domain.Extensions](../../groupdocs.signature.domain.extensions)
* assembly [GroupDocs.Signature](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.signature.dll -->
