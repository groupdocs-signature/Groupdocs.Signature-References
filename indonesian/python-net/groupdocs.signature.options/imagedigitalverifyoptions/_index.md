---
title: "Kelas ImageDigitalVerifyOptions"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Menyimpan opsi untuk memverifikasi tanda tangan digital dalam gambar raster."
type: docs
url: /id/python-net/groupdocs.signature.options/imagedigitalverifyoptions/
is_root: false
weight: 220
---


## ImageDigitalVerifyOptions class

Menyimpan opsi untuk memverifikasi tanda tangan digital dalam gambar raster.

Tipe ImageDigitalVerifyOptions menampilkan anggota-anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/imagedigitalverifyoptions/__init__/) | Menginisialisasi instance baru dari kelas ImageDigitalVerifyOptions untuk memverifikasi tanda tangan digital (steganografi) pada gambar raster. |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [detected_probability](/signature/python-net/groupdocs.signature.options/imagedigitalverifyoptions/detected_probability/) | Probabilitas yang dikembalikan oleh AnalyzePercentageDigitalSignature (0-100). |
| [detection_threshold_percent](/signature/python-net/groupdocs.signature.options/imagedigitalverifyoptions/detection_threshold_percent/) | Persentase ambang deteksi untuk ekstraksi parsial (0-100). Nilai default adalah 75. |
| [password](/signature/python-net/groupdocs.signature.options/imagedigitalverifyoptions/password/) | Kata sandi yang digunakan untuk menyematkan tanda tangan. |
| [use_full_data_extraction](/signature/python-net/groupdocs.signature.options/imagedigitalverifyoptions/use_full_data_extraction/) | Properti ini menentukan apakah ekstraksi data penuh (AnalyzePercentageDigitalSignature) dilakukan untuk akurasi maksimum. |
| [all_pages](/signature/python-net/groupdocs.signature.options/verifyoptions/all_pages/) | Bendera yang menunjukkan apakah setiap halaman dokumen harus diverifikasi. Secara default nilainya True. (diturunkan dari [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/verifyoptions/extensions/) | Ekstensi tambahan untuk verifikasi opsi tanda tangan alternatif. (diturunkan dari [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [is_valid](/signature/python-net/groupdocs.signature.options/verifyoptions/is_valid/) | Bendera properti valid. (diturunkan dari [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/verifyoptions/page_number/) | Nomor halaman dokumen yang akan diverifikasi; jika tidak disetel, semua halaman dokumen diverifikasi untuk kejadian pertama (nilai minimum adalah 1). (diturunkan dari [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/verifyoptions/pages_setup/) | Opsi halaman untuk menentukan halaman yang akan diverifikasi. (diturunkan dari [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/verifyoptions/shape_position/) | Posisi bentuk dalam tata letak dokumen yang digunakan untuk memverifikasi tanda tangan di header/footer. (diturunkan dari [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |

### Lihat Juga
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
