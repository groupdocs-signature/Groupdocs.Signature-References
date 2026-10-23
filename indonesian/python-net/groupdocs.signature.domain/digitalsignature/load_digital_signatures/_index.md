---
title: "load_digital_signatures metode"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Muat tanda tangan digital dari semua penyimpanan sertifikat X509 sistem."
type: docs
url: /id/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures/
is_root: false
weight: 1050
---


## load_digital_signatures

Muat tanda tangan digital dari semua penyimpanan sertifikat X509 sistem.

```python
def load_digital_signatures(cls):
    ...
```

**Returns:** list[DigitalSignature]: List of digital signatures.

## load_digital_signatures {#store_name}

Muat tanda tangan digital dari penyimpanan sertifikat.

```python
def load_digital_signatures(cls, store_name):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| store_name | `System.Security.Cryptography.X509Certificates.StoreName` | Nama penyimpanan digital yang berisi sertifikat. |

**Returns:** list[DigitalSignature]: List of digital signatures.

## load_digital_signatures {#store_name}

Muat tanda tangan digital dari penyimpanan sertifikat.

```python
def load_digital_signatures(cls, store_name):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| store_name | `str` | Nama khusus penyimpanan digital yang berisi sertifikat. |

**Returns:** list[DigitalSignature]: List of DigitalSignature objects.

## load_digital_signatures {#store_name-store_location}

Muat tanda tangan digital dari penyimpanan sertifikat digital yang ditempatkan di lokasi tertentu.

```python
def load_digital_signatures(cls, store_name, store_location):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| store_name | `System.Security.Cryptography.X509Certificates.StoreName` | Nama penyimpanan digital yang berisi sertifikat. |
| store_location | `System.Security.Cryptography.X509Certificates.StoreLocation` | Lokasi penyimpanan sertifikat digital. |

**Returns:** list[DigitalSignature]: List of DigitalSignature objects.

## load_digital_signatures {#store_name-store_location}

Muat tanda tangan digital dari penyimpanan sertifikat digital yang ditempatkan pada lokasi tertentu.

```python
def load_digital_signatures(cls, store_name, store_location):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| store_name | `str` | Nama khusus penyimpanan digital yang berisi sertifikat. |
| store_location | `System.Security.Cryptography.X509Certificates.StoreLocation` | Lokasi penyimpanan sertifikat digital. |

**Returns:** list[DigitalSignature]: List of digital signatures.

### Lihat Juga
* class [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)
