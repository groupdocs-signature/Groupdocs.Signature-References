---
title: "load_digital_signatures méthode"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Charge les signatures numériques depuis tous les magasins de certificats X509 du système."
type: docs
url: /fr/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures/
is_root: false
weight: 1050
---


## load_digital_signatures

Charge les signatures numériques depuis tous les magasins de certificats X509 du système.

```python
def load_digital_signatures(cls):
    ...
```

**Returns:** list[DigitalSignature]: List of digital signatures.

## load_digital_signatures {#store_name}

Charge les signatures numériques depuis un stockage de certificats.

```python
def load_digital_signatures(cls, store_name):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| store_name | `System.Security.Cryptography.X509Certificates.StoreName` | Nom d'un stockage numérique contenant des certificats. |

**Returns:** list[DigitalSignature]: List of digital signatures.

## load_digital_signatures {#store_name}

Charge les signatures numériques depuis un stockage de certificats.

```python
def load_digital_signatures(cls, store_name):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| store_name | `str` | Nom personnalisé d'un stockage numérique contenant des certificats. |

**Returns:** list[DigitalSignature]: List of DigitalSignature objects.

## load_digital_signatures {#store_name-store_location}

Charge les signatures numériques depuis un stockage de certificats numériques placé à un emplacement spécifique.

```python
def load_digital_signatures(cls, store_name, store_location):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| store_name | `System.Security.Cryptography.X509Certificates.StoreName` | Nom d'un stockage numérique contenant des certificats. |
| store_location | `System.Security.Cryptography.X509Certificates.StoreLocation` | Emplacement d'un stockage de certificats numériques. |

**Returns:** list[DigitalSignature]: List of DigitalSignature objects.

## load_digital_signatures {#store_name-store_location}

Charge les signatures numériques depuis un stockage de certificats numériques placé à un emplacement spécifique.

```python
def load_digital_signatures(cls, store_name, store_location):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| store_name | `str` | Nom personnalisé d'un stockage numérique contenant des certificats. |
| store_location | `System.Security.Cryptography.X509Certificates.StoreLocation` | Emplacement d'un stockage de certificats numériques. |

**Returns:** list[DigitalSignature]: List of digital signatures.

### Voir aussi
* class [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)
