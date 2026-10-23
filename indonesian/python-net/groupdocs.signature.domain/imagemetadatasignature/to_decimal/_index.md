---
title: "metode to_decimal"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Mengonversi menjadi Decimal."
type: docs
url: /id/python-net/groupdocs.signature.domain/imagemetadatasignature/to_decimal/
is_root: false
weight: 1090
---


## to_decimal

Mengonversi menjadi Decimal.

Menghasilkan pengecualian jika nilai metadata tidak dapat dikonversi. Jika nilai asli berbasis string, budaya default dari [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/) digunakan.

```python
def to_decimal(self):
    ...
```

**Returns:** decimal.Decimal: The Image Metadata Signature value as Decimal.

## to_decimal {#provider}

Mengonversi nilai signature metadata menjadi desimal.

Menaikkan pengecualian jika nilai metadata tidak dapat dikonversi.

```python
def to_decimal(self, provider):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| provider | `System.IFormatProvider` | Penyedia format data untuk digunakan dengan operasi konversi data. |

**Returns:** float: The metadata signature value as a decimal.

### Lihat Juga
* class [`ImageMetadataSignature`](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/)
