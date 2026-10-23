---
title: "metode to_date_time"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Mengonversi nilai signature metadata menjadi datetime.datetime."
type: docs
url: /id/python-net/groupdocs.signature.domain/imagemetadatasignature/to_date_time/
is_root: false
weight: 1070
---


## to_date_time

Mengonversi nilai signature metadata menjadi `datetime.datetime`.

Melemparkan pengecualian jika nilai metadata tidak dapat dikonversi. Jika nilai asli berbasis string, budaya default dari [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/) digunakan.

```python
def to_date_time(self):
    ...
```

**Returns:** datetime.datetime: The metadata signature value as a `datetime.datetime`.

## to_date_time {#provider}

Mengonversi nilai signature metadata menjadi `datetime`.

Melempar pengecualian jika nilai metadata tidak dapat dikonversi.

```python
def to_date_time(self, provider):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| provider | `System.IFormatProvider` | Penyedia format data untuk digunakan dengan operasi konversi data. |

**Returns:** datetime: The metadata signature value as a `datetime`.

### Lihat Juga
* class [`ImageMetadataSignature`](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/)
