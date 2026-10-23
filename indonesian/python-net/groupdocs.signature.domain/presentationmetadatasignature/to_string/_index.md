---
title: "metode to_string"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Mengonversi tanda tangan metadata ke string."
type: docs
url: /id/python-net/groupdocs.signature.domain/presentationmetadatasignature/to_string/
is_root: false
weight: 1030
---


## to_string

Mengonversi tanda tangan metadata ke string.

Mengonversi properti boolean menjadi "True" atau "False". Untuk tipe data lain, penyedia format data default digunakan.

```python
def to_string(self):
    ...
```

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

**Returns:** str: The metadata signature value as string.

### Lihat Juga
* class [`PresentationMetadataSignature`](/signature/python-net/groupdocs.signature.domain/presentationmetadatasignature/)
