---
title: "método to_single"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Convierte el valor de la firma de metadatos a un número de punto flotante."
type: docs
url: /es/python-net/groupdocs.signature.domain/metadatasignature/to_single/
is_root: false
weight: 1160
---


## to_single

Convierte el valor de la firma de metadatos a un número de punto flotante.

Lanza una excepción si el valor de metadata no puede ser convertido. Si el valor original es de tipo cadena, se utiliza la cultura predeterminada de [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/).

```python
def to_single(self):
    ...
```

**Returns:** float: The metadata signature value as a float.

## to_single {#provider}

Convierte a float.

```python
def to_single(self, provider):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| provider | `System.IFormatProvider` | Proveedor de formato de datos para usar con operaciones de conversión de datos. |

**Returns:** float: The Metadata Signature value as float.

### Ver también
* class [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)
