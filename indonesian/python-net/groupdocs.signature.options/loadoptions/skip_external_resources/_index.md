---
title: "properti skip_external_resources"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Bendera yang menghentikan dokumen dari memuat sumber daya eksternal."
type: docs
url: /id/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/
is_root: false
weight: 2050
---


## skip_external_resources property

Flag yang menghentikan dokumen dari memuat sumber daya eksternal. Nilai default adalah True; sumber daya eksternal tidak dimuat kecuali yang cocok dengan [`LoadOptions.WhitelistedResources`](/signature/python-net/groupdocs.signature.options/loadoptions/whitelisted_resources/).

Sebuah dokumen dapat merujuk ke sumber daya yang disimpan di luar, seperti gambar yang ditautkan, gambar yang disisipkan oleh bidang INCLUDEPICTURE, gambar yang ditautkan dalam presentasi dan spreadsheet, serta gambar dan lembar gaya yang direferensikan oleh gambar SVG. Memuat sumber daya semacam itu membuat perpustakaan meminta alamatnya. Pada server yang memproses dokumen yang tidak terpercaya, sebuah dokumen dapat menggunakan ini untuk membuat server mengirim permintaan ke alamat internal (pemalsuan permintaan sisi‑server), dan jalur UNC atau `file://` dapat menyebabkan Windows mengirim kredensial NTLM akun ke host lain. Pada instalasi offline atau yang terisolasi, permintaan gagal atau menunggu batas waktu.

Sumber daya yang dilewati tidak digambar dalam pratinjau halaman atau dalam dokumen yang disimpan sebagai gambar, dan pencarian gambar, barcode, serta QR‑code tidak melihatnya. Atur properti ini ke False hanya untuk dokumen yang tepercaya, dan lebih baik mengizinkan alamat tertentu dengan [`LoadOptions.WhitelistedResources`](/signature/python-net/groupdocs.signature.options/loadoptions/whitelisted_resources/).

Pengaturan ini berlaku untuk dokumen pengolah kata, presentasi, spreadsheet, dan gambar SVG, termasuk dokumen di dalam arsip. Untuk gambar SVG, referensi yang tidak diizinkan dihapus dari gambar sebelum dibaca, dan gambar SVG yang bukan XML yang terbentuk dengan baik ditolak. Pengaturan ini tidak mengontrol pemeriksaan pencabutan sertifikat, server stempel waktu, atau lisensi.

Properti ini menggantikan [`LoadOptions.LoadExternalResources`](/signature/python-net/groupdocs.signature.options/loadoptions/load_external_resources/), yang memiliki arti berlawanan.

### Definition:
```python
@property
def skip_external_resources(self):
    ...
@skip_external_resources.setter
def skip_external_resources(self, value):
    ...
```

### Lihat Juga
* class [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/)
