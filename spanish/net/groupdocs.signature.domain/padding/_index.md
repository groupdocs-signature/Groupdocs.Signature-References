---
title: "Padding"
second_title: "Referencia de la API de GroupDocs.Signature para .NET"
description: "Representa la información de relleno o margen asociada al elemento."
type: docs
weight: 820
url: /es/net/groupdocs.signature.domain/padding/
---
## Padding class

Representa la información de relleno o margen asociada al elemento.

```csharp
public class Padding : ICloneable
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Padding](padding#constructor)() | Inicializa una nueva instancia de la clase Padding usando valores cero. |
| [Padding](padding#constructor_1)(int) | Inicializa una nueva instancia de la clase Padding usando el tamaño de relleno suministrado para todos los bordes. |
| [Padding](padding#constructor_2)(int, int, int, int) | Inicializa una nueva instancia de la clase Padding usando los tamaños de relleno suministrados. |

## Properties

| Nombre | Descripción |
| --- | --- |
| [All](../../groupdocs.signature.domain/padding/all) { get; set; } | Obtiene o establece el valor de relleno para todos los bordes. Cambiar cualquier borde parcial, como el izquierdo o el superior, hace que esta propiedad sea igual a 0; |
| [Bottom](../../groupdocs.signature.domain/padding/bottom) { get; set; } | Obtiene o establece el valor de relleno para el borde inferior. |
| [Horizontal](../../groupdocs.signature.domain/padding/horizontal) { get; } | Obtiene el relleno combinado para los bordes derecho e izquierdo. |
| [Left](../../groupdocs.signature.domain/padding/left) { get; set; } | Obtiene o establece el valor de relleno para el borde izquierdo. |
| [Right](../../groupdocs.signature.domain/padding/right) { get; set; } | Obtiene o establece el valor de relleno para el borde derecho. |
| [Top](../../groupdocs.signature.domain/padding/top) { get; set; } | Obtiene o establece el valor de relleno para el borde superior. |
| [Vertical](../../groupdocs.signature.domain/padding/vertical) { get; } | Obtiene el relleno combinado para los bordes superior e inferior. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Clone](../../groupdocs.signature.domain/padding/clone)() | Obtiene una copia de este objeto. |

## Fields

| Nombre | Descripción |
| --- | --- |
| static readonly [Empty](../../groupdocs.signature.domain/padding/empty) | Proporciona un objeto Padding sin relleno. |

### Ver también

* namespace [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.signature.dll -->
