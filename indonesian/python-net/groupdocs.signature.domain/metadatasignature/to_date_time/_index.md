---
title: "metode to_date_time"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Mengonversi nilai tanda tangan metadata ke datetime."
type: docs
url: /id/python-net/groupdocs.signature.domain/metadatasignature/to_date_time/
is_root: false
weight: 1090
---


## to_date_time

Mengonversi nilai tanda tangan metadata ke datetime.

Jika nilai metadata tidak dapat dikonversi, sebuah pengecualian akan dilempar. Ketika nilai asli berbasis string, budaya default dari [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/) digunakan untuk konversi.

```python
def to_date_time(self):
    ...
```

**Returns:** datetime: The metadata signature value as a datetime.

### Contoh

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSearchOptions

with Signature("signed.pdf") as signature:
    result = signature.search([MetadataSearchOptions()])
    for metadata in result.signatures:
        try:
            dt = metadata.to_date_time()
            print(f"{metadata.name} as datetime: {dt}")
        except Exception as e:
            print(f"Could not convert {metadata.name} to datetime: {e}")
```

## to_date_time {#provider}

Mengonversi nilai tanda tangan metadata ke datetime.

```python
def to_date_time(self, provider):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| provider | `System.IFormatProvider` | Penyedia format data untuk digunakan dengan operasi konversi data. |

**Returns:** datetime.datetime: The metadata signature value as a datetime.

Melempar pengecualian jika nilai metadata tidak dapat dikonversi.

### Lihat Juga
* class [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)
