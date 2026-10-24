---
title: "search yöntemi"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "Bir belgede imzaları, SearchOptions listesini kullanarak arar."
type: docs
url: /tr/python-net/groupdocs.signature/signature/search/
is_root: false
weight: 1140
---


## search {#search_options_list}

Bir belge içinde imzaları, bir [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/) listesi kullanarak arar.

Daha fazla bilgi edinin

- More about search electronic signatures in a documents using GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document
- More about electronic signatures search dependent on eSign type: https://docs.groupdocs.com/display/signaturenet/Searching

```python
def search(self, search_options_list):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| search_options_list | `List[SearchOptions]` | Arama seçenekleri koleksiyonu. |

**Returns:** SearchResult: Instance containing the list of found signatures.

### Örnek

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

with Signature("signed.pdf") as signature:
    result = signature.search([TextSearchOptions()])
    for found in result.signatures:
        print(f"Text signature '{found.text}' on page {found.page_number}")
```

## search {#search_options_list-predicate}

Belgedeki imzaları, sağlanan arama seçeneklerini kullanarak arar ve sonuçları belirtilen koşula göre filtreler.

Daha fazla bilgi:
- More about search electronic signatures in a documents using GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document
- More about electronic signatures search dependent on eSign type: https://docs.groupdocs.com/display/signaturenet/Searching

```python
def search(self, search_options_list, predicate):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| search_options_list | `List[SearchOptions]` | `SearchOptions` örneklerinden oluşan, imza arama kriterlerini tanımlayan bir liste. |
| predicate | `Func[BaseSignature, bool]` | Bulunan imzalar listesine uygulanacak filtre koşulu. |

**Returns:** SearchResult: A `SearchResult` containing the signatures that match the specified search options and satisfy the predicate.

### Örnek

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def search_document_for_signatures():
    with Signature("signed.pdf") as signature:
        # Her sayfada metin imzalarını arayın
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

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| search_options | `SearchOptions` |  |

## search {#signature_type}

```python
def search(self, signature_type):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| signature_type | `SignatureType` |  |

## search {#signature_types}

`SignatureType` değeriyle belgede belirtilen imza türlerini arar.

- More about search electronic signatures in a documents using GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document
- More about electronic signatures search dependent on eSign type: https://docs.groupdocs.com/display/signaturenet/Searching

```python
def search(self, signature_types):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| signature_types | `list[SignatureType]` | Bulunacak bir veya birden fazla imza türü. |

**Returns:** SearchResult: Instance containing the list of found signatures.

### Örnek

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def search_document_for_signatures():
    with Signature("signed.pdf") as signature:
        # Her sayfada metin imzalarını arayın
        result = signature.search([TextSearchOptions()])
        for found in result.signatures:
            print(f"Text signature '{found.text}' on page {found.page_number}")

if __name__ == "__main__":
    search_document_for_signatures()
```

## search {#predicate}

Belgedeki imzaları, mevcut tüm arama seçeneklerini kullanarak arar ve sonuçları belirtilen koşula göre filtreler.

- More about search electronic signatures in a documents using GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document
- More about electronic signatures search dependent on eSign type: https://docs.groupdocs.com/display/signaturenet/Searching

```python
def search(self, predicate):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| predicate | `Func[BaseSignature, bool]` | Callable[[BaseSignature], bool] – bir `BaseSignature` alan ve imzayı tutmak için `True`, atmak için `False` döndüren bir işlev. |

**Returns:** list[BaseSignature]: A list of `BaseSignature` instances that satisfy the provided predicate.

### Örnek

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def is_text_signature(sig):
    return hasattr(sig, "text") and sig.text.startswith("Invoice")

with Signature("signed.pdf") as signature:
    # Metin imzalarını ara ve özel bir koşulla filtrele
    result = signature.search([TextSearchOptions()], predicate=is_text_signature)
    for found in result.signatures:
        print(f"Found text signature: {found.text} on page {found.page_number}")
```

### Ayrıca Bakınız
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
