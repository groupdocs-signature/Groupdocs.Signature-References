---
title: "Kelas DigitalVBA"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Mewakili tanda tangan digital untuk proyek VBA Spreadsheet."
type: docs
url: /id/python-net/groupdocs.signature.domain.extensions/digitalvba/
is_root: false
weight: 60
---


## DigitalVBA class

Mewakili tanda tangan digital untuk proyek VBA Spreadsheet.

Memberikan kemampuan untuk menandatangani proyek VBA dalam format dokumen spreadsheet seperti `Xlsm` atau `Xltm`. Jika beberapa ekstensi [`DigitalVBA`](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/) ditambahkan ke [`DigitalSignOptions.extensions`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/), hanya yang pertama yang digunakan selama penandatanganan.

Tipe DigitalVBA menampilkan anggota-anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/__init__/#certificate_file_path-password) | Menginisialisasi instance baru dari kelas DigitalVBA dengan file sertifikat. |
| [__init__](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/__init__/#certificate_stream-password) | Menginisialisasi instance baru dari kelas DigitalVBA dengan aliran sertifikat. |

### Metode
| Metode | Deskripsi |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain.extensions/signatureextension/clone/) | Mendapatkan salinan objek ini. (diturunkan dari [`SignatureExtension`](/signature/python-net/groupdocs.signature.domain.extensions/signatureextension/)) |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [certificate_file_path](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/certificate_file_path/) | Jalur file sertifikat digital, hanya digunakan jika `CertificateStream` tidak ditentukan. |
| [certificate_stream](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/certificate_stream/) | Aliran sertifikat digital. Jika properti ini ditentukan, selalu digunakan menggantikan CertificateFilePath. |
| [comments](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/comments/) | Komentar tanda tangan. |
| [password](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/password/) | Kata sandi sertifikat digital. |
| [sign_only_vba_project](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/sign_only_vba_project/) | Pengaturan yang menentukan apakah hanya proyek VBA yang ditandatangani. Ketika True, dokumen spreadsheet itu sendiri tidak ditandatangani; hanya proyek VBA yang ditandatangani. |

### Contoh

```python
import zipfile
from groupdocs.signature import Signature
from groupdocs.signature.domain.extensions import DigitalVBA
from groupdocs.signature.options import DigitalSignOptions


def sign_spreadsheet_macros_only():
    # Menandatangani makro dalam spreadsheet
    with Signature("sample.xlsm") as signature:
        sign_options = DigitalSignOptions()

        # Menambahkan ekstensi untuk menandatangani proyek VBA secara digital
        digital_vba = DigitalVBA("certificate.pfx", "1234567890")
        digital_vba.sign_only_vba_project = True
        digital_vba.comments = "Signed VBA macros"
        sign_options.extensions.append(digital_vba)

        result = signature.sign("signed_macros.xlsm", sign_options)
        print(f"Signatures added: {len(result.succeeded)}")

    # Verifikasi bahwa bagian tanda tangan proyek VBA telah ditambahkan
    with zipfile.ZipFile("signed_macros.xlsm") as package:
        print("VBA project signed:", "xl/vbaProjectSignature.bin" in package.namelist())
```

### Lihat Juga
* module [`groupdocs.signature.domain.extensions`](/signature/python-net/groupdocs.signature.domain.extensions/)
