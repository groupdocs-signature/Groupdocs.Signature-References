---
title: "método to_string"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Convierte el valor de la firma de metadatos a una cadena usando el método ToString sobrescrito."
type: docs
url: /es/python-net/groupdocs.signature.domain/spreadsheetmetadatasignature/to_string/
is_root: false
weight: 1030
---


## to_string

Convierte el valor de la firma de metadatos a una cadena usando el método sobrescrito `ToString`.

Convierte una propiedad booleana en `True` o `False`. Para otros tipos de datos, se utiliza el proveedor de formato de datos predeterminado.

```python
def to_string(self):
    ...
```

**Returns:** str: The metadata signature value as a string.

## to_string {#format-provider}

Convierte la firma de metadatos a una cadena usando el formato especificado.

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
* class [`SpreadsheetMetadataSignature`](/signature/python-net/groupdocs.signature.domain/spreadsheetmetadatasignature/)
