---
title: "get_document_info yöntemi"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "Belge sayfaları hakkında bilgi alır: boyutları, maksimum sayfa yüksekliği, maksimum yüksekliğe sahip sayfanın genişliği."
type: docs
url: /tr/python-net/groupdocs.signature/signature/get_document_info/
is_root: false
weight: 1130
---


## get_document_info

Belge sayfaları hakkında bilgi alır: boyutları, maksimum sayfa yüksekliği, maksimum yüksekliğe sahip sayfanın genişliği.

İmzalı belge hakkında daha fazla bilgi edinin - dosya türü, sayfa sayısı ve birçok diğer format özel özelliği:
- https://docs.groupdocs.com/display/signaturenet/Get+document+information

```python
def get_document_info(self):
    ...
```

**Returns:** Information about document.

### Örnek

```python
from groupdocs.signature import Signature

with Signature("sample.pdf") as signature:
    info = signature.get_document_info()
    print(f"File type: {info.file_type.file_format}")
    print(f"Pages count: {info.page_count}")
    print(f"File size: {info.size} bytes")
    for page in info.pages:
        # page_number 0 tabanlıdır: 0 ilk sayfadır
        print(f"Page {page.page_number}: {page.width} x {page.height}")
```

### Ayrıca Bakınız
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
