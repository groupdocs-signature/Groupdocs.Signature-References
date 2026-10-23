---
title: "metode to_double"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Mengonversi nilai tanda tangan metadata ke float."
type: docs
url: /id/python-net/groupdocs.signature.domain/metadatasignature/to_double/
is_root: false
weight: 1130
---


## to_double

Mengonversi nilai tanda tangan metadata ke float.

Menghasilkan pengecualian jika nilai metadata tidak dapat dikonversi. Jika nilai asli berbasis string, budaya default dari [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/) digunakan.

```python
def to_double(self):
    ...
```

**Returns:** float: The metadata signature value as a float.

## to_double {#provider}

Mengonversi ke Double.

```python
def to_double(self, provider):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| provider | `System.IFormatProvider` | Penyedia format data untuk digunakan dengan operasi konversi data. |

**Returns:** float: The metadata signature value as a float.

### Lihat Juga
* class [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)
