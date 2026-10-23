---
title: "Kelas DigitalSignOptions"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Menunjukkan opsi tanda tangan digital."
type: docs
url: /id/python-net/groupdocs.signature.options/digitalsignoptions/
is_root: false
weight: 140
---


## DigitalSignOptions class

Menunjukkan opsi tanda tangan digital.

Pelajari lebih lanjut

- Basic usage of creating Digital electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Digital+signature
- Advanced usage of settings of Digital electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Digital+signature+-+advanced

Tipe DigitalSignOptions menampilkan anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/) | Menginisialisasi instance baru dari kelas DigitalSignOptions dengan nilai default. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/#certificate_file_path) | Menginisialisasi instance baru DigitalSignOptions dengan file sertifikat. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/#certificate_stream) | Menginisialisasi instance baru DigitalSignOptions dengan aliran sertifikat. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/#certificate_file_path-image_file_path) | Menginisialisasi instance baru dari kelas DigitalSignOptions dengan file sertifikat dan file gambar tampilan. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/#certificate_file_path-appearence_image_stream) | Menginisialisasi instance baru DigitalSignOptions dengan file sertifikat dan aliran gambar tampilan. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/#certificate_stream-image_file_path) | Menginisialisasi instance baru DigitalSignOptions dengan aliran sertifikat dan file gambar tampilan. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/#certificate_stream-appearence_image_stream) | Menginisialisasi instance baru DigitalSignOptions dengan aliran sertifikat dan aliran gambar tampilan. |

