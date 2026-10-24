---
title: "método to_decimal"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Convierte a Decimal."
type: docs
url: /es/python-net/groupdocs.signature.domain/imagemetadatasignature/to_decimal/
is_root: false
weight: 1090
---


## to_decimal

Convierte a Decimal.

Genera una excepción si el valor de los metadatos no puede convertirse. Si el valor original es de tipo cadena, se utiliza la cultura predeterminada de [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/).

```python
def to_decimal(self):
    ...
```

**Returns:** decimal.Decimal: The Image Metadata Signature value as Decimal.

## to_decimal {#provider}

Convierte el valor de la firma de metadatos a un decimal.

Lanza una excepción si el valor de metadatos no pudo ser convertido.

```python
def to_decimal(self, provider):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| provider | `System.IFormatProvider` | Proveedor de formato de datos para usar con operaciones de conversión de datos. |

**Returns:** float: The metadata signature value as a decimal.

### Ver también
* class [`ImageMetadataSignature`](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/)
