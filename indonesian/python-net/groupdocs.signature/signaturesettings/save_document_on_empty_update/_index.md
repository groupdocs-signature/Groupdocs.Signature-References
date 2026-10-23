---
title: "properti save_document_on_empty_update"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Flag yang menentukan apakah dokumen sumber disimpan kembali ketika metode Update tidak memiliki tanda tangan untuk diperbarui."
type: docs
url: /id/python-net/groupdocs.signature/signaturesettings/save_document_on_empty_update/
is_root: false
weight: 2060
---


## save_document_on_empty_update property

Flag yang menentukan apakah dokumen sumber disimpan kembali ketika metode `Update` tidak memiliki tanda tangan untuk diperbarui.

Jika disetel ke `True` (default), dokumen disimpan dengan log proses riwayat yang sesuai (tanggal dan jenis operasi) bahkan ketika tidak ada tanda tangan yang diperbarui. Ketika disetel ke `False`, dokumen sumber tidak diubah sama sekali.

### Definition:
```python
@property
def save_document_on_empty_update(self):
    ...
@save_document_on_empty_update.setter
def save_document_on_empty_update(self, value):
    ...
```

### Lihat Juga
* class [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/)
