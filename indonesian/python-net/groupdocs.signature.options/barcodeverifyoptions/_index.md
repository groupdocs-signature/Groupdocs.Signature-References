---
title: "Kelas BarcodeVerifyOptions"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Menunjukkan opsi verifikasi Barcode."
type: docs
url: /id/python-net/groupdocs.signature.options/barcodeverifyoptions/
is_root: false
weight: 30
---


## BarcodeVerifyOptions class

Menunjukkan opsi verifikasi Barcode.

Pelajari lebih lanjut
- Basic usage of verification for Barcode electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Verify+Barcode+signatures+in+the+document
- Advanced usage of settings of verification for Barcode electronic signature with GroupDocs.Signature: Advanced usage of eVerification Barcode signatures in a document and additional settings

Tipe BarcodeVerifyOptions menampilkan anggota-anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodeverifyoptions/__init__/) | Menginisialisasi opsi verifikasi default untuk tanda tangan barcode. |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodeverifyoptions/__init__/#text) | Menginisialisasi opsi verifikasi default dengan teks verifikasi. |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodeverifyoptions/__init__/#encode_type) | Menginisialisasi opsi verifikasi default dengan verifikasi tipe barcode. |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodeverifyoptions/__init__/#text-encode_type) | Menginisialisasi opsi verifikasi default dengan verifikasi tipe barcode dan teks. |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [encode_type](/signature/python-net/groupdocs.signature.options/barcodeverifyoptions/encode_type/) | Tipe barcode yang digunakan untuk verifikasi. |
| [all_pages](/signature/python-net/groupdocs.signature.options/verifyoptions/all_pages/) | Bendera yang menunjukkan apakah setiap halaman dokumen harus diverifikasi. Secara default nilainya True. (diturunkan dari [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/verifyoptions/extensions/) | Ekstensi tambahan untuk verifikasi opsi tanda tangan alternatif. (diturunkan dari [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [form_text_field_title](/signature/python-net/groupdocs.signature.options/textverifyoptions/form_text_field_title/) | Judul bidang formulir yang akan diverifikasi. Jika diatur, teks hanya akan ditemukan di bidang formulir teks. (diturunkan dari [`TextVerifyOptions`](/signature/python-net/groupdocs.signature.options/textverifyoptions/)) |
| [form_text_field_type](/signature/python-net/groupdocs.signature.options/textverifyoptions/form_text_field_type/) | Tipe bidang formulir yang akan diverifikasi; jika diatur, teks hanya akan ditemukan di bidang formulir teks. (diturunkan dari [`TextVerifyOptions`](/signature/python-net/groupdocs.signature.options/textverifyoptions/)) |
| [is_valid](/signature/python-net/groupdocs.signature.options/verifyoptions/is_valid/) | Bendera properti valid. (diturunkan dari [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [match_type](/signature/python-net/groupdocs.signature.options/textverifyoptions/match_type/) | Verifikasi tipe kecocokan teks. (diturunkan dari [`TextVerifyOptions`](/signature/python-net/groupdocs.signature.options/textverifyoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/verifyoptions/page_number/) | Nomor halaman dokumen yang akan diverifikasi; jika tidak disetel, semua halaman dokumen diverifikasi untuk kejadian pertama (nilai minimum adalah 1). (diturunkan dari [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/verifyoptions/pages_setup/) | Opsi halaman untuk menentukan halaman yang akan diverifikasi. (diturunkan dari [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/verifyoptions/shape_position/) | Posisi bentuk dalam tata letak dokumen yang digunakan untuk memverifikasi tanda tangan di header/footer. (diturunkan dari [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [signature_id](/signature/python-net/groupdocs.signature.options/textverifyoptions/signature_id/) | ID Tanda Tangan Teks yang akan diverifikasi. Harus lebih besar dari nol; hanya didukung untuk dokumen PDF. (diturunkan dari [`TextVerifyOptions`](/signature/python-net/groupdocs.signature.options/textverifyoptions/)) |
| [signature_implementation](/signature/python-net/groupdocs.signature.options/textverifyoptions/signature_implementation/) | Tipe tanda tangan yang akan diverifikasi. (diturunkan dari [`TextVerifyOptions`](/signature/python-net/groupdocs.signature.options/textverifyoptions/)) |
| [text](/signature/python-net/groupdocs.signature.options/textverifyoptions/text/) | Teks tanda tangan yang akan diverifikasi. (diturunkan dari [`TextVerifyOptions`](/signature/python-net/groupdocs.signature.options/textverifyoptions/)) |

### Contoh

```python
from groupdocs.signature import Signature
from groupdocs.signature.domain import TextMatchType
from groupdocs.signature.options import BarcodeVerifyOptions


def verify_barcode_signatures():
    with Signature("signed.pdf") as signature:
        options = BarcodeVerifyOptions()
        options.all_pages = True
        options.text = "12345"
        options.match_type = TextMatchType.CONTAINS

        result = signature.verify(options)

        if result.is_valid:
            print(f"Document was verified successfully: {len(result.succeeded)} matching barcode signature(s).")
        else:
            print("Document failed verification process.")
```

### Lihat Juga
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
