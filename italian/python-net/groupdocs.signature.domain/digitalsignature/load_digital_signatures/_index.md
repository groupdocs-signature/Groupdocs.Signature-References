---
title: "metodo load_digital_signatures"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Carica firme digitali da tutti i negozi di certificati X509 di sistema."
type: docs
url: /it/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures/
is_root: false
weight: 1050
---


## load_digital_signatures

Carica firme digitali da tutti i negozi di certificati X509 di sistema.

```python
def load_digital_signatures(cls):
    ...
```

**Returns:** list[DigitalSignature]: List of digital signatures.

## load_digital_signatures {#store_name}

Carica firme digitali da un archivio di certificati.

```python
def load_digital_signatures(cls, store_name):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| store_name | `System.Security.Cryptography.X509Certificates.StoreName` | Nome di un archivio digitale contenente certificati. |

**Returns:** list[DigitalSignature]: List of digital signatures.

## load_digital_signatures {#store_name}

Carica firme digitali da un archivio di certificati.

```python
def load_digital_signatures(cls, store_name):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| store_name | `str` | Nome personalizzato di un archivio digitale contenente certificati. |

**Returns:** list[DigitalSignature]: List of DigitalSignature objects.

## load_digital_signatures {#store_name-store_location}

Carica firme digitali da un archivio di certificati digitali posizionato in una posizione specifica.

```python
def load_digital_signatures(cls, store_name, store_location):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| store_name | `System.Security.Cryptography.X509Certificates.StoreName` | Nome di un archivio digitale contenente certificati. |
| store_location | `System.Security.Cryptography.X509Certificates.StoreLocation` | Posizione di un archivio digitale di certificati. |

**Returns:** list[DigitalSignature]: List of DigitalSignature objects.

## load_digital_signatures {#store_name-store_location}

Carica firme digitali da un archivio di certificati digitali posizionato in una posizione specifica.

```python
def load_digital_signatures(cls, store_name, store_location):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| store_name | `str` | Nome personalizzato di un archivio digitale contenente certificati. |
| store_location | `System.Security.Cryptography.X509Certificates.StoreLocation` | Posizione di un archivio digitale di certificati. |

**Returns:** list[DigitalSignature]: List of digital signatures.

### Vedi anche
* class [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)
