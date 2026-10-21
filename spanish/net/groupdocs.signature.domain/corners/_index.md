---
title: "Corners"
second_title: "Referencia de la API de GroupDocs.Signature para .NET"
description: "Representa las esquinas de un objeto gráfico cuadrado."
type: docs
weight: 110
url: /es/net/groupdocs.signature.domain/corners/
---
## Corners class

Representa las esquinas de un objeto gráfico cuadrado.

```csharp
public class Corners : ICloneable
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Corners](corners#constructor)() | Inicializa una nueva instancia de la clase Corners usando valores cero. |
| [Corners](corners#constructor_1)(double) | Inicializa una nueva instancia de la clase Corners usando el valor suministrado para todas las esquinas. |
| [Corners](corners#constructor_2)(double, double, double, double) | Inicializa una nueva instancia de la clase Corners usando los valores suministrados. |

## Properties

| Nombre | Descripción |
| --- | --- |
| [All](../../groupdocs.signature.domain/corners/all) { get; set; } | Obtiene o establece el valor para todas las esquinas. Cambiar cualquier esquina parcial, como la superior derecha, hace que esta propiedad sea igual a 0; |
| [BottomLeft](../../groupdocs.signature.domain/corners/bottomleft) { get; set; } | Obtiene o establece el valor de la esquina inferior izquierda. |
| [BottomRight](../../groupdocs.signature.domain/corners/bottomright) { get; set; } | Obtiene o establece el valor de la esquina inferior derecha. |
| [TopLeft](../../groupdocs.signature.domain/corners/topleft) { get; set; } | Obtiene o establece el valor de la esquina superior izquierda. |
| [TopRight](../../groupdocs.signature.domain/corners/topright) { get; set; } | Obtiene o establece el valor de la esquina superior derecha. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Clone](../../groupdocs.signature.domain/corners/clone)() | Obtiene una copia de este objeto. |
| override [Equals](../../groupdocs.signature.domain/corners/equals)(object) | Sobrescribir el método equals |
| override [GetHashCode](../../groupdocs.signature.domain/corners/gethashcode)() | Sobrescribe la obtención del valor único del código hash |

## Fields

| Nombre | Descripción |
| --- | --- |
| static readonly [Empty](../../groupdocs.signature.domain/corners/empty) | Proporciona un objeto Corners sin datos. |

### Ver también

* namespace [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.signature.dll -->
