---
title: "metode to_single"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Mengonversi ke float."
type: docs
url: /id/python-net/groupdocs.signature.domain/imagemetadatasignature/to_single/
is_root: false
weight: 1150
---


## to_single

Mengonversi ke float.

Melemparkan pengecualian jika nilai Metadata tidak dapat dikonversi. Jika nilai asli berbasis string, informasi properti budaya default akan digunakan dari [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/).

```python
def to_single(self):
    ...
```

**Returns:** float: The Image Metadata Signature value as float.

## to_single {#provider}

Mengonversi nilai tanda tangan metadata ke float.

Menaikkan pengecualian jika nilai metadata tidak dapat dikonversi.

```python
def to_single(self, provider):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| provider | `System.IFormatProvider` | Penyedia format data untuk digunakan dengan operasi konversi data. |

**Returns:** float: The metadata signature value as a float.

### Lihat Juga
* class [`ImageMetadataSignature`](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/)
