---
title: "метод get_document_info"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Получает информацию о страницах документа: их размеры, максимальную высоту страницы, ширину страницы с максимальной высотой."
type: docs
url: /ru/python-net/groupdocs.signature/signature/get_document_info/
is_root: false
weight: 1130
---


## get_document_info

Получает информацию о страницах документа: их размеры, максимальную высоту страницы, ширину страницы с максимальной высотой.

Узнайте больше о подписанном документе — тип файла, количество страниц и многие другие свойства, специфичные для формата:
- https://docs.groupdocs.com/display/signaturenet/Get+document+information

```python
def get_document_info(self):
    ...
```

**Returns:** Information about document.

### Пример

```python
from groupdocs.signature import Signature

with Signature("sample.pdf") as signature:
    info = signature.get_document_info()
    print(f"File type: {info.file_type.file_format}")
    print(f"Pages count: {info.page_count}")
    print(f"File size: {info.size} bytes")
    for page in info.pages:
        # page_number начинается с 0: 0 — первая страница
        print(f"Page {page.page_number}: {page.width} x {page.height}")
```

### См. также
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
