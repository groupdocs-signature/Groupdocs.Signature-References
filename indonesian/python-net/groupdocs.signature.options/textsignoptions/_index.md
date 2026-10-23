---
title: "Kelas TextSignOptions"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Mewakili opsi tanda tangan Teks."
type: docs
url: /id/python-net/groupdocs.signature.options/textsignoptions/
is_root: false
weight: 590
---


## TextSignOptions class

Mewakili opsi tanda tangan Teks.

Pelajari lebih lanjut

- Basic usage of creating Text electronic signature by GroupDocs.Signature: [How to eSign document with Text signature](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Text+signature)
- Advanced usage of settings of Text electronic signature with GroupDocs.Signature: [Advanced usage to eSign document with Text signature and additional settings](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Text+signature+-+advanced)

Tipe TextSignOptions menampilkan anggota-anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/textsignoptions/__init__/) | Menginisialisasi instance baru dari kelas TextSignOptions dengan nilai default. |
| [__init__](/signature/python-net/groupdocs.signature.options/textsignoptions/__init__/#text) | Menginisialisasi instance baru dari kelas TextSignOptions dengan teks. |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [background](/signature/python-net/groupdocs.signature.options/textsignoptions/background/) | Pengaturan latar belakang tanda tangan. |
| [border](/signature/python-net/groupdocs.signature.options/textsignoptions/border/) | Pengaturan batas. |
| [font](/signature/python-net/groupdocs.signature.options/textsignoptions/font/) | Font tanda tangan. |
| [fore_color](/signature/python-net/groupdocs.signature.options/textsignoptions/fore_color/) | Warna depan tanda tangan. |
| [form_text_field_title](/signature/python-net/groupdocs.signature.options/textsignoptions/form_text_field_title/) | Judul bidang formulir teks untuk menempatkan tanda tangan teks. Hanya dapat digunakan ketika `signature_implementation` diatur ke `TextSignatureImplementation.FORM_FIELD`. |
| [form_text_field_type](/signature/python-net/groupdocs.signature.options/textsignoptions/form_text_field_type/) | The jenis bidang formulir untuk menempatkan tanda tangan teks. Properti ini hanya berlaku ketika `signature_implementation` diatur ke `TextSignatureImplementation.FORM_FIELD` (yaitu, TextToFormField). Nilai default adalah `FormTextFieldType.ALL_TEXT_TYPES`. |
| [height](/signature/python-net/groupdocs.signature.options/textsignoptions/height/) | Tinggi tanda tangan pada halaman dokumen dalam nilai ukuran (piksel, persen, atau milimeter). Satuan ditentukan oleh properti `SizeMeasureType`. |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/textsignoptions/horizontal_alignment/) | Penjajaran horizontal tanda tangan pada halaman dokumen. |
| [left](/signature/python-net/groupdocs.signature.options/textsignoptions/left/) | Posisi X kiri tanda tangan pada halaman dokumen dalam nilai ukuran (piksel, persen, atau milimeter sebagaimana didefinisikan oleh properti `MeasureType` LocationMeasureType). Berfungsi jika perataan horizontal tidak ditentukan. |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/textsignoptions/location_measure_type/) | Jenis ukuran (piksel, persen, atau milimeter) untuk properti `left` dan `top`. |
| [margin](/signature/python-net/groupdocs.signature.options/textsignoptions/margin/) | Jarak antara tanda tangan dan tepi dokumen. Hanya berlaku ketika perataan horizontal atau vertikal ditentukan. |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/textsignoptions/margin_measure_type/) | Tipe ukuran (piksel, persen atau milimeter) untuk margin. |
| [native](/signature/python-net/groupdocs.signature.options/textsignoptions/native/) | Atribut native. |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/textsignoptions/rotation_angle/) | Sudut rotasi tanda tangan pada halaman dokumen (searah jarum jam). |
| [shape_position](/signature/python-net/groupdocs.signature.options/textsignoptions/shape_position/) | Posisi bentuk menentukan di mana bentuk harus ditampilkan dalam tata letak dokumen. Hanya tersedia untuk dokumen Word. |
| [shape_type](/signature/python-net/groupdocs.signature.options/textsignoptions/shape_type/) | Jenis bentuk untuk menempatkan teks. |
| [signature_id](/signature/python-net/groupdocs.signature.options/textsignoptions/signature_id/) | ID unik tanda tangan, dapat digunakan dalam opsi verifikasi dan hanya didukung untuk dokumen PDF. |
| [signature_implementation](/signature/python-net/groupdocs.signature.options/textsignoptions/signature_implementation/) | Jenis implementasi tanda tangan teks. |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/textsignoptions/size_measure_type/) | Jenis pengukuran (piksel, persen, atau milimeter) untuk properti Width dan Height. |
| [stretch](/signature/python-net/groupdocs.signature.options/textsignoptions/stretch/) | Mode peregangan pada halaman dokumen. |
| [text](/signature/python-net/groupdocs.signature.options/textsignoptions/text/) | Teks tanda tangan. |
| [text_horizontal_alignment](/signature/python-net/groupdocs.signature.options/textsignoptions/text_horizontal_alignment/) | Perataan horizontal teks di dalam tanda tangan, hanya didukung untuk implementasi tanda tangan Image dan Annotation (lihat properti `TextSignatureImplementation` SignatureImplementation). |
| [text_vertical_alignment](/signature/python-net/groupdocs.signature.options/textsignoptions/text_vertical_alignment/) | Penjajaran vertikal teks di dalam tanda tangan. |
| [top](/signature/python-net/groupdocs.signature.options/textsignoptions/top/) | Posisi Y atas tanda tangan pada halaman dokumen, dinyatakan dalam satuan ukuran (piksel, persen, atau milimeter). |
| [transparency](/signature/python-net/groupdocs.signature.options/textsignoptions/transparency/) | Transparansi tanda tangan, nilai float antara 0.0 (opaque) dan 1.0 (clear). Default adalah 0.0 (opaque). |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/textsignoptions/vertical_alignment/) | Penjajaran vertikal tanda tangan pada halaman dokumen. |
| [width](/signature/python-net/groupdocs.signature.options/textsignoptions/width/) | Lebar tanda tangan pada halaman dokumen dalam nilai ukuran (piksel, persen, atau milimeter; lihat properti `MeasureType` `SizeMeasureType`). |
| [all_pages](/signature/python-net/groupdocs.signature.options/signoptions/all_pages/) | Tanda tangan akan ditempatkan pada semua halaman dokumen. (diturunkan dari [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [appearance](/signature/python-net/groupdocs.signature.options/signoptions/appearance/) | Penampilan tanda tangan tambahan. (diturunkan dari [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [document_type](/signature/python-net/groupdocs.signature.options/signoptions/document_type/) | Tipe dokumen dari opsi tanda tangan (`DocumentType`). (diturunkan dari [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/signoptions/extensions/) | Ekstensi tanda tangan. (diturunkan dari [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [hash_algorithm](/signature/python-net/groupdocs.signature.options/signoptions/hash_algorithm/) | Algoritma hash yang akan digunakan untuk operasi kriptografi. Didukung secara eksklusif untuk tanda tangan digital dalam file PDF. (diturunkan dari [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/signoptions/page_number/) | Nomor halaman dokumen untuk penandatanganan. (diturunkan dari [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/signoptions/pages_setup/) | Opsi untuk menentukan halaman yang akan ditandatangani. (diturunkan dari [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [signature_type](/signature/python-net/groupdocs.signature.options/signoptions/signature_type/) | Tipe tanda tangan (`SignatureType`). (diturunkan dari [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [zorder](/signature/python-net/groupdocs.signature.options/signoptions/zorder/) | Posisi urutan Z dari tanda tangan teks, yang menentukan urutan tampilan tanda tangan yang tumpang tindih. (diturunkan dari [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |

### Contoh

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

def sign_pdf_with_text_signature():
    with Signature("sample.pdf") as signature:
        options = TextSignOptions("John Smith")
        options.left = 100
        options.top = 100
        result = signature.sign("signed_sample.pdf", options)
        print(f"Signatures added: {len(result.succeeded)}")
```

### Guides
Panduan tugas yang menggunakan `TextSignOptions`:

* [Quick Start Guide](/signature/python-net/guides/quick-start-guide/)
* [eSign Document with Text Signature](/signature/python-net/guides/esign-document-with-text-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)
* [Generate signatures preview](/signature/python-net/guides/generate-signatures-preview/)

### Lihat Juga
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
