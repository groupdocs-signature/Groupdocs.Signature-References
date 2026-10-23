---
title: "properti allow_not_yet_valid"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Bendera yang memungkinkan penandatanganan dengan sertifikat yang masa berlakunya belum dimulai."
type: docs
url: /id/python-net/groupdocs.signature.options/digitalsignoptions/allow_not_yet_valid/
is_root: false
weight: 2020
---


## allow_not_yet_valid property

Flag yang memungkinkan penandatanganan dengan sertifikat yang masa berlakunya belum dimulai. Nilai default adalah False; penandatanganan dengan sertifikat semacam itu memunculkan `GroupDocsSignatureException` dan dokumen tidak ditandatangani.

Validator melaporkan tanda tangan yang dibuat sebelum sertifikat menjadi valid sebagai tidak valid. Sertifikat semacam itu biasanya diterbitkan untuk tanggal yang lebih lama, atau jam komputer salah. Ketika bendera ini True, dokumen ditandatangani, dan peringatan ditulis ke logger yang diatur dalam [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/).

Sertifikat dibandingkan dengan waktu saat ini dalam UTC. Bendera ini berlaku untuk sertifikat yang sama seperti [`DigitalSignOptions.AllowExpired`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/allow_expired/), yang mengontrol sertifikat yang masa berlakunya telah berakhir.

### Definition:
```python
@property
def allow_not_yet_valid(self):
    ...
@allow_not_yet_valid.setter
def allow_not_yet_valid(self, value):
    ...
```

### Lihat Juga
* class [`DigitalSignOptions`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/)
