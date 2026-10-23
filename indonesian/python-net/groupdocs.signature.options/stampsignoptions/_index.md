---
title: "Kelas StampSignOptions"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Mewakili opsi tanda tangan Stamp."
type: docs
url: /id/python-net/groupdocs.signature.options/stampsignoptions/
is_root: false
weight: 570
---


## StampSignOptions class

Mewakili opsi tanda tangan Stamp.

Pelajari lebih lanjut:
- Basic usage of creating Stamp electronic signature by GroupDocs.Signature: How to eSign document with Stamp signature (https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Stamp+signature)
- Advanced usage of settings of Stamp electronic signature with GroupDocs.Signature: Advanced usage to eSign document with Stamp signature and additional settings (https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Stamp+signature+-+advanced)

Tipe StampSignOptions menampilkan anggota-anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/stampsignoptions/__init__/) | Menginisialisasi instance baru kelas StampSignOptions dengan nilai default. |
| [__init__](/signature/python-net/groupdocs.signature.options/stampsignoptions/__init__/#left-top-width-height) | Menginisialisasi instance baru kelas StampSignOptions dengan opsi penyelarasan. |

### Metode
| Metode | Deskripsi |
| :- | :- |
| [dispose](/signature/python-net/groupdocs.signature.options/imagesignoptions/dispose/) | Menghapus sumber daya internal. (diturunkan dari [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |
| [from_base64](/signature/python-net/groupdocs.signature.options/imagesignoptions/from_base64/) | Membuat instance baru ImageSignOptions dengan gambar yang telah ditentukan sebelumnya dari string Base64. (diturunkan dari [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [background](/signature/python-net/groupdocs.signature.options/stampsignoptions/background/) | Latar belakang stempel. |
| [background_color_crop_type](/signature/python-net/groupdocs.signature.options/stampsignoptions/background_color_crop_type/) | Tipe pemotongan warna latar belakang tanda tangan. |
| [background_image_crop_type](/signature/python-net/groupdocs.signature.options/stampsignoptions/background_image_crop_type/) | Tipe pemotongan gambar latar belakang tanda tangan. |
| [height](/signature/python-net/groupdocs.signature.options/stampsignoptions/height/) | Tinggi area tanda tangan pada halaman dokumen dalam satuan ukuran (piksel, persen, atau milimeter). |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/stampsignoptions/horizontal_alignment/) | Perataan horizontal gambar pada halaman dokumen. |
| [inner_lines](/signature/python-net/groupdocs.signature.options/stampsignoptions/inner_lines/) | Daftar garis dalam yang dirender sebagai sekumpulan persegi panjang. |
| [left](/signature/python-net/groupdocs.signature.options/stampsignoptions/left/) | Posisi X kiri area tanda tangan pada halaman dokumen dalam satuan ukuran (piksel, persen, atau milimeter). Lihat `MeasureType` `LocationMeasureType`. |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/stampsignoptions/location_measure_type/) | Tipe ukuran (pixel, persen, atau milimeter) untuk properti kiri dan atas. |
| [margin](/signature/python-net/groupdocs.signature.options/stampsignoptions/margin/) | Ruang yang secara default ditentukan antara gambar dan tepi dokumen (berfungsi jika penyelarasan horizontal atau vertikal ditentukan). |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/stampsignoptions/margin_measure_type/) | Jenis pengukuran margin (piksel, persen, atau milimeter). |
| [outer_lines](/signature/python-net/groupdocs.signature.options/stampsignoptions/outer_lines/) | Daftar garis luar yang dirender sebagai lingkaran konsentris. |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/stampsignoptions/rotation_angle/) | Sudut rotasi searah jarum jam. |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/stampsignoptions/size_measure_type/) | Jenis pengukuran (piksel, persen, atau milimeter) untuk properti Width dan Height. |
| [stamp_type](/signature/python-net/groupdocs.signature.options/stampsignoptions/stamp_type/) | Tipe stempel. Default adalah `Round`. |
| [stretch](/signature/python-net/groupdocs.signature.options/stampsignoptions/stretch/) | Mode peregangan pada halaman dokumen. |
| [top](/signature/python-net/groupdocs.signature.options/stampsignoptions/top/) | Posisi Y atas area tanda tangan pada halaman dokumen dalam satuan ukuran (piksel, persen, atau milimeter). Lihat `MeasureType` `LocationMeasureType`. |
| [transparency](/signature/python-net/groupdocs.signature.options/stampsignoptions/transparency/) | Transparansi tanda tangan stempel. Nilai berkisar dari 0,0 hingga 1,0, dengan default 0. |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/stampsignoptions/vertical_alignment/) | Penyelarasan vertikal stempel pada halaman dokumen. |
| [width](/signature/python-net/groupdocs.signature.options/stampsignoptions/width/) | Lebar area tanda tangan pada halaman dokumen dalam nilai ukuran (piksel, persen, atau milimeter). Satuan ukuran didefinisikan oleh `MeasureType` SizeMeasureType. |
| [all_pages](/signature/python-net/groupdocs.signature.options/signoptions/all_pages/) | Tanda tangan akan ditempatkan pada semua halaman dokumen. (diturunkan dari [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [appearance](/signature/python-net/groupdocs.signature.options/signoptions/appearance/) | Penampilan tanda tangan tambahan. (diturunkan dari [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [border](/signature/python-net/groupdocs.signature.options/imagesignoptions/border/) | Pengaturan batas untuk tanda tangan gambar. (diturunkan dari [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |
| [document_type](/signature/python-net/groupdocs.signature.options/signoptions/document_type/) | Tipe dokumen dari opsi tanda tangan (`DocumentType`). (diturunkan dari [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/signoptions/extensions/) | Ekstensi tanda tangan. (diturunkan dari [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [hash_algorithm](/signature/python-net/groupdocs.signature.options/signoptions/hash_algorithm/) | Algoritma hash yang akan digunakan untuk operasi kriptografi. Didukung secara eksklusif untuk tanda tangan digital dalam file PDF. (diturunkan dari [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [image_file_path](/signature/python-net/groupdocs.signature.options/imagesignoptions/image_file_path/) | Path file gambar tanda tangan, hanya digunakan jika `image_stream` tidak ditentukan. (diturunkan dari [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |
| [image_stream](/signature/python-net/groupdocs.signature.options/imagesignoptions/image_stream/) | Stream gambar tanda tangan. Jika ditentukan, selalu digunakan menggantikan ImageFilePath. (diturunkan dari [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/signoptions/page_number/) | Nomor halaman dokumen untuk penandatanganan. (diturunkan dari [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/signoptions/pages_setup/) | Opsi untuk menentukan halaman yang akan ditandatangani. (diturunkan dari [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [rectangle](/signature/python-net/groupdocs.signature.options/imagesignoptions/rectangle/) | Persegi panjang area untuk menempatkan gambar pada dokumen. (diturunkan dari [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/imagesignoptions/shape_position/) | Posisi bentuk menentukan di mana bentuk harus ditampilkan dalam tata letak dokumen. Hanya tersedia untuk dokumen Word. (diturunkan dari [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |
| [signature_type](/signature/python-net/groupdocs.signature.options/signoptions/signature_type/) | Tipe tanda tangan (`SignatureType`). (diturunkan dari [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [zorder](/signature/python-net/groupdocs.signature.options/signoptions/zorder/) | Posisi urutan Z dari tanda tangan teks, yang menentukan urutan tampilan tanda tangan yang tumpang tindih. (diturunkan dari [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |

### Contoh

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import StampSignOptions

with Signature("sample.docx") as signature:
    options = StampSignOptions()
    options.left = 380
    options.top = 520
    options.width = 160
    options.height = 160
    # konfigurasikan opsi stempel tambahan sesuai kebutuhan
    signature.sign(options)
```

### Lihat Juga
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
