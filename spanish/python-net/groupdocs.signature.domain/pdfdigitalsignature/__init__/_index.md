---
title: "constructor __init__"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Inicializa una firma digital PDF sin un certificado."
type: docs
url: /es/python-net/groupdocs.signature.domain/pdfdigitalsignature/__init__/
is_root: false
weight: 10
---


## __init__

Inicializa una firma digital PDF sin un certificado.

```python
def __init__(self):
    ...
```

## __init__ {#store}

Inicializa una firma digital PDF usando el almacén X509 especificado. Se usará el primer certificado del almacén.

```python
def __init__(self, store):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| store | `System.Security.Cryptography.X509Certificates.X509Store` | almacén X509. |

## __init__ {#store-index}

Inicializa una firma digital PDF usando el almacén X509 especificado y el índice del certificado.

```python
def __init__(self, store, index):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| store | `System.Security.Cryptography.X509Certificates.X509Store` | almacén X509. |
| index | `int` | Índice del certificado. |

## __init__ {#certificate}

Inicializa una firma digital PDF con el certificado X509 especificado.

```python
def __init__(self, certificate):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| certificate | `System.Security.Cryptography.X509Certificates.X509Certificate2` | certificado X509. |

### Ver también
* class [`PdfDigitalSignature`](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/)
