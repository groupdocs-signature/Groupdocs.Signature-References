---
title: "Permisos"
second_title: "Referencia de la API de GroupDocs.Signature para .NET"
description: "Especifica permisos configurables para documentos PDF, como impresión, modificación de contenido y extracción de datos. Estas configuraciones se aplican solo al formato PDF y controlan el acceso del usuario y sus capacidades de interacción."
type: docs
weight: 1790
url: /es/net/groupdocs.signature.options/permissions/
---
## Permissions enumeration

Especifica permisos configurables para documentos PDF, como impresión, modificación de contenido y extracción de datos. Estas configuraciones se aplican solo al formato PDF y controlan el acceso del usuario y las capacidades de interacción.

```csharp
[Flags]
public enum Permissions
```

### Values

| Nombre | Value | Descripción |
| --- | --- | --- |
| None | `0` | Permitir todas las acciones, incluyendo impresión, modificación y extracción de datos. |
| DenyPrinting | `1` | Denegar la impresión del documento. |
| DenyModification | `2` | Denegar la modificación de contenido, incluyendo rellenar formularios y agregar o modificar anotaciones. |
| DenyDataExtraction | `4` | Denegar la extracción de texto y gráficos del documento. |
| DenyAll | `7` | Denegar todas las acciones, incluyendo impresión, modificación y extracción de datos. |

### Ver también

* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.signature.dll -->
