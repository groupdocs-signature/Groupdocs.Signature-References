---
title: "Kelas QrCodeSignOptions"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Mewakili opsi tanda tangan QR-Code."
type: docs
url: /id/python-net/groupdocs.signature.options/qrcodesignoptions/
is_root: false
weight: 480
---


## QrCodeSignOptions class

Mewakili opsi tanda tangan QR-Code.

- Basic usage of creating QR-Code electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/eSign+document+with+QR-code+signature
- Advanced usage of settings of QR-Code electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Sign+document+with+QR-code+signature+-+advanced

Tipe QrCodeSignOptions menampilkan anggota-anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/__init__/) | Menginisialisasi instance baru dari kelas QRCodeSignOptions dengan nilai default. |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/__init__/#text) | Menginisialisasi instance opsi tanda tangan kode QR dengan teks yang ditentukan. |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/__init__/#text-encode_type) | Menginisialisasi instance baru dari kelas QrCodeSignOptions dengan teks. |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [code_text_alignment](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/code_text_alignment/) | Perataan teks dalam gambar kode QR yang dihasilkan, nilai default adalah None. |
| [data](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/data/) | Objek khusus untuk diserialkan ke konten QR-Code. |
| [data_encryption](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/data_encryption/) | Implementasi enkripsi data yang digunakan untuk mengkodekan dan mendekode teks atau data tanda tangan kode QR. |
| [encode_type](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/encode_type/) | Tipe QR-Code. |
| [fore_color](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/fore_color/) | Warna latar depan batang QR code; menggunakan properti ini dapat menyebabkan masalah verifikasi, jadi gunakan dengan hati-hati. |
| [height](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/height/) | Tinggi area tanda tangan pada halaman dokumen dalam satuan ukuran (piksel, persen, atau milimeter; lihat `MeasureType` SizeMeasureType). |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/horizontal_alignment/) | Penjajaran horizontal QR code pada halaman dokumen. |
| [inner_margins](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/inner_margins/) | Ruang antara elemen QR code dan batas gambar hasil. |
| [left](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/left/) | Posisi X kiri area tanda tangan pada halaman dokumen dalam satuan ukuran (piksel, persen, atau milimeter). |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/location_measure_type/) | Tipe ukuran (piksel, persen atau milimeter) untuk properti kiri dan atas. |
| [logo_file_path](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/logo_file_path/) | Nama file gambar logo QR-code. |
| [logo_stream](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/logo_stream/) | Aliran gambar logo QR-code. |
| [margin](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/margin/) | Ruang yang secara default ditentukan antara tepi Gambar dan Dokumen (berfungsi jika penjajaran horizontal atau vertikal ditentukan). |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/margin_measure_type/) | Jenis pengukuran margin (piksel, persen, atau milimeter). |
| [return_content](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/return_content/) | Bendera untuk mengambil konten gambar QR-Code dari tanda tangan yang ditempatkan pada halaman dokumen. |
| [return_content_type](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/return_content_type/) | Tipe file dari konten gambar yang dikembalikan dari tanda tangan QR‑Code ketika properti `return_content` diaktifkan. |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/rotation_angle/) | Sudut rotasi dalam derajat, searah jarum jam. |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/size_measure_type/) | Jenis pengukuran (piksel, persen, atau milimeter) untuk properti Width dan Height. |
| [stretch](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/stretch/) | Mode peregangan pada halaman dokumen. |
| [top](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/top/) | Posisi Y atas area tanda tangan pada halaman dokumen dalam satuan ukuran (piksel, persen, atau milimeter). Satuan didefinisikan oleh properti `LocationMeasureType` dengan tipe `MeasureType`. |
| [transparency](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/transparency/) | Transparansi tanda tangan QR code. Nilainya berkisar antara 0,0 hingga 1,0, dengan default 0. |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/vertical_alignment/) | Perataan vertikal gambar pada halaman dokumen. |
| [width](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/width/) | Lebar area tanda tangan pada halaman dokumen dalam nilai ukuran (piksel, persen, atau milimeter sebagaimana didefinisikan oleh `MeasureType`). |
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
from groupdocs.signature.options import QrCodeSignOptions
from groupdocs.signature.domain import (
    Background, Border, DashStyle, HorizontalAlignment, Padding,
    QrCodeTypes, VerticalAlignment)
from groupdocs.pydrawing import Color

def sign_with_qr_code_signature_advanced():
    with Signature("sample.pdf") as signature:
        # Berikan teks dan tipe QR code ke konstruktor
        options = QrCodeSignOptions("https://www.example.com/verify-document", QrCodeTypes.QR)

        # Letakkan QR code di sudut kanan bawah halaman
        options.width = 120
        options.height = 120
        options.horizontal_alignment = HorizontalAlignment.RIGHT
        options.vertical_alignment = VerticalAlignment.BOTTOM
        options.margin = Padding(right=40, bottom=60)

        # Warna modul, latar belakang, dan batas titik dengan sedikit ruang di dalamnya
        options.fore_color = Color.dark_blue
        background = Background()
        background.color = Color.light_yellow
        options.background = background
        border = Border()
        border.color = Color.dark_blue
        border.dash_style = DashStyle.DOT
        border.weight = 2
        border.visible = True

        signature.sign("signed.pdf", options)
```

### Guides
Panduan tugas yang menggunakan `QrCodeSignOptions`:

* [eSign Document with QR Code Signature](/signature/python-net/guides/esign-document-with-qr-code-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)
* [Generate signatures preview](/signature/python-net/guides/generate-signatures-preview/)

### Lihat Juga
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
