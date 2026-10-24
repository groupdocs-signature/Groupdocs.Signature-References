---
title: "método load_digital_signatures"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Carga firmas digitales de todos los almacenes de certificados X509 del sistema."
type: docs
url: /es/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures/
is_root: false
weight: 1050
---


## load_digital_signatures

Carga firmas digitales de todos los almacenes de certificados X509 del sistema.

```python
def load_digital_signatures(cls):
    ...
```

**Returns:** list[DigitalSignature]: List of digital signatures.

## load_digital_signatures {#store_name}

Carga firmas digitales de un almacenamiento de certificados.

```python
def load_digital_signatures(cls, store_name):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| store_name | `System.Security.Cryptography.X509Certificates.StoreName` | Nombre de un almacenamiento digital que contiene certificados. |

**Returns:** list[DigitalSignature]: List of digital signatures.

## load_digital_signatures {#store_name}

Carga firmas digitales de un almacenamiento de certificados.

```python
def load_digital_signatures(cls, store_name):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| store_name | `str` | Nombre personalizado de un almacenamiento digital que contiene certificados. |

**Returns:** list[DigitalSignature]: List of DigitalSignature objects.

## load_digital_signatures {#store_name-store_location}

Carga firmas digitales de un almacenamiento de certificados digitales ubicado en una ubicación específica.

```python
def load_digital_signatures(cls, store_name, store_location):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| store_name | `System.Security.Cryptography.X509Certificates.StoreName` | Nombre de un almacenamiento digital que contiene certificados. |
| store_location | `System.Security.Cryptography.X509Certificates.StoreLocation` | Ubicación de un almacenamiento de certificados digitales. |

**Returns:** list[DigitalSignature]: List of DigitalSignature objects.

## load_digital_signatures {#store_name-store_location}

Carga firmas digitales de un almacenamiento de certificados digitales ubicado en una ubicación específica.

```python
def load_digital_signatures(cls, store_name, store_location):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| store_name | `str` | Nombre personalizado de un almacenamiento digital que contiene certificados. |
| store_location | `System.Security.Cryptography.X509Certificates.StoreLocation` | Ubicación de un almacenamiento de certificados digitales. |

**Returns:** list[DigitalSignature]: List of digital signatures.

### Ver también
* class [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)
