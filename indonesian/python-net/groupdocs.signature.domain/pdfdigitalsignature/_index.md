---
title: "Kelas PdfDigitalSignature"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Mewakili properti tanda tangan digital PDF."
type: docs
url: /id/python-net/groupdocs.signature.domain/pdfdigitalsignature/
is_root: false
weight: 420
---


## PdfDigitalSignature class

Mewakili properti tanda tangan digital PDF.

Tipe PdfDigitalSignature menampilkan anggota-anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/__init__/) | Menginisialisasi tanda tangan digital PDF tanpa sertifikat. |
| [__init__](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/__init__/#store) | Menginisialisasi tanda tangan digital PDF menggunakan penyimpanan X509 yang ditentukan. Sertifikat pertama dari penyimpanan akan digunakan. |
| [__init__](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/__init__/#store-index) | Menginisialisasi tanda tangan digital PDF menggunakan penyimpanan X509 yang ditentukan dan indeks sertifikat. |
| [__init__](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/__init__/#certificate) | Menginisialisasi tanda tangan digital PDF dengan sertifikat X509 yang ditentukan. |

### Metode
| Metode | Deskripsi |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/clone/) | Menggandakan instance tanda tangan digital PDF. |
| [equals](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/equals/#obj) | Membandingkan properti tanda tangan untuk menentukan kesetaraan. |
| [equals_object](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/equals_object/) |  |
| [get_hash_code](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/get_hash_code/) | Menimpa metode GetHashCode. |
| [load_digital_signatures](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures/) | Muat tanda tangan digital dari semua penyimpanan sertifikat X509 sistem. (diturunkan dari [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)) |
| [load_digital_signatures_file](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures_file/) | (diturunkan dari [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)) |
| [load_digital_signatures_store_name](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures_store_name/) | (diturunkan dari [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)) |
| [load_digital_signatures_string](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures_string/) | (diturunkan dari [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)) |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [contact_info](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/contact_info/) | Informasi kontak yang diberikan oleh penandatangan untuk memungkinkan penerima memverifikasi tanda tangan, misalnya nomor telepon. |
| [location](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/location/) | Nama host CPU atau lokasi fisik penandatanganan. |
| [reason](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/reason/) | Alasan penandatanganan, seperti (I agree). |
| [show_properties](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/show_properties/) | Flag yang memaksa properti tanda tangan ditampilkan atau disembunyikan; ketika true, bidang tanda tangan menggunakan format tampilan yang telah ditentukan (misalnya, `Digitally signed by {PdfDigitalSignature.contact_info} Date: {Date} Reason: {PdfDigitalSignature.reason} Location: {PdfDigitalSignature.location}`) dan defaultnya True. |
| [time_stamp](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/time_stamp/) | Stempel waktu untuk tanda tangan digital PDF. Nilai default adalah None. |
| [type](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/type/) | Tipe tanda tangan digital PDF. |
| [certificate](/signature/python-net/groupdocs.signature.domain/digitalsignature/certificate/) | Sertifikat X509 yang terkait dengan tanda tangan digital. (diturunkan dari [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)) |
| [certificate_custom_store_name](/signature/python-net/groupdocs.signature.domain/digitalsignature/certificate_custom_store_name/) | Nama penyimpanan khusus dari sertifikat. (diturunkan dari [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)) |
| [certificate_store_location](/signature/python-net/groupdocs.signature.domain/digitalsignature/certificate_store_location/) | Lokasi penyimpanan sertifikat. (diturunkan dari [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)) |
| [certificate_store_name](/signature/python-net/groupdocs.signature.domain/digitalsignature/certificate_store_name/) | Nama penyimpanan sertifikat. (diturunkan dari [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)) |
| [comments](/signature/python-net/groupdocs.signature.domain/digitalsignature/comments/) | Komentar tujuan penandatanganan. (diturunkan dari [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)) |
| [created_on](/signature/python-net/groupdocs.signature.domain/basesignature/created_on/) | Tanggal pembuatan tanda tangan. (diturunkan dari [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [deleted](/signature/python-net/groupdocs.signature.domain/basesignature/deleted/) | Bendera yang menunjukkan apakah tanda tangan ini telah dihapus dari dokumen. (diturunkan dari [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [height](/signature/python-net/groupdocs.signature.domain/basesignature/height/) | Tinggi tanda tangan. (diturunkan dari [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [is_signature](/signature/python-net/groupdocs.signature.domain/basesignature/is_signature/) | Bendera yang menunjukkan apakah komponen ini mewakili tanda tangan (`True`) atau konten dokumen (`False`). (diturunkan dari [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [is_valid](/signature/python-net/groupdocs.signature.domain/digitalsignature/is_valid/) | Tanda tangan digital valid dan dokumen tidak diubah. (diturunkan dari [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)) |
| [left](/signature/python-net/groupdocs.signature.domain/basesignature/left/) | Posisi kiri tanda tangan. (diturunkan dari [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [modified_on](/signature/python-net/groupdocs.signature.domain/basesignature/modified_on/) | Tanggal modifikasi tanda tangan. (diturunkan dari [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [page_number](/signature/python-net/groupdocs.signature.domain/basesignature/page_number/) | Nomor halaman tempat tanda tangan ditemukan. (diturunkan dari [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [sign_time](/signature/python-net/groupdocs.signature.domain/digitalsignature/sign_time/) | Waktu dokumen ditandatangani. (diturunkan dari [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)) |
| [signature_id](/signature/python-net/groupdocs.signature.domain/basesignature/signature_id/) | Pengidentifikasi unik tanda tangan, digunakan untuk memodifikasi tanda tangan dalam dokumen melalui operasi pembaruan atau penghapusan. (diturunkan dari [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [signature_type](/signature/python-net/groupdocs.signature.domain/basesignature/signature_type/) | Jenis tanda tangan. (diturunkan dari [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [thumbprint](/signature/python-net/groupdocs.signature.domain/digitalsignature/thumbprint/) | Sidik jari sertifikat. (diturunkan dari [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)) |
| [top](/signature/python-net/groupdocs.signature.domain/basesignature/top/) | Posisi atas tanda tangan. (diturunkan dari [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [width](/signature/python-net/groupdocs.signature.domain/basesignature/width/) | Lebar tanda tangan. (diturunkan dari [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [xad_es_type](/signature/python-net/groupdocs.signature.domain/digitalsignature/xad_es_type/) | Tipe XAdES ([`DigitalSignature.x_ad_es_type`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)). (diturunkan dari [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)) |

### Lihat Juga
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
