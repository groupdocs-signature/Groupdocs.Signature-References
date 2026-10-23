---
title: "search मेथड"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "SearchOptions की सूची का उपयोग करके दस्तावेज़ में हस्ताक्षरों की खोज करता है।"
type: docs
url: /hi/python-net/groupdocs.signature/signature/search/
is_root: false
weight: 1140
---


## search {#search_options_list}

एक दस्तावेज़ में हस्ताक्षर खोजता है, एक सूची के [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/) का उपयोग करके।

और अधिक जानें

- More about search electronic signatures in a documents using GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document
- More about electronic signatures search dependent on eSign type: https://docs.groupdocs.com/display/signaturenet/Searching

```python
def search(self, search_options_list):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| search_options_list | `List[SearchOptions]` | खोज विकल्प संग्रह। |

**Returns:** SearchResult: Instance containing the list of found signatures.

### उदाहरण

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

with Signature("signed.pdf") as signature:
    result = signature.search([TextSearchOptions()])
    for found in result.signatures:
        print(f"Text signature '{found.text}' on page {found.page_number}")
```

## search {#search_options_list-predicate}

दस्तावेज़ में प्रदान किए गए खोज विकल्पों का उपयोग करके हस्ताक्षर खोजता है और निर्दिष्ट प्रेडिकेट के आधार पर परिणामों को फ़िल्टर करता है।

और अधिक जानें:
- More about search electronic signatures in a documents using GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document
- More about electronic signatures search dependent on eSign type: https://docs.groupdocs.com/display/signaturenet/Searching

```python
def search(self, search_options_list, predicate):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| search_options_list | `List[SearchOptions]` | हस्ताक्षरों की खोज के मानदंड को परिभाषित करने वाले `SearchOptions` इंस्टेंस की सूची। |
| predicate | `Func[BaseSignature, bool]` | पाए गए हस्ताक्षरों की सूची पर लागू करने के लिए फ़िल्टर प्रेडिकेट। |

**Returns:** SearchResult: A `SearchResult` containing the signatures that match the specified search options and satisfy the predicate.

### उदाहरण

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def search_document_for_signatures():
    with Signature("signed.pdf") as signature:
        # हर पृष्ठ पर टेक्स्ट सिग्नेचर खोजें
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

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| search_options | `SearchOptions` |  |

## search {#signature_type}

```python
def search(self, signature_type):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| signature_type | `SignatureType` |  |

## search {#signature_types}

`SignatureType` मान द्वारा दस्तावेज़ में निर्दिष्ट हस्ताक्षर प्रकार खोजता है।

- More about search electronic signatures in a documents using GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document
- More about electronic signatures search dependent on eSign type: https://docs.groupdocs.com/display/signaturenet/Searching

```python
def search(self, signature_types):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| signature_types | `list[SignatureType]` | खोजने के लिए एक या कई प्रकार के हस्ताक्षर। |

**Returns:** SearchResult: Instance containing the list of found signatures.

### उदाहरण

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def search_document_for_signatures():
    with Signature("signed.pdf") as signature:
        # हर पृष्ठ पर टेक्स्ट सिग्नेचर खोजें
        result = signature.search([TextSearchOptions()])
        for found in result.signatures:
            print(f"Text signature '{found.text}' on page {found.page_number}")

if __name__ == "__main__":
    search_document_for_signatures()
```

## search {#predicate}

दस्तावेज़ में सभी उपलब्ध खोज विकल्पों का उपयोग करके हस्ताक्षर खोजता है और निर्दिष्ट प्रेडिकेट के आधार पर परिणामों को फ़िल्टर करता है।

- More about search electronic signatures in a documents using GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document
- More about electronic signatures search dependent on eSign type: https://docs.groupdocs.com/display/signaturenet/Searching

```python
def search(self, predicate):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| predicate | `Func[BaseSignature, bool]` | Callable[[BaseSignature], bool] – एक फ़ंक्शन जो `BaseSignature` प्राप्त करता है और हस्ताक्षर को रखने के लिए `True` या त्यागने के लिए `False` लौटाता है। |

**Returns:** list[BaseSignature]: A list of `BaseSignature` instances that satisfy the provided predicate.

### उदाहरण

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def is_text_signature(sig):
    return hasattr(sig, "text") and sig.text.startswith("Invoice")

with Signature("signed.pdf") as signature:
    # पाठ हस्ताक्षरों की खोज करें और उन्हें एक कस्टम प्रेडिकेट से फ़िल्टर करें
    result = signature.search([TextSearchOptions()], predicate=is_text_signature)
    for found in result.signatures:
        print(f"Found text signature: {found.text} on page {found.page_number}")
```

### संबंधित देखें
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
