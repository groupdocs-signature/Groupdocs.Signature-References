---
title: "costruttore __init__"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Inizializza una firma digitale con parametri predefiniti."
type: docs
url: /it/python-net/groupdocs.signature.domain/digitalsignature/__init__/
is_root: false
weight: 10
---


## __init__

Inizializza una firma digitale con parametri predefiniti.

```python
def __init__(self):
    ...
```

## __init__ {#signature_id}

Inizializza una firma digitale con un identificatore di firma noto.

```python
def __init__(self, signature_id):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| signature_id | `str` |  |

## __init__ {#store}

Inizializza un DigitalSignature utilizzando il primo certificato dal negozio X509 specificato.

```python
def __init__(self, store):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| store | `System.Security.Cryptography.X509Certificates.X509Store` | archivio X509. |

## __init__ {#store-index}

Inizializza un DigitalSignature basato sul negozio X509 specificato e sull'indice del certificato.

```python
def __init__(self, store, index):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| store | `System.Security.Cryptography.X509Certificates.X509Store` | archivio X509. |
| index | `int` | Indice del certificato. |

## __init__ {#certificate}

Inizializza una firma digitale con il certificato specificato.

```python
def __init__(self, certificate):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| certificate | `System.Security.Cryptography.X509Certificates.X509Certificate2` | certificato X509. |

### Vedi anche
* class [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)
