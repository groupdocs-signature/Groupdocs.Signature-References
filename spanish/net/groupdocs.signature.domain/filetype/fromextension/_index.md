---
title: FromExtension
second_title: Referencia de API de GroupDocs.Signature para .NET
description: Asigna la extensión del archivo al tipo de archivo.
type: docs
weight: 570
url: /es/net/groupdocs.signature.domain/filetype/fromextension/
---
## FileType.FromExtension method

Asigna la extensión del archivo al tipo de archivo.

```csharp
public static FileType FromExtension(string extension)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| extension | String | Extensión del archivo (incluido el punto "."). |

### Valor_devuelto

Cuando el tipo de archivo es compatible, lo devuelve; de lo contrario, devuelve el valor predeterminado[`Unknown`](../unknown) Tipo de archivo.

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | arrojado cuando*extension* es una cadena nula o vacía. |

### Ver también

* class [FileType](../../filetype)
* espacio de nombres [GroupDocs.Signature.Domain](../../filetype)
* asamblea [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->