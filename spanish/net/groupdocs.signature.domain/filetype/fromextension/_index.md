---
title: "FromExtension"
second_title: "Referencia de la API de GroupDocs.Signature para .NET"
description: "Mapea la extensión de archivo al tipo de archivo."
type: docs
weight: 660
url: /es/net/groupdocs.signature.domain/filetype/fromextension/
---
## FileType.FromExtension method

Mapea la extensión de archivo al tipo de archivo.

```csharp
public static FileType FromExtension(string extension)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| extension | String | Extensión de archivo (incluyendo el punto "."). |

### Valor de retorno

Cuando el tipo de archivo es compatible lo devuelve, de lo contrario devuelve el tipo de archivo predeterminado [`Unknown`](../unknown).

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | Se lanza cuando *extension* es nulo o una cadena vacía. |

### Ver también

* class [FileType](../../filetype)
* namespace [GroupDocs.Signature.Domain](../../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.signature.dll -->
