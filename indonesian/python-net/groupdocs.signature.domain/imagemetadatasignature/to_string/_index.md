---
title: "metode to_string"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Mengonversi nilai signature metadata menjadi string."
type: docs
url: /id/python-net/groupdocs.signature.domain/imagemetadatasignature/to_string/
is_root: false
weight: 1170
---


## to_string

Mengonversi nilai signature metadata menjadi string.

```python
def to_string(self):
    ...
```

**Returns:** str: The metadata signature value.

## to_string {#format}

Mengonversi nilai signature metadata menjadi string menggunakan format yang ditentukan.

Mengonversi properti boolean menjadi "True" atau "False". Informasi budaya default dari [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/) digunakan.

```python
def to_string(self, format):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| format | `str` | String format data. |

**Returns:** str: The metadata signature value as a string.

## to_string {#format-provider}

Mengonversi menjadi string dengan format yang ditentukan.

Mengonversi properti boolean menjadi "True" atau "False".

```python
def to_string(self, format, provider):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| format | `str` | String format data. |
| provider | `System.IFormatProvider` | Penyedia format data untuk digunakan dengan operasi konversi data. |

**Returns:** str: The metadata signature value as a string.

### Lihat Juga
* class [`ImageMetadataSignature`](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/)
