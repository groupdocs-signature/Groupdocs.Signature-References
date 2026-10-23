---
title: "Kelas VerificationResult"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Mewakili sebuah instance yang menyimpan hasil proses verifikasi."
type: docs
url: /id/python-net/groupdocs.signature.domain/verificationresult/
is_root: false
weight: 820
---


## VerificationResult class

Mewakili sebuah instance yang menyimpan hasil proses verifikasi.

Tipe VerificationResult menampilkan anggota-anggota berikut:

### Properti
| Properti | Deskripsi |
| :- | :- |
| [destin_document_size](/signature/python-net/groupdocs.signature.domain/verificationresult/destin_document_size/) | Ukuran dokumen tujuan. Untuk verifikasi variabel ini selalu berisi nol. |
| [failed](/signature/python-net/groupdocs.signature.domain/verificationresult/failed/) | Daftar tanda tangan yang gagal dalam proses verifikasi. |
| [is_valid](/signature/python-net/groupdocs.signature.domain/verificationresult/is_valid/) | Hasil verifikasi; True jika proses verifikasi berhasil, jika tidak False. |
| [processing_time](/signature/python-net/groupdocs.signature.domain/verificationresult/processing_time/) | Waktu eksekusi proses dalam milidetik. |
| [source_document_size](/signature/python-net/groupdocs.signature.domain/verificationresult/source_document_size/) | Ukuran dokumen sumber dalam byte. |
| [succeeded](/signature/python-net/groupdocs.signature.domain/verificationresult/succeeded/) | Daftar tanda tangan yang berhasil diverifikasi [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/). |
| [total_signatures](/signature/python-net/groupdocs.signature.domain/verificationresult/total_signatures/) | Jumlah total tanda tangan yang diproses. |

### Contoh

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextVerifyOptions
from groupdocs.signature.domain import TextMatchType

with Signature("signed.pdf") as signature:
    options = TextVerifyOptions()
    options.text = "John Smith"
    options.match_type = TextMatchType.CONTAINS

    result = signature.verify(options)

    if result.is_valid:
        print(f"Verified: {len(result.succeeded)} matching signature(s).")
    else:
        print("Verification failed.")
```

### Lihat Juga
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
