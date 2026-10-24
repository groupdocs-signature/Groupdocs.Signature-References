---
title: "método to_date_time"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Convierte el valor de la firma de metadatos a un datetime.datetime."
type: docs
url: /es/python-net/groupdocs.signature.domain/imagemetadatasignature/to_date_time/
is_root: false
weight: 1070
---


## to_date_time

Convierte el valor de la firma de metadatos a un `datetime.datetime`.

Lanza una excepción si el valor de metadata no puede ser convertido. Si el valor original es de tipo cadena, se utiliza la cultura predeterminada de [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/).

```python
def to_date_time(self):
    ...
```

**Returns:** datetime.datetime: The metadata signature value as a `datetime.datetime`.

## to_date_time {#provider}

Convierte el valor de la firma de metadatos a un `datetime`.

Lanza una excepción si el valor de los metadatos no pudo convertirse.

```python
def to_date_time(self, provider):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| provider | `System.IFormatProvider` | Proveedor de formato de datos para usar con operaciones de conversión de datos. |

**Returns:** datetime: The metadata signature value as a `datetime`.

### Ver también
* class [`ImageMetadataSignature`](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/)
