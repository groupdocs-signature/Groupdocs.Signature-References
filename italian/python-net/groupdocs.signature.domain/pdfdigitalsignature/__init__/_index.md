---
title: "costruttore __init__"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Inizializza una firma digitale PDF senza certificato."
type: docs
url: /it/python-net/groupdocs.signature.domain/pdfdigitalsignature/__init__/
is_root: false
weight: 10
---


## __init__

Inizializza una firma digitale PDF senza certificato.

```python
def __init__(self):
    ...
```

## __init__ {#store}

Inizializza una firma digitale PDF utilizzando lo store X509 specificato. Verrà utilizzato il primo certificato dello store.

```python
def __init__(self, store):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| store | `System.Security.Cryptography.X509Certificates.X509Store` | archivio X509. |

## __init__ {#store-index}

Inizializza una firma digitale PDF utilizzando lo store X509 specificato e l'indice del certificato.

```python
def __init__(self, store, index):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| store | `System.Security.Cryptography.X509Certificates.X509Store` | archivio X509. |
| index | `int` | Indice del certificato. |

## __init__ {#certificate}

Inizializza una firma digitale PDF con il certificato X509 specificato.

```python
def __init__(self, certificate):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| certificate | `System.Security.Cryptography.X509Certificates.X509Certificate2` | certificato X509. |

### Vedi anche
* class [`PdfDigitalSignature`](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/)