### Metode
| Metode | Deskripsi |
| :- | :- |
| [dispose](/signature/python-net/groupdocs.signature.options/imagesignoptions/dispose/) | Menghapus sumber daya internal. (diturunkan dari [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |
| [from_base64](/signature/python-net/groupdocs.signature.options/imagesignoptions/from_base64/) | Membuat instance baru ImageSignOptions dengan gambar yang telah ditentukan sebelumnya dari string Base64. (diturunkan dari [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [allow_expired](/signature/python-net/groupdocs.signature.options/digitalsignoptions/allow_expired/) | Flag yang memungkinkan penandatanganan dengan sertifikat yang masa berlakunya telah berakhir. Nilai default adalah False; penandatanganan dengan sertifikat yang kedaluwarsa memunculkan `GroupDocsSignatureException` dan dokumen tidak ditandatangani. |
| [allow_not_yet_valid](/signature/python-net/groupdocs.signature.options/digitalsignoptions/allow_not_yet_valid/) | Flag yang memungkinkan penandatanganan dengan sertifikat yang masa berlakunya belum dimulai. Nilai default adalah False; penandatanganan dengan sertifikat semacam itu memunculkan `GroupDocsSignatureException` dan dokumen tidak ditandatangani. |
| [certificate_file_path](/signature/python-net/groupdocs.signature.options/digitalsignoptions/certificate_file_path/) | Path file sertifikat digital. |
| [certificate_stream](/signature/python-net/groupdocs.signature.options/digitalsignoptions/certificate_stream/) | Aliran sertifikat digital. Jika properti ini ditentukan, selalu digunakan menggantikan CertificateFilePath. |
| [contact](/signature/python-net/groupdocs.signature.options/digitalsignoptions/contact/) | Kontak tanda tangan. |
| [custom_sign_hash](/signature/python-net/groupdocs.signature.options/digitalsignoptions/custom_sign_hash/) | Fungsi penandatanganan hash khusus yang digunakan untuk menandatangani dokumen, memungkinkan pengguna mengimplementasikan logika penandatanganan digital mereka sendiri. |
| [height](/signature/python-net/groupdocs.signature.options/digitalsignoptions/height/) | Tinggi area tanda tangan pada halaman dokumen dalam satuan ukuran (pixel, persen, atau milimeter; lihat `MeasureType`). |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/digitalsignoptions/horizontal_alignment/) | Perataan horizontal gambar pada halaman dokumen. |
| [left](/signature/python-net/groupdocs.signature.options/digitalsignoptions/left/) | Posisi X kiri area tanda tangan pada halaman dokumen dalam satuan ukuran (pixel, persen, atau milimeter sebagaimana didefinisikan oleh `MeasureType.location_measure_type`). |
| [location](/signature/python-net/groupdocs.signature.options/digitalsignoptions/location/) | Lokasi tanda tangan. |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/digitalsignoptions/location_measure_type/) | Tipe ukuran (pixel, persen, atau milimeter) untuk properti kiri dan atas. |
| [margin](/signature/python-net/groupdocs.signature.options/digitalsignoptions/margin/) | Ruang yang ditentukan secara default antara gambar dan tepi dokumen (berlaku ketika penyelarasan horizontal atau vertikal ditentukan). |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/digitalsignoptions/margin_measure_type/) | Jenis pengukuran margin (piksel, persen, atau milimeter). |
| [password](/signature/python-net/groupdocs.signature.options/digitalsignoptions/password/) | Kata sandi sertifikat digital. |
| [reason](/signature/python-net/groupdocs.signature.options/digitalsignoptions/reason/) | Alasan tanda tangan. |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/digitalsignoptions/rotation_angle/) | Sudut rotasi searah jarum jam. |
| [signature](/signature/python-net/groupdocs.signature.options/digitalsignoptions/signature/) | Properti tanda tangan digital untuk dokumen. Untuk penandatanganan PDF, properti lanjutan dapat diatur menggunakan instance [`PdfDigitalSignature`](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/). |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/digitalsignoptions/size_measure_type/) | Jenis pengukuran (piksel, persen, atau milimeter) untuk properti Width dan Height. |
| [stretch](/signature/python-net/groupdocs.signature.options/digitalsignoptions/stretch/) | Mode peregangan pada halaman dokumen. |
| [top](/signature/python-net/groupdocs.signature.options/digitalsignoptions/top/) | Posisi Y atas area tanda tangan pada halaman dokumen dalam satuan ukuran (pixel, persen, atau milimeter; lihat `MeasureType` `LocationMeasureType`). |
| [transparency](/signature/python-net/groupdocs.signature.options/digitalsignoptions/transparency/) | Transparansi tanda tangan digital, berkisar antara 0.0 hingga 1.0. Default adalah 0. |
| [use_ltv](/signature/python-net/groupdocs.signature.options/digitalsignoptions/use_ltv/) | Flag validasi LTV (Long Term Validation). |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/digitalsignoptions/vertical_alignment/) | Perataan vertikal gambar pada halaman dokumen. |
| [visible](/signature/python-net/groupdocs.signature.options/digitalsignoptions/visible/) | Visibilitas tanda tangan. |
| [width](/signature/python-net/groupdocs.signature.options/digitalsignoptions/width/) | Lebar area tanda tangan pada halaman dokumen dalam nilai ukuran (pixel, persen, atau milimeter). Satuan pengukuran didefinisikan oleh `MeasureType` melalui properti SizeMeasureType. |
| [xad_es_type](/signature/python-net/groupdocs.signature.options/digitalsignoptions/xad_es_type/) | Tipe XAdES. Nilai default adalah None (XAdES dimatikan). |
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
from groupdocs.signature.options import DigitalSignOptions

def sign_with_digital_signature_advanced():
    with Signature("sample.pdf") as signature:
        # Berikan sertifikat dan gambar tampilan ke konstruktor
        options = DigitalSignOptions("certificate.pfx", "signature.jpg")
        options.password = "1234567890"

        # Tampilkan tanda tangan pada halaman, pada posisi dan ukuran ini
        options.visible = True
        options.left = 100
        options.top = 400
        options.width = 200
        options.height = 100

        # Informasi yang disimpan dalam tanda tangan
        options.contact = "John Smith"
        options.reason = "Approval"
        options.location = "New York"

        result = signature.sign("signed_digital_advanced.pdf", options)
        print(f"Signed with {len(result.succeeded)} digital signature(s)")

if __name__ == "__main__":
    sign_with_digital_signature_advanced()
```

### Guides
Panduan tugas yang menggunakan `DigitalSignOptions`:

* [Sign Document with Digital Signature](/signature/python-net/guides/esign-document-with-digital-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)

### Lihat Juga
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
