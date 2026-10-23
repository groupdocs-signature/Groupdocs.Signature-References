---
title: "Kelas FormFieldSignOptions"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Menunjukkan opsi tanda tangan FormField untuk dokumen PDF."
type: docs
url: /id/python-net/groupdocs.signature.options/formfieldsignoptions/
is_root: false
weight: 180
---


## FormFieldSignOptions class

Menunjukkan opsi tanda tangan FormField untuk dokumen PDF.

Menyediakan opsi untuk membuat atau memperbarui tanda tangan bidang formulir dalam file PDF.

- Basic usage of creating FormField electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Form+Field+signature
- Advanced usage of settings of FormField electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Form+Field+signature+-+advanced

Tipe FormFieldSignOptions menampilkan anggota-anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/__init__/) | Menginisialisasi instance baru dari kelas PdfFormFieldSignOptions dengan nilai default. |
| [__init__](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/__init__/#signature) | Menginisialisasi instance baru dari kelas PdfFormFieldSignOptions dengan tanda tangan FormField. |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [height](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/height/) | Tinggi area tanda tangan pada halaman dokumen dalam satuan ukuran (piksel, persen, atau milimeter; lihat `MeasureType` SizeMeasureType). |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/horizontal_alignment/) | Perataan horizontal gambar pada halaman dokumen. |
| [left](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/left/) | Posisi X kiri area tanda tangan pada halaman dokumen dalam satuan ukuran (piksel, persen, atau milimeter). |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/location_measure_type/) | Jenis ukuran (piksel, persen, atau milimeter) untuk properti Left dan Top. |
| [margin](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/margin/) | Spasi default antara gambar dan tepi dokumen (berlaku ketika perataan horizontal atau vertikal disetel). |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/margin_measure_type/) | Jenis pengukuran margin (piksel, persen, atau milimeter). |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/rotation_angle/) | Sudut rotasi, diukur searah jarum jam. |
| [signature](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/signature/) | FormField dari tanda tangan. |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/size_measure_type/) | Jenis pengukuran (piksel, persen, atau milimeter) untuk properti Width dan Height. |
| [stretch](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/stretch/) | Mode peregangan pada halaman dokumen. |
| [top](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/top/) | Posisi Y atas area tanda tangan pada halaman dokumen dalam satuan ukuran (piksel, persentase, atau milimeter). Lihat `MeasureType` untuk tipe ukuran lokasi. |
| [transparency](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/transparency/) | Transparansi tanda tangan bidang formulir. Nilai berkisar antara 0,0 hingga 1,0, dengan default 0. |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/vertical_alignment/) | Perataan vertikal gambar pada halaman dokumen. |
| [width](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/width/) | Lebar area tanda tangan pada halaman dokumen dalam nilai ukuran (piksel, persen, atau milimeter; lihat `MeasureType` SizeMeasureType). |
| [all_pages](/signature/python-net/groupdocs.signature.options/signoptions/all_pages/) | Tanda tangan akan ditempatkan pada semua halaman dokumen. (diturunkan dari [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [appearance](/signature/python-net/groupdocs.signature.options/signoptions/appearance/) | Penampilan tanda tangan tambahan. (diturunkan dari [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [background](/signature/python-net/groupdocs.signature.options/textsignoptions/background/) | Pengaturan latar belakang tanda tangan. (diturunkan dari [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [border](/signature/python-net/groupdocs.signature.options/textsignoptions/border/) | Pengaturan batas. (diturunkan dari [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [document_type](/signature/python-net/groupdocs.signature.options/signoptions/document_type/) | Tipe dokumen dari opsi tanda tangan (`DocumentType`). (diturunkan dari [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/signoptions/extensions/) | Ekstensi tanda tangan. (diturunkan dari [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [font](/signature/python-net/groupdocs.signature.options/textsignoptions/font/) | Font tanda tangan. (diturunkan dari [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [fore_color](/signature/python-net/groupdocs.signature.options/textsignoptions/fore_color/) | Warna depan tanda tangan. (diturunkan dari [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
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
from groupdocs.signature.options import FormFieldSignOptions
from groupdocs.signature.domain import TextFormFieldSignature

def sign_with_form_field_signature():
    with Signature("sample.pdf") as signature:
        text_field = TextFormFieldSignature("FieldText", "Value1")
        options = FormFieldSignOptions(text_field)
        options.left = 100
        options.top = 400
        options.width = 200
        options.height = 20

        result = signature.sign("signed_form_field.pdf", options)
        for field in result.succeeded:
            print(f"Added form field '{field.name}' with value '{field.value}'")
```

### Lihat Juga
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
