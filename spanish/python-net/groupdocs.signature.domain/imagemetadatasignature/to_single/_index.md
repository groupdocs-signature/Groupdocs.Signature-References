---
title: "método to_single"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Convierte a float."
type: docs
url: /es/python-net/groupdocs.signature.domain/imagemetadatasignature/to_single/
is_root: false
weight: 1150
---


## to_single

Convierte a float.

Lanza una excepción si el valor de Metadata no se pudo convertir. Si el valor original es de tipo cadena, se utilizará la información de la propiedad de cultura predeterminada de [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/).

```python
def to_single(self):
    ...
```

**Returns:** float: The Image Metadata Signature value as float.

## to_single {#provider}

Convierte el valor de la firma de metadatos a un número de punto flotante.

Lanza una excepción si el valor de metadatos no pudo ser convertido.

```python
def to_single(self, provider):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| provider | `System.IFormatProvider` | Proveedor de formato de datos para usar con operaciones de conversión de datos. |

**Returns:** float: The metadata signature value as a float.

### Ver también
* class [`ImageMetadataSignature`](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/)
