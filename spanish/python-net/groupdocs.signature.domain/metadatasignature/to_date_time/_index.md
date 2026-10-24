---
title: "método to_date_time"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Convierte el valor de la firma de metadatos a una fecha y hora."
type: docs
url: /es/python-net/groupdocs.signature.domain/metadatasignature/to_date_time/
is_root: false
weight: 1090
---


## to_date_time

Convierte el valor de la firma de metadatos a una fecha y hora.

Si el valor de los metadatos no puede convertirse, se lanza una excepción. Cuando el valor original es de tipo cadena, se utiliza la cultura predeterminada de [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/) para la conversión.

```python
def to_date_time(self):
    ...
```

**Returns:** datetime: The metadata signature value as a datetime.

### Ejemplo

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSearchOptions

with Signature("signed.pdf") as signature:
    result = signature.search([MetadataSearchOptions()])
    for metadata in result.signatures:
        try:
            dt = metadata.to_date_time()
            print(f"{metadata.name} as datetime: {dt}")
        except Exception as e:
            print(f"Could not convert {metadata.name} to datetime: {e}")
```

## to_date_time {#provider}

Convierte el valor de la firma de metadatos a una fecha y hora.

```python
def to_date_time(self, provider):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| provider | `System.IFormatProvider` | Proveedor de formato de datos para usar con operaciones de conversión de datos. |

**Returns:** datetime.datetime: The metadata signature value as a datetime.

Lanza una excepción si el valor de los metadatos no pudo convertirse.

### Ver también
* class [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)
