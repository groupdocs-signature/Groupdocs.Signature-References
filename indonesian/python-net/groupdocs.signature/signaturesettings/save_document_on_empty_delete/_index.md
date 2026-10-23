---
title: "properti save_document_on_empty_delete"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Flag yang menentukan apakah dokumen sumber disimpan kembali ketika metode Delete tidak memiliki tanda tangan yang terpengaruh untuk dihapus."
type: docs
url: /id/python-net/groupdocs.signature/signaturesettings/save_document_on_empty_delete/
is_root: false
weight: 2050
---


## save_document_on_empty_delete property

Flag yang menentukan apakah dokumen sumber disimpan kembali ketika metode Delete tidak memiliki tanda tangan yang terpengaruh untuk dihapus.

Ketika True (default), dokumen disimpan dengan log riwayat (tanggal dan jenis operasi) bahkan jika tidak ada tanda tangan yang dihapus; ketika False, dokumen sumber tetap tidak berubah.

### Definition:
```python
@property
def save_document_on_empty_delete(self):
    ...
@save_document_on_empty_delete.setter
def save_document_on_empty_delete(self, value):
    ...
```

### Lihat Juga
* class [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/)
