---
title: "طريقة search"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "يبحث عن التوقيعات في مستند باستخدام قائمة من SearchOptions."
type: docs
url: /ar/python-net/groupdocs.signature/signature/search/
is_root: false
weight: 1140
---


## search {#search_options_list}

يبحث عن التوقيعات في مستند باستخدام قائمة من [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/).

اعرف المزيد

- More about search electronic signatures in a documents using GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document
- More about electronic signatures search dependent on eSign type: https://docs.groupdocs.com/display/signaturenet/Searching

```python
def search(self, search_options_list):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| search_options_list | `List[SearchOptions]` | مجموعة خيارات البحث. |

**Returns:** SearchResult: Instance containing the list of found signatures.

### مثال

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

with Signature("signed.pdf") as signature:
    result = signature.search([TextSearchOptions()])
    for found in result.signatures:
        print(f"Text signature '{found.text}' on page {found.page_number}")
```

## search {#search_options_list-predicate}

يبحث عن التوقيعات في المستند باستخدام خيارات البحث المقدمة ويصفي النتائج بناءً على الشرط المحدد.

تعرف على المزيد:
- More about search electronic signatures in a documents using GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document
- More about electronic signatures search dependent on eSign type: https://docs.groupdocs.com/display/signaturenet/Searching

```python
def search(self, search_options_list, predicate):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| search_options_list | `List[SearchOptions]` | قائمة من كائنات `SearchOptions` التي تحدد المعايير للبحث عن التوقيعات. |
| predicate | `Func[BaseSignature, bool]` | دالة التصفية لتطبيقها على قائمة التوقيعات التي تم العثور عليها. |

**Returns:** SearchResult: A `SearchResult` containing the signatures that match the specified search options and satisfy the predicate.

### مثال

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def search_document_for_signatures():
    with Signature("signed.pdf") as signature:
        # ابحث عن توقيعات نصية في كل صفحة
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

| معامل | نوع | الوصف |
| :- | :- | :- |
| search_options | `SearchOptions` |  |

## search {#signature_type}

```python
def search(self, signature_type):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| signature_type | `SignatureType` |  |

## search {#signature_types}

يبحث عن أنواع التوقيع المحددة في المستند بقيمة `SignatureType`.

- More about search electronic signatures in a documents using GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document
- More about electronic signatures search dependent on eSign type: https://docs.groupdocs.com/display/signaturenet/Searching

```python
def search(self, signature_types):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| signature_types | `list[SignatureType]` | نوع أو عدة أنواع من التوقيعات للعثور عليها. |

**Returns:** SearchResult: Instance containing the list of found signatures.

### مثال

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def search_document_for_signatures():
    with Signature("signed.pdf") as signature:
        # ابحث عن توقيعات نصية في كل صفحة
        result = signature.search([TextSearchOptions()])
        for found in result.signatures:
            print(f"Text signature '{found.text}' on page {found.page_number}")

if __name__ == "__main__":
    search_document_for_signatures()
```

## search {#predicate}

يبحث عن التوقيعات في المستند باستخدام جميع خيارات البحث المتاحة ويصفي النتائج بناءً على الشرط المحدد.

- More about search electronic signatures in a documents using GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document
- More about electronic signatures search dependent on eSign type: https://docs.groupdocs.com/display/signaturenet/Searching

```python
def search(self, predicate):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| predicate | `Func[BaseSignature, bool]` | Callable[[BaseSignature], bool] – دالة تستقبل `BaseSignature` وتعيد `True` للاحتفاظ بالتوقيع أو `False` لتجاهله. |

**Returns:** list[BaseSignature]: A list of `BaseSignature` instances that satisfy the provided predicate.

### مثال

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def is_text_signature(sig):
    return hasattr(sig, "text") and sig.text.startswith("Invoice")

with Signature("signed.pdf") as signature:
    # ابحث عن توقيعات النص وقم بتصفيةها باستخدام دالة مخصصة.
    result = signature.search([TextSearchOptions()], predicate=is_text_signature)
    for found in result.signatures:
        print(f"Found text signature: {found.text} on page {found.page_number}")
```

### انظر أيضًا
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
