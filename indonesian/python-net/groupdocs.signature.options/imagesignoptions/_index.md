---
title: "kelas ImageSignOptions"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Mewakili opsi tanda tangan Gambar."
type: docs
url: /id/python-net/groupdocs.signature.options/imagesignoptions/
is_root: false
weight: 250
---


## ImageSignOptions class

Mewakili opsi tanda tangan Gambar.

Pelajari lebih lanjut:
- Basic usage of creating Image electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Image+signature
- Advanced usage of settings of Image electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Image+signature+-+advanced

Tipe ImageSignOptions menampilkan anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/imagesignoptions/__init__/) | Menginisialisasi instance baru dari kelas ImageSignOptions dengan nilai default. |
| [__init__](/signature/python-net/groupdocs.signature.options/imagesignoptions/__init__/#image_file_path) | Menginisialisasi ImageSignOptions dengan file gambar. |
| [__init__](/signature/python-net/groupdocs.signature.options/imagesignoptions/__init__/#image_stream) | Menginisialisasi instance baru ImageSignOptions dengan aliran gambar. |

### Metode
| Metode | Deskripsi |
| :- | :- |
| [dispose](/signature/python-net/groupdocs.signature.options/imagesignoptions/dispose/) | Membersihkan sumber daya internal. |
| [from_base64](/signature/python-net/groupdocs.signature.options/imagesignoptions/from_base64/#base_64_content) | Membuat instance baru ImageSignOptions dengan gambar yang telah ditentukan dari string Base64. |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [border](/signature/python-net/groupdocs.signature.options/imagesignoptions/border/) | Pengaturan batas untuk tanda tangan gambar. |
| [height](/signature/python-net/groupdocs.signature.options/imagesignoptions/height/) | Tinggi tanda tangan pada halaman dokumen dalam nilai ukuran (piksel, persen, atau milimeter; lihat `MeasureType` SizeMeasureType). |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/imagesignoptions/horizontal_alignment/) | Penjajaran horizontal tanda tangan pada halaman dokumen. |
| [image_file_path](/signature/python-net/groupdocs.signature.options/imagesignoptions/image_file_path/) | Path file gambar tanda tangan, hanya digunakan jika `image_stream` tidak ditentukan. |
| [image_stream](/signature/python-net/groupdocs.signature.options/imagesignoptions/image_stream/) | Aliran gambar tanda tangan. Jika ditentukan, selalu digunakan menggantikan ImageFilePath. |
| [left](/signature/python-net/groupdocs.signature.options/imagesignoptions/left/) | Posisi X kiri tanda tangan pada halaman dokumen dalam nilai ukuran (piksel, persen, atau milimeter). Berfungsi jika penjajaran horizontal tidak ditentukan. Lihat `MeasureType` untuk tipe ukuran lokasi. |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/imagesignoptions/location_measure_type/) | Tipe ukuran (piksel, persen atau milimeter) untuk properti kiri dan atas. |
| [margin](/signature/python-net/groupdocs.signature.options/imagesignoptions/margin/) | Ruang antara tanda tangan dan tepi dokumen. Hanya berfungsi jika penjajaran horizontal atau vertikal ditentukan. |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/imagesignoptions/margin_measure_type/) | Tipe ukuran (piksel, persen atau milimeter) untuk margin. |
| [rectangle](/signature/python-net/groupdocs.signature.options/imagesignoptions/rectangle/) | Persegi panjang area untuk menempatkan gambar pada dokumen. |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/imagesignoptions/rotation_angle/) | Sudut rotasi tanda tangan pada halaman dokumen (searah jarum jam). |
| [shape_position](/signature/python-net/groupdocs.signature.options/imagesignoptions/shape_position/) | Posisi bentuk menentukan di mana bentuk harus ditampilkan dalam tata letak dokumen. Hanya tersedia untuk dokumen Word. |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/imagesignoptions/size_measure_type/) | Jenis pengukuran (piksel, persen, atau milimeter) untuk properti Width dan Height. |
| [stretch](/signature/python-net/groupdocs.signature.options/imagesignoptions/stretch/) | Mode peregangan pada halaman dokumen. |
| [top](/signature/python-net/groupdocs.signature.options/imagesignoptions/top/) | Posisi Y atas tanda tangan pada halaman dokumen dalam nilai ukuran (piksel, persen, atau milimeter) sebagaimana didefinisikan oleh `MeasureType` LocationMeasureType. Berfungsi jika penjajaran vertikal tidak ditentukan. |
| [transparency](/signature/python-net/groupdocs.signature.options/imagesignoptions/transparency/) | Transparansi tanda tangan, berkisar dari 0,0 (opak) hingga 1,0 (transparan), default 0 (opak). |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/imagesignoptions/vertical_alignment/) | Penjajaran vertikal tanda tangan pada halaman dokumen. |
| [width](/signature/python-net/groupdocs.signature.options/imagesignoptions/width/) | Lebar tanda tangan pada halaman dokumen dalam nilai ukuran (piksel, persen, atau milimeter `MeasureType` tipe ukuran ukuran). |
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
from groupdocs.signature.options import ImageSignOptions

def sign_with_image_signature():
    with Signature("sample.pdf") as signature:
        # Buat opsi tanda tangan gambar dengan file gambar
        options = ImageSignOptions("signature.jpg")
        # Atur posisi dan ukuran tanda tangan
        options.left = 100
        options.top = 400
        options.width = 120
        options.height = 100

        result = signature.sign("signed_image.pdf", options)
        print(f"Signed with {len(result.succeeded)} image signature(s)")
```

### Guides
Panduan tugas yang menggunakan `ImageSignOptions`:

* [eSign Document with Image Signature](/signature/python-net/guides/esign-document-with-image-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)

### Lihat Juga
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
