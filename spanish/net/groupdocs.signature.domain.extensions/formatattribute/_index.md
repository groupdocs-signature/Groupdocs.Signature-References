---
title: "FormatAttribute"
second_title: "Referencia de la API de GroupDocs.Signature para .NET"
description: "Indica a la serialización de objetos que serialice el miembro con el nombre y formato especificados."
type: docs
weight: 280
url: /es/net/groupdocs.signature.domain.extensions/formatattribute/
---
## FormatAttribute class

Indica a la serialización de objetos que serialice el miembro con el nombre y formato especificados.

```csharp
[AttributeUsage(AttributeTargets.Property | AttributeTargets.Field | AttributeTargets.Parameter)]
public sealed class FormatAttribute : Attribute
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [FormatAttribute](formatattribute#constructor)(string) | Crea el atributo Format con la propiedad Name dada. |
| [FormatAttribute](formatattribute#constructor_1)(string, string) | Crea el atributo Format con la propiedad Name dada. |

## Properties

| Nombre | Descripción |
| --- | --- |
| [PropertyFormat](../../groupdocs.signature.domain.extensions/formatattribute/propertyformat) { get; set; } | Obtiene o establece el formato de serialización de la propiedad. |
| [PropertyName](../../groupdocs.signature.domain.extensions/formatattribute/propertyname) { get; set; } | Obtiene o establece el nombre de la propiedad. |

### Ver también

* namespace [GroupDocs.Signature.Domain.Extensions](../../groupdocs.signature.domain.extensions)
* assembly [GroupDocs.Signature](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.signature.dll -->
