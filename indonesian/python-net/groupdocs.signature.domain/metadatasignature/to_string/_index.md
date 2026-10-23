---
title: "metode to_string"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Mengonversi tanda tangan metadata ke string."
type: docs
url: /id/python-net/groupdocs.signature.domain/metadatasignature/to_string/
is_root: false
weight: 1180
---


## to_string

Mengonversi tanda tangan metadata ke string.

Mengonversi properti boolean menjadi "True" atau "False". Untuk tipe data lain, penyedia format data default akan digunakan.

```python
def to_string(self):
    ...
```

**Returns:** str: The metadata signature value as a string.

## to_string {#format}

Mengonversi tanda tangan metadata ke string menggunakan format yang ditentukan.

Mengonversi properti boolean menjadi "True" atau "False". Informasi properti budaya default akan digunakan dari properti SignatureSettings [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/).

```python
def to_string(self, format):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| format | `str` | String format data. |

**Returns:** str: The metadata signature value as a string.

## to_string {#format-provider}

Mengonversi ke string dengan format yang ditentukan.

Mengonversi properti boolean menjadi "True" atau "False".

```python
def to_string(self, format, provider):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| format | `str` | String format data. |
| provider | `System.IFormatProvider` | Penyedia format data untuk digunakan dengan operasi konversi data. |

**Returns:** The metadata signature value as a string.

### Lihat Juga
* class [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)
