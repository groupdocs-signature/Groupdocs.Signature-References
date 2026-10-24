---
title: "método to_string"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Convierte el valor de la firma de metadatos a una cadena."
type: docs
url: /es/python-net/groupdocs.signature.domain/imagemetadatasignature/to_string/
is_root: false
weight: 1170
---


## to_string

Convierte el valor de la firma de metadatos a una cadena.

```python
def to_string(self):
    ...
```

**Returns:** str: The metadata signature value.

## to_string {#format}

Convierte el valor de la firma de metadatos a una cadena usando el formato especificado.

Convierte una propiedad booleana en \"True\" o \"False\". Se utiliza la información de cultura predeterminada de [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/).

```python
def to_string(self, format):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| format | `str` | Cadena de formato de datos. |

**Returns:** str: The metadata signature value as a string.

## to_string {#format-provider}

Convierte a una cadena con el formato especificado.

Convierte una propiedad booleana en "True" o "False".

```python
def to_string(self, format, provider):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| format | `str` | Cadena de formato de datos. |
| provider | `System.IFormatProvider` | Proveedor de formato de datos para usar con operaciones de conversión de datos. |

**Returns:** str: The metadata signature value as a string.

### Ver también
* class [`ImageMetadataSignature`](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/)
