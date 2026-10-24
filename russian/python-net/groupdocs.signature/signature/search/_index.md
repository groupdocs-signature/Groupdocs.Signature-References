---
title: "метод search"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Ищет подписи в документе, используя список SearchOptions."
type: docs
url: /ru/python-net/groupdocs.signature/signature/search/
is_root: false
weight: 1140
---


## search {#search_options_list}

Ищет подписи в документе, используя список [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/).

Узнать больше

- More about search electronic signatures in a documents using GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document
- More about electronic signatures search dependent on eSign type: https://docs.groupdocs.com/display/signaturenet/Searching

```python
def search(self, search_options_list):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| search_options_list | `List[SearchOptions]` | Коллекция параметров поиска. |

**Returns:** SearchResult: Instance containing the list of found signatures.

### Пример

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

with Signature("signed.pdf") as signature:
    result = signature.search([TextSearchOptions()])
    for found in result.signatures:
        print(f"Text signature '{found.text}' on page {found.page_number}")
```

## search {#search_options_list-predicate}

Ищет подписи в документе, используя предоставленные параметры поиска, и фильтрует результаты на основе указанного предиката.

Узнать больше:
- More about search electronic signatures in a documents using GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document
- More about electronic signatures search dependent on eSign type: https://docs.groupdocs.com/display/signaturenet/Searching

```python
def search(self, search_options_list, predicate):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| search_options_list | `List[SearchOptions]` | Список экземпляров `SearchOptions`, определяющих критерии поиска подписей. |
| predicate | `Func[BaseSignature, bool]` | Предикат фильтра, применяемый к списку найденных подписей. |

**Returns:** SearchResult: A `SearchResult` containing the signatures that match the specified search options and satisfy the predicate.

### Пример

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def search_document_for_signatures():
    with Signature("signed.pdf") as signature:
        # Ищите текстовые подписи на каждой странице
        result = signature.search([TextSearchOptions()])
        for found in result.signatures:
            print(f"Text signature '{found.text}' on page {found.page_number}")

if __name__ == "__main__":
    search_document_for_signatures()
```

## search {#search_options}

```python
def search(self, search_options):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| search_options | `SearchOptions` |  |

## search {#signature_type}

```python
def search(self, signature_type):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| signature_type | `SignatureType` |  |

## search {#signature_types}

Ищет указанные типы подписей в документе по значению `SignatureType`.

- More about search electronic signatures in a documents using GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document
- More about electronic signatures search dependent on eSign type: https://docs.groupdocs.com/display/signaturenet/Searching

```python
def search(self, signature_types):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| signature_types | `list[SignatureType]` | Один или несколько типов подписей для поиска. |

**Returns:** SearchResult: Instance containing the list of found signatures.

### Пример

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def search_document_for_signatures():
    with Signature("signed.pdf") as signature:
        # Ищите текстовые подписи на каждой странице
        result = signature.search([TextSearchOptions()])
        for found in result.signatures:
            print(f"Text signature '{found.text}' on page {found.page_number}")

if __name__ == "__main__":
    search_document_for_signatures()
```

## search {#predicate}

Ищет подписи в документе, используя все доступные параметры поиска, и фильтрует результаты на основе указанного предиката.

- More about search electronic signatures in a documents using GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document
- More about electronic signatures search dependent on eSign type: https://docs.groupdocs.com/display/signaturenet/Searching

```python
def search(self, predicate):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| predicate | `Func[BaseSignature, bool]` | Callable[[BaseSignature], bool] – функция, получающая `BaseSignature` и возвращающая `True`, чтобы сохранить подпись, или `False`, чтобы отбрасывать её. |

**Returns:** list[BaseSignature]: A list of `BaseSignature` instances that satisfy the provided predicate.

### Пример

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def is_text_signature(sig):
    return hasattr(sig, "text") and sig.text.startswith("Invoice")

with Signature("signed.pdf") as signature:
    # Ищите текстовые подписи и фильтруйте их с помощью пользовательского предиката
    result = signature.search([TextSearchOptions()], predicate=is_text_signature)
    for found in result.signatures:
        print(f"Found text signature: {found.text} on page {found.page_number}")
```

### См. также
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
