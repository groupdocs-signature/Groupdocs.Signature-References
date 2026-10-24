---
title: "Método add_image_signature"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Crea una nueva ImageMetadataSignature con los argumentos proporcionados y la agrega a la colección."
type: docs
url: /es/python-net/groupdocs.signature.options/metadatasignoptions/add_image_signature/
is_root: false
weight: 1020
---


## add_image_signature {#id-value}

Crea una nueva ImageMetadataSignature con los argumentos proporcionados y la agrega a la colección.

```python
def add_image_signature(self, id, value):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| id | `System.UInt16` | Identificador único para el nombre de la firma de metadatos de imagen. Consulte las referencias para las especificaciones de etiquetas Exif para posibles valores de id. |
| value | `Any` | Valor de metadatos. |

**Returns:** ImageMetadataSignature: The newly created signature that was added to the MetadataSignatures collection.

### Ver también
* class [`MetadataSignOptions`](/signature/python-net/groupdocs.signature.options/metadatasignoptions/)
