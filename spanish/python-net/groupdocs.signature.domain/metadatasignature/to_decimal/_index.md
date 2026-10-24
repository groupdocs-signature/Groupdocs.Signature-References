---
title: "método to_decimal"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Convierte el valor de la firma de metadatos a Decimal."
type: docs
url: /es/python-net/groupdocs.signature.domain/metadatasignature/to_decimal/
is_root: false
weight: 1110
---


## to_decimal

Convierte el valor de la firma de metadatos a Decimal.

Genera una excepción si el valor de los metadatos no pudo convertirse. Si el valor original es de tipo cadena, la información de la cultura predeterminada se obtendrá de [`SignatureSettings.DefaultCulture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/).

```python
def to_decimal(self):
    ...
```

**Returns:** The metadata signature value as Decimal.

## to_decimal {#provider}

Convierte el valor de la firma de metadatos a Decimal.

```python
def to_decimal(self, provider):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| provider | `System.IFormatProvider` | Proveedor de formato de datos para usar con operaciones de conversión de datos. |

**Returns:** The metadata signature value as Decimal.

### Ver también
* class [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)
