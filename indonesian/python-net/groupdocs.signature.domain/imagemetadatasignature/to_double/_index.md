---
title: "metode to_double"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Mengonversi menjadi float."
type: docs
url: /id/python-net/groupdocs.signature.domain/imagemetadatasignature/to_double/
is_root: false
weight: 1110
---


## to_double

Mengonversi menjadi float.

Melemparkan pengecualian jika nilai metadata tidak dapat dikonversi. Jika nilai asli berbasis string, budaya default dari [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/) digunakan.

```python
def to_double(self):
    ...
```

**Returns:** float: The Image Metadata Signature value as a float.

## to_double {#provider}

Mengonversi nilai tanda tangan metadata ke float.

Menggunakan penyedia format data yang ditentukan untuk melakukan konversi.

```python
def to_double(self, provider):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| provider | `System.IFormatProvider` | Penyedia format data untuk digunakan dengan operasi konversi data. |

**Returns:** float: The metadata signature value as a float.

### Lihat Juga
* class [`ImageMetadataSignature`](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/)
