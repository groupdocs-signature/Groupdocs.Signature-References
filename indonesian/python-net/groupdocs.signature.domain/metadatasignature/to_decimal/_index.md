---
title: "metode to_decimal"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Mengonversi nilai tanda tangan metadata ke Decimal."
type: docs
url: /id/python-net/groupdocs.signature.domain/metadatasignature/to_decimal/
is_root: false
weight: 1110
---


## to_decimal

Mengonversi nilai tanda tangan metadata ke Decimal.

Menghasilkan pengecualian jika nilai metadata tidak dapat dikonversi. Jika nilai asli berbasis string, informasi properti budaya default akan digunakan dari [`SignatureSettings.DefaultCulture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/).

```python
def to_decimal(self):
    ...
```

**Returns:** The metadata signature value as Decimal.

## to_decimal {#provider}

Mengonversi nilai tanda tangan metadata ke Decimal.

```python
def to_decimal(self, provider):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| provider | `System.IFormatProvider` | Penyedia format data untuk digunakan dengan operasi konversi data. |

**Returns:** The metadata signature value as Decimal.

### Lihat Juga
* class [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)
