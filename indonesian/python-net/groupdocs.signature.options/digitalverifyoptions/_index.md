---
title: "Kelas DigitalVerifyOptions"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Menyimpan opsi untuk memverifikasi tanda tangan digital dokumen."
type: docs
url: /id/python-net/groupdocs.signature.options/digitalverifyoptions/
is_root: false
weight: 150
---


## DigitalVerifyOptions class

Menyimpan opsi untuk memverifikasi tanda tangan digital dokumen.

Pelajari lebih lanjut

- Basic usage of verification for Digital electronic signature by GroupDocs.Signature: [How to eVerification Digital signatures in a document](https://docs.groupdocs.com/display/signaturenet/Verify+Digital+signatures+in+the+document)
- Advanced usage of settings of verification for Digital electronic signature with GroupDocs.Signature: Advanced usage of eVerification Digital signatures in a document and additional settings

Tipe DigitalVerifyOptions menampilkan anggota-anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/__init__/) | Menginisialisasi instance DigitalVerifyOptions dengan nilai default. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/__init__/#certificate_file_path) | Menginisialisasi instance DigitalVerifyOptions dengan jalur file sertifikat digital yang diberikan. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/__init__/#certificate_stream) | Menginisialisasi instance DigitalVerifyOptions dengan aliran sertifikat yang diberikan. |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [certificate](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/certificate/) | Sertifikat X509Certificate2 yang diperoleh dari jalur file sertifikat atau aliran. |
| [certificate_file_path](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/certificate_file_path/) | Jalur file sertifikat digital. |
| [certificate_stream](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/certificate_stream/) | Aliran sertifikat digital. |
| [comments](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/comments/) | Komentar tanda tangan digital yang akan divalidasi. |
| [contact](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/contact/) | Kontak tanda tangan yang akan divalidasi. |
| [issuer_name](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/issuer_name/) | Nama penerbit sertifikat yang akan divalidasi. |
| [location](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/location/) | Lokasi tanda tangan yang akan divalidasi. |
| [password](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/password/) | Kata sandi sertifikat digital jika diperlukan. |
| [reason](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/reason/) | Alasan tanda tangan digital yang akan divalidasi. |
| [sign_date_time_from](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/sign_date_time_from/) | Awal rentang tanggal dan waktu tanda tangan digital yang akan divalidasi. Nilai None akan diabaikan. |
| [sign_date_time_to](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/sign_date_time_to/) | Akhir rentang tanggal dan waktu tanda tangan digital yang akan divalidasi. Nilai null akan diabaikan. |
| [subject_name](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/subject_name/) | Nama subjek yang dibedakan dari sertifikat yang akan divalidasi; verifikasi memeriksa apakah nama subjek tanda tangan mengandung atau sama dengan nilai case‑sensitive ini. |
| [all_pages](/signature/python-net/groupdocs.signature.options/verifyoptions/all_pages/) | Bendera yang menunjukkan apakah setiap halaman dokumen harus diverifikasi. Secara default nilainya True. (diturunkan dari [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/verifyoptions/extensions/) | Ekstensi tambahan untuk verifikasi opsi tanda tangan alternatif. (diturunkan dari [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [is_valid](/signature/python-net/groupdocs.signature.options/verifyoptions/is_valid/) | Bendera properti valid. (diturunkan dari [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/verifyoptions/page_number/) | Nomor halaman dokumen yang akan diverifikasi; jika tidak disetel, semua halaman dokumen diverifikasi untuk kejadian pertama (nilai minimum adalah 1). (diturunkan dari [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/verifyoptions/pages_setup/) | Opsi halaman untuk menentukan halaman yang akan diverifikasi. (diturunkan dari [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/verifyoptions/shape_position/) | Posisi bentuk dalam tata letak dokumen yang digunakan untuk memverifikasi tanda tangan di header/footer. (diturunkan dari [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |

### Lihat Juga
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
