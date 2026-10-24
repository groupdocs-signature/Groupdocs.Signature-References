---
title: "Класс MetadataSignOptions"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Представляет параметры подписи метаданных."
type: docs
url: /ru/python-net/groupdocs.signature.options/metadatasignoptions/
is_root: false
weight: 320
---


## MetadataSignOptions class

Представляет параметры подписи метаданных.

Узнать больше

- Basic usage of creating Metadata electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Metadata+signature
- Advanced usage of settings of Metadata electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Metadata+signature+-+advanced

Тип MetadataSignOptions раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/metadatasignoptions/__init__/) | Инициализирует новый экземпляр класса MetadataSignOptions со значениями по умолчанию. |
| [__init__](/signature/python-net/groupdocs.signature.options/metadatasignoptions/__init__/#signatures) | Инициализирует новый экземпляр [`MetadataSignOptions`](/signature/python-net/groupdocs.signature.options/metadatasignoptions/) с метаданными. |

### Методы
| Метод | Описание |
| :- | :- |
| [add](/signature/python-net/groupdocs.signature.options/metadatasignoptions/add/#metadata_signature) | Добавить существующий экземпляр MetadataSignature в коллекцию. |
| [add_image_signature](/signature/python-net/groupdocs.signature.options/metadatasignoptions/add_image_signature/#id-value) | Создаёт новый ImageMetadataSignature с заданными аргументами и добавляет его в коллекцию. |
| [add_image_signature_uint16](/signature/python-net/groupdocs.signature.options/metadatasignoptions/add_image_signature_uint16/) |  |
| [add_metadata_signature](/signature/python-net/groupdocs.signature.options/metadatasignoptions/add_metadata_signature/) |  |
| [add_pdf_signature](/signature/python-net/groupdocs.signature.options/metadatasignoptions/add_pdf_signature/#name-value-tag) | Создаёт новый PdfMetadataSignature с заданными аргументами и добавляет его в коллекцию. |
| [add_pdf_signature_file](/signature/python-net/groupdocs.signature.options/metadatasignoptions/add_pdf_signature_file/) |  |
| [add_pdf_signature_string](/signature/python-net/groupdocs.signature.options/metadatasignoptions/add_pdf_signature_string/) |  |

### Свойства
| Свойство | Описание |
| :- | :- |
| [data_encryption](/signature/python-net/groupdocs.signature.options/metadatasignoptions/data_encryption/) | Реализация [`IDataEncryption`](/signature/python-net/groupdocs.signature.domain.extensions/idataencryption/) используется для шифрования всех подписей метаданных в этой коллекции параметров. |
| [signatures](/signature/python-net/groupdocs.signature.options/metadatasignoptions/signatures/) | Подписи метаданных, связанные с подписью. |
| [all_pages](/signature/python-net/groupdocs.signature.options/signoptions/all_pages/) | Подпись будет размещена на всех страницах документа. (унаследовано от [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [appearance](/signature/python-net/groupdocs.signature.options/signoptions/appearance/) | Дополнительный внешний вид подписи. (унаследовано от [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [document_type](/signature/python-net/groupdocs.signature.options/signoptions/document_type/) | Тип документа параметров подписи (`DocumentType`). (унаследовано от [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/signoptions/extensions/) | Расширения подписи. (унаследовано от [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [hash_algorithm](/signature/python-net/groupdocs.signature.options/signoptions/hash_algorithm/) | Алгоритм хеширования, используемый для криптографических операций. Поддерживается исключительно для цифровых подписей в PDF‑файлах. (унаследовано от [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/signoptions/page_number/) | Номер страницы документа для подписи. (унаследовано от [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/signoptions/pages_setup/) | Параметры для указания страниц, которые необходимо подписать. (унаследовано от [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [signature_type](/signature/python-net/groupdocs.signature.options/signoptions/signature_type/) | Тип подписи (`SignatureType`). (унаследовано от [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [zorder](/signature/python-net/groupdocs.signature.options/signoptions/zorder/) | Позиция Z‑порядка текстовой подписи, определяющая порядок отображения перекрывающихся подписей. (унаследовано от [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |

### Пример

```python
from datetime import datetime
from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSignOptions
from groupdocs.signature.domain import WordProcessingMetadataSignature

with Signature("sample.docx") as signature:
    options = MetadataSignOptions()
    signatures = [
        WordProcessingMetadataSignature("Author", "Mr.Scherlock Holmes"),
        WordProcessingMetadataSignature("DateCreated", datetime.now()),
        WordProcessingMetadataSignature("DocumentId", 123456),
        WordProcessingMetadataSignature("SignatureId", 123.456),
    ]
    options.signatures.add_range(signatures)
    result = signature.sign("signed.docx", options)
    print(f"Signed with {len(result.succeeded)} metadata signature(s).")
```

### См. также
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
