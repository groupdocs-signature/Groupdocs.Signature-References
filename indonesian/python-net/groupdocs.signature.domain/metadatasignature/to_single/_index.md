---
title: "metode to_single"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Mengonversi nilai tanda tangan metadata ke float."
type: docs
url: /id/python-net/groupdocs.signature.domain/metadatasignature/to_single/
is_root: false
weight: 1160
---


## to_single

Mengonversi nilai tanda tangan metadata ke float.

Melemparkan pengecualian jika nilai metadata tidak dapat dikonversi. Jika nilai asli berbasis string, budaya default dari [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/) digunakan.

```python
def to_single(self):
    ...
```

**Returns:** float: The metadata signature value as a float.

## to_single {#provider}

Mengonversi ke float.

```python
def to_single(self, provider):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| provider | `System.IFormatProvider` | Penyedia format data untuk digunakan dengan operasi konversi data. |

**Returns:** float: The Metadata Signature value as float.

### Lihat Juga
* class [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)
