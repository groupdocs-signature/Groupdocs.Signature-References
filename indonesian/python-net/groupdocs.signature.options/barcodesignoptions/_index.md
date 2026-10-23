---
title: "Kelas BarcodeSignOptions"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Menunjukkan opsi tanda tangan barcode."
type: docs
url: /id/python-net/groupdocs.signature.options/barcodesignoptions/
is_root: false
weight: 20
---


## BarcodeSignOptions class

Menunjukkan opsi tanda tangan barcode.

Pelajari lebih lanjut

- Basic usage of creating Barcode electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Barcode+signature
- Advanced usage of settings of Barcode electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Barcode+signature+and+additional+settings

Tipe BarcodeSignOptions menampilkan anggota-anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodesignoptions/__init__/) | Menginisialisasi instance baru dari kelas BarcodeSignOptions dengan nilai default. |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodesignoptions/__init__/#text) | Menginisialisasi instance baru dari kelas BarcodeSignOptions dengan teks. |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodesignoptions/__init__/#text-encode_type) | Menginisialisasi instance baru dari kelas BarcodeSignOptions dengan teks. |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [code_text_alignment](/signature/python-net/groupdocs.signature.options/barcodesignoptions/code_text_alignment/) | Penjajaran teks dalam gambar barcode yang dihasilkan. Nilai default adalah None. |
| [encode_type](/signature/python-net/groupdocs.signature.options/barcodesignoptions/encode_type/) | Tipe barcode. |
| [fore_color](/signature/python-net/groupdocs.signature.options/barcodesignoptions/fore_color/) | Warna latar depan bar barcode; menggunakannya dapat menyebabkan masalah verifikasi, jadi gunakan dengan hati-hati. |
| [height](/signature/python-net/groupdocs.signature.options/barcodesignoptions/height/) | Tinggi area tanda tangan pada halaman dokumen dalam satuan ukuran (piksel, persen, atau milimeter). Lihat `MeasureType` untuk tipe ukuran. |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/barcodesignoptions/horizontal_alignment/) | Perataan horizontal gambar pada halaman dokumen. |
| [inner_margins](/signature/python-net/groupdocs.signature.options/barcodesignoptions/inner_margins/) | Jarak antara elemen barcode dan batas gambar hasil. |
| [left](/signature/python-net/groupdocs.signature.options/barcodesignoptions/left/) | Posisi X kiri area tanda tangan pada halaman dokumen, dinyatakan dalam satuan ukuran (piksel, persen, atau milimeter). Lihat `MeasureType`. |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/barcodesignoptions/location_measure_type/) | Tipe ukuran (piksel, persen atau milimeter) untuk properti kiri dan atas. |
| [margin](/signature/python-net/groupdocs.signature.options/barcodesignoptions/margin/) | Ruang yang secara default ditentukan antara gambar dan tepi dokumen (berlaku ketika perataan horizontal atau vertikal diatur). |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/barcodesignoptions/margin_measure_type/) | Jenis pengukuran margin (piksel, persen, atau milimeter). |
| [return_content](/signature/python-net/groupdocs.signature.options/barcodesignoptions/return_content/) | Bendera yang menunjukkan apakah akan mengambil konten gambar barcode dari tanda tangan yang ditempatkan pada halaman dokumen. |
| [return_content_type](/signature/python-net/groupdocs.signature.options/barcodesignoptions/return_content_type/) | Tipe file dari konten gambar yang dikembalikan dari tanda tangan Barcode ketika properti `return_content` diaktifkan. |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/barcodesignoptions/rotation_angle/) | Sudut rotasi searah jarum jam. |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/barcodesignoptions/size_measure_type/) | Jenis pengukuran (piksel, persen, atau milimeter) untuk properti Width dan Height. |
| [stretch](/signature/python-net/groupdocs.signature.options/barcodesignoptions/stretch/) | Mode peregangan pada halaman dokumen. |
| [top](/signature/python-net/groupdocs.signature.options/barcodesignoptions/top/) | Posisi Y atas area tanda tangan pada halaman dokumen dalam satuan ukuran (piksel, persen, atau milimeter). Lihat `MeasureType` LocationMeasureType. |
| [transparency](/signature/python-net/groupdocs.signature.options/barcodesignoptions/transparency/) | Transparansi tanda tangan barcode, berkisar dari 0.0 (sepenuhnya buram) hingga 1.0 (sepenuhnya transparan); default adalah 0. |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/barcodesignoptions/vertical_alignment/) | Penjajaran vertikal gambar barcode pada halaman dokumen. |
| [width](/signature/python-net/groupdocs.signature.options/barcodesignoptions/width/) | Lebar area tanda tangan pada halaman dokumen dalam nilai ukuran (piksel, persen, atau milimeter) sebagaimana didefinisikan oleh `MeasureType`. |
| [all_pages](/signature/python-net/groupdocs.signature.options/signoptions/all_pages/) | Tanda tangan akan ditempatkan pada semua halaman dokumen. (diturunkan dari [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [appearance](/signature/python-net/groupdocs.signature.options/signoptions/appearance/) | Penampilan tanda tangan tambahan. (diturunkan dari [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [background](/signature/python-net/groupdocs.signature.options/textsignoptions/background/) | Pengaturan latar belakang tanda tangan. (diturunkan dari [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [border](/signature/python-net/groupdocs.signature.options/textsignoptions/border/) | Pengaturan batas. (diturunkan dari [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [document_type](/signature/python-net/groupdocs.signature.options/signoptions/document_type/) | Tipe dokumen dari opsi tanda tangan (`DocumentType`). (diturunkan dari [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/signoptions/extensions/) | Ekstensi tanda tangan. (diturunkan dari [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [font](/signature/python-net/groupdocs.signature.options/textsignoptions/font/) | Font tanda tangan. (diturunkan dari [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [form_text_field_title](/signature/python-net/groupdocs.signature.options/textsignoptions/form_text_field_title/) | Judul bidang formulir teks untuk menempatkan tanda tangan teks. Hanya dapat digunakan ketika `signature_implementation` disetel ke `TextSignatureImplementation.FORM_FIELD`. (diturunkan dari [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [form_text_field_type](/signature/python-net/groupdocs.signature.options/textsignoptions/form_text_field_type/) | Tipe bidang formulir untuk menempatkan tanda tangan teks. Properti ini hanya berlaku ketika `signature_implementation` disetel ke `TextSignatureImplementation.FORM_FIELD` (misalnya, TextToFormField). Nilai default adalah `FormTextFieldType.ALL_TEXT_TYPES`. (diturunkan dari [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [hash_algorithm](/signature/python-net/groupdocs.signature.options/signoptions/hash_algorithm/) | Algoritma hash yang akan digunakan untuk operasi kriptografi. Didukung secara eksklusif untuk tanda tangan digital dalam file PDF. (diturunkan dari [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [native](/signature/python-net/groupdocs.signature.options/textsignoptions/native/) | Atribut native. (diturunkan dari [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/signoptions/page_number/) | Nomor halaman dokumen untuk penandatanganan. (diturunkan dari [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/signoptions/pages_setup/) | Opsi untuk menentukan halaman yang akan ditandatangani. (diturunkan dari [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/textsignoptions/shape_position/) | Posisi bentuk menentukan di mana bentuk harus ditampilkan dalam tata letak dokumen. Hanya tersedia untuk dokumen Word. (diturunkan dari [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [shape_type](/signature/python-net/groupdocs.signature.options/textsignoptions/shape_type/) | Tipe bentuk untuk menempatkan teks. (diturunkan dari [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [signature_id](/signature/python-net/groupdocs.signature.options/textsignoptions/signature_id/) | ID unik tanda tangan, dapat digunakan dalam opsi verifikasi dan hanya didukung untuk dokumen PDF. (diturunkan dari [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [signature_implementation](/signature/python-net/groupdocs.signature.options/textsignoptions/signature_implementation/) | Tipe implementasi tanda tangan teks. (diturunkan dari [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [signature_type](/signature/python-net/groupdocs.signature.options/signoptions/signature_type/) | Tipe tanda tangan (`SignatureType`). (diturunkan dari [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [text](/signature/python-net/groupdocs.signature.options/textsignoptions/text/) | Teks tanda tangan. (diturunkan dari [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [text_horizontal_alignment](/signature/python-net/groupdocs.signature.options/textsignoptions/text_horizontal_alignment/) | Perataan horizontal teks di dalam tanda tangan, hanya didukung untuk implementasi tanda tangan Gambar dan Anotasi (lihat properti `TextSignatureImplementation` SignatureImplementation). (diturunkan dari [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [text_vertical_alignment](/signature/python-net/groupdocs.signature.options/textsignoptions/text_vertical_alignment/) | Perataan vertikal teks di dalam tanda tangan. (diturunkan dari [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [zorder](/signature/python-net/groupdocs.signature.options/signoptions/zorder/) | Posisi urutan Z dari tanda tangan teks, yang menentukan urutan tampilan tanda tangan yang tumpang tindih. (diturunkan dari [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |

### Contoh

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import BarcodeSignOptions
from groupdocs.signature.domain import (
    Background, BarcodeTypes, Border, CodeTextAlignment,
    HorizontalAlignment, Padding, VerticalAlignment)
from groupdocs.pydrawing import Color

def sign_with_barcode():
    with Signature("sample.pdf") as signature:
        options = BarcodeSignOptions("JohnSmith", BarcodeTypes.CODE128)
        options.width = 220
        options.height = 80
        options.horizontal_alignment = HorizontalAlignment.RIGHT
        options.vertical_alignment = VerticalAlignment.BOTTOM
        options.margin = Padding(right=40, bottom=60)
        options.fore_color = Color.dark_blue
        options.code_text_alignment = CodeTextAlignment.BELOW
        options.inner_margins = Padding(5)

        background = Background()
        background.color = Color.light_yellow
        options.background = background

        border = Border()
        options.border = border

        signature.sign("signed.pdf", options)
```

### Guides
Panduan tugas yang menggunakan `BarcodeSignOptions`:

* [eSign Document with Barcode Signature](/signature/python-net/guides/esign-document-with-barcode-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)
* [Generate signatures preview](/signature/python-net/guides/generate-signatures-preview/)

### Lihat Juga
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
