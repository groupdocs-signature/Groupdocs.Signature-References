---
title: "método to_double"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Convierte a un float."
type: docs
url: /es/python-net/groupdocs.signature.domain/imagemetadatasignature/to_double/
is_root: false
weight: 1110
---


## to_double

Convierte a un float.

Lanza una excepción si el valor de metadata no puede ser convertido. Si el valor original es de tipo cadena, se utiliza la cultura predeterminada de [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/).

```python
def to_double(self):
    ...
```

**Returns:** float: The Image Metadata Signature value as a float.

## to_double {#provider}

Convierte el valor de la firma de metadatos a un número de punto flotante.

Utiliza el proveedor de formato de datos especificado para realizar la conversión.

```python
def to_double(self, provider):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| provider | `System.IFormatProvider` | Proveedor de formato de datos para usar con operaciones de conversión de datos. |

**Returns:** float: The metadata signature value as a float.

### Ver también
* class [`ImageMetadataSignature`](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/)
