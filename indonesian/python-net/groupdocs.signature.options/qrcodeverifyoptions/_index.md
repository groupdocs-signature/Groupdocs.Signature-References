---
title: "kelas QrCodeVerifyOptions"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Menyimpan opsi untuk memverifikasi tanda tangan QR-code dokumen."
type: docs
url: /id/python-net/groupdocs.signature.options/qrcodeverifyoptions/
is_root: false
weight: 490
---


## QrCodeVerifyOptions class

Menyimpan opsi untuk memverifikasi tanda tangan QR-code dokumen.

- Basic usage of verification for QR-code electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Verify+QR-code+signatures+in+the+document
- Advanced usage of settings of verification for QR-code electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Verify+QR-code+signatures

Tipe QrCodeVerifyOptions menampilkan anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodeverifyoptions/__init__/) | Menginisialisasi opsi verifikasi untuk tanda tangan QR-Code. |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodeverifyoptions/__init__/#text) | Menginisialisasi opsi verifikasi untuk tanda tangan QR-Code dengan teks QR-code yang ditentukan. |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodeverifyoptions/__init__/#text-encode_type) | Menginisialisasi opsi verifikasi untuk tanda tangan QR-Code dengan teks dan tipe enkode QR-Code untuk diverifikasi. |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [data_encryption](/signature/python-net/groupdocs.signature.options/qrcodeverifyoptions/data_encryption/) | Implementasi [`IDataEncryption`](/signature/python-net/groupdocs.signature.domain.extensions/idataencryption/) yang digunakan untuk mengkodekan dan mendekode properti teks tanda tangan QR-Code. |
| [encode_type](/signature/python-net/groupdocs.signature.options/qrcodeverifyoptions/encode_type/) | Verifikasi tipe QR-code. Properti ini bersifat opsional. |
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
from groupdocs.signature.options import QrCodeVerifyOptions
from groupdocs.signature.domain import TextMatchType

def verify_qr_codes():
    with Signature("signed.pdf") as signature:
        options = QrCodeVerifyOptions()
        options.all_pages = True
        options.text = "John"
        options.match_type = TextMatchType.CONTAINS

        result = signature.verify(options)

        if result.is_valid:
            print(f"Document verified: {len(result.succeeded)} matching QR code signature(s).")
        else:
            print("Document verification failed.")
```

### Lihat Juga
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
