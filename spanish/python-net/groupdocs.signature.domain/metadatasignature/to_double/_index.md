---
title: "método to_double"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Convierte el valor de la firma de metadatos a un número de punto flotante."
type: docs
url: /es/python-net/groupdocs.signature.domain/metadatasignature/to_double/
is_root: false
weight: 1130
---


## to_double

Convierte el valor de la firma de metadatos a un número de punto flotante.

Genera una excepción si el valor de los metadatos no puede convertirse. Si el valor original es de tipo cadena, se utiliza la cultura predeterminada de [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/).

```python
def to_double(self):
    ...
```

**Returns:** float: The metadata signature value as a float.

## to_double {#provider}

Convierte a Double.

```python
def to_double(self, provider):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| provider | `System.IFormatProvider` | Proveedor de formato de datos para usar con operaciones de conversión de datos. |

**Returns:** float: The metadata signature value as a float.

### Ver también
* class [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)
