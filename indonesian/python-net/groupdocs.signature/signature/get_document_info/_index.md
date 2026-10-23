---
title: "metode get_document_info"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Mendapatkan informasi tentang halaman dokumen: ukuran mereka, tinggi maksimum halaman, lebar halaman dengan tinggi maksimum."
type: docs
url: /id/python-net/groupdocs.signature/signature/get_document_info/
is_root: false
weight: 1130
---


## get_document_info

Mendapatkan informasi tentang halaman dokumen: ukuran mereka, tinggi maksimum halaman, lebar halaman dengan tinggi maksimum.

Pelajari lebih lanjut tentang dokumen yang ditandatangani - tipe file, jumlah halaman, dan banyak properti spesifik format lainnya:
- https://docs.groupdocs.com/display/signaturenet/Get+document+information

```python
def get_document_info(self):
    ...
```

**Returns:** Information about document.

### Contoh

```python
from groupdocs.signature import Signature

with Signature("sample.pdf") as signature:
    info = signature.get_document_info()
    print(f"File type: {info.file_type.file_format}")
    print(f"Pages count: {info.page_count}")
    print(f"File size: {info.size} bytes")
    for page in info.pages:
        # page_number berbasis 0: 0 adalah halaman pertama
        print(f"Page {page.page_number}: {page.width} x {page.height}")
```

### Lihat Juga
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
