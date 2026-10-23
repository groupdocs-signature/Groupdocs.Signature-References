---
title: "Kelas TextVerifyOptions"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Menyimpan opsi untuk memverifikasi tanda tangan Teks dokumen."
type: docs
url: /id/python-net/groupdocs.signature.options/textverifyoptions/
is_root: false
weight: 600
---


## TextVerifyOptions class

Menyimpan opsi untuk memverifikasi tanda tangan Teks dokumen.

Pelajari lebih lanjut:
- Basic usage of verification for Barcode electronic signature by GroupDocs.Signature: [How to eVerification Barcode signatures in a document](https://docs.groupdocs.com/display/signaturenet/Verify+Text+signatures+in+the+document)
- Advanced usage of settings of verification for Barcode electronic signature with GroupDocs.Signature: [Advanced usage of eVerification Barcode signatures in a document and additional settings](https://docs.groupdocs.com/display/signaturenet/Verify+Text+signatures)

Tipe TextVerifyOptions menampilkan anggota-anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/textverifyoptions/__init__/) | Menginisialisasi instance baru dari TextVerifyOptions dengan nilai default. |
| [__init__](/signature/python-net/groupdocs.signature.options/textverifyoptions/__init__/#text) | Menginisialisasi instance baru dari TextVerifyOptions dengan teks verifikasi. |
| [__init__](/signature/python-net/groupdocs.signature.options/textverifyoptions/__init__/#text-implementation) | Menginisialisasi instance baru TextVerifyOptions dengan teks yang akan diverifikasi dan tipe implementasi tanda tangan. |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [form_text_field_title](/signature/python-net/groupdocs.signature.options/textverifyoptions/form_text_field_title/) | Judul bidang formulir yang akan diverifikasi. Jika disetel, teks hanya akan ditemukan dalam bidang formulir teks. |
| [form_text_field_type](/signature/python-net/groupdocs.signature.options/textverifyoptions/form_text_field_type/) | Jenis bidang formulir yang akan diverifikasi; jika diatur, teks hanya akan ditemukan dalam bidang formulir teks. |
| [match_type](/signature/python-net/groupdocs.signature.options/textverifyoptions/match_type/) | Verifikasi jenis kecocokan teks. |
| [signature_id](/signature/python-net/groupdocs.signature.options/textverifyoptions/signature_id/) | ID Tanda Tangan Teks yang akan diverifikasi. Harus lebih besar dari nol; hanya didukung untuk dokumen PDF. |
| [signature_implementation](/signature/python-net/groupdocs.signature.options/textverifyoptions/signature_implementation/) | Jenis tanda tangan yang akan diverifikasi. |
| [text](/signature/python-net/groupdocs.signature.options/textverifyoptions/text/) | Teks tanda tangan yang akan diverifikasi. |
| [all_pages](/signature/python-net/groupdocs.signature.options/verifyoptions/all_pages/) | Bendera yang menunjukkan apakah setiap halaman dokumen harus diverifikasi. Secara default nilainya True. (diturunkan dari [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/verifyoptions/extensions/) | Ekstensi tambahan untuk verifikasi opsi tanda tangan alternatif. (diturunkan dari [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [is_valid](/signature/python-net/groupdocs.signature.options/verifyoptions/is_valid/) | Bendera properti valid. (diturunkan dari [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/verifyoptions/page_number/) | Nomor halaman dokumen yang akan diverifikasi; jika tidak disetel, semua halaman dokumen diverifikasi untuk kejadian pertama (nilai minimum adalah 1). (diturunkan dari [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/verifyoptions/pages_setup/) | Opsi halaman untuk menentukan halaman yang akan diverifikasi. (diturunkan dari [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/verifyoptions/shape_position/) | Posisi bentuk dalam tata letak dokumen yang digunakan untuk memverifikasi tanda tangan di header/footer. (diturunkan dari [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |

### Contoh

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextVerifyOptions

def verify_text_signature():
    with Signature("signed.pdf") as signature:
        options = TextVerifyOptions("John Smith")
        result = signature.verify(options)
        print(f"Document is signed by John Smith: {result.is_valid}")

if __name__ == "__main__":
    verify_text_signature()
```

### Guides
Panduan tugas yang menggunakan `TextVerifyOptions`:

* [Quick Start Guide](/signature/python-net/guides/quick-start-guide/)

### Lihat Juga
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
