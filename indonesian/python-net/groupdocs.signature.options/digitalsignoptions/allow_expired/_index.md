---
title: "properti allow_expired"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Bendera yang memungkinkan penandatanganan dengan sertifikat yang masa berlakunya telah berakhir."
type: docs
url: /id/python-net/groupdocs.signature.options/digitalsignoptions/allow_expired/
is_root: false
weight: 2010
---


## allow_expired property

Flag yang memungkinkan penandatanganan dengan sertifikat yang masa berlakunya telah berakhir. Nilai default adalah False; penandatanganan dengan sertifikat yang kedaluwarsa memunculkan `GroupDocsSignatureException` dan dokumen tidak ditandatangani.

Validator melaporkan tanda tangan yang dibuat dengan sertifikat yang kedaluwarsa sebagai tidak valid. Atur properti ini ke True hanya ketika Anda memang membutuhkan tanda tangan semacam itu, misalnya untuk menguji dengan sertifikat lama. Dokumen kemudian ditandatangani, dan peringatan ditulis ke logger yang diatur dalam [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/).

Sertifikat dibandingkan dengan waktu saat ini dalam UTC, bukan dengan [`DigitalSignature.sign_time`](/signature/python-net/groupdocs.signature.domain/digitalsignature/sign_time/). Bendera ini berlaku untuk sertifikat yang diberikan oleh [`DigitalSignOptions.CertificateFilePath`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/certificate_file_path/), [`DigitalSignOptions.CertificateStream`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/certificate_stream/) atau [`DigitalSignOptions.Signature`](/signature/python-net/groupdocs.signature/signature/), dan, ketika spreadsheet ditandatangani, untuk sertifikat dari ekstensi [`DigitalVBA`](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/) pertama. Tanda tangan digital pada gambar tidak menggunakan sertifikat dan tidak diperiksa. Sertifikat yang masa berlakunya belum dimulai dikontrol oleh [`DigitalSignOptions.AllowNotYetValid`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/allow_not_yet_valid/).

### Definition:
```python
@property
def allow_expired(self):
    ...
@allow_expired.setter
def allow_expired(self, value):
    ...
```

### Lihat Juga
* class [`DigitalSignOptions`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/)
