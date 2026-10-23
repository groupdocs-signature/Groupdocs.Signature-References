---
title: "__init__ कंस्ट्रक्टर"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "एक दस्तावेज़ को स्ट्रीम के रूप में प्रदान करके एक नया Signature इंस्टेंस प्रारंभ करता है।"
type: docs
url: /hi/python-net/groupdocs.signature/signature/__init__/
is_root: false
weight: 10
---


## __init__ {#document}

एक दस्तावेज़ को स्ट्रीम के रूप में प्रदान करके एक नया Signature इंस्टेंस प्रारंभ करता है।

- More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: [Developer Guide](https://docs.groupdocs.com/display/signaturenet/Developer+Guide)

```python
def __init__(self, document):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| document | `io.RawIOBase` | दस्तावेज़ सामग्री स्ट्रीम। |

## __init__ {#document-load_options}

एक दस्तावेज़ स्ट्रीम और लोड विकल्पों के साथ एक नया [`Signature`](/signature/python-net/groupdocs.signature/signature/) इंस्टेंस प्रारंभ करता है।

और अधिक जानें

- More about file types supported by GroupDocs.Signature: Document formats supported by GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: Developer Guide (https://docs.groupdocs.com/display/signaturenet/Developer+Guide)
- More about how to open and eSign password-protected documents and document from different storages: Load and eSign documents using GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Loading)

```python
def __init__(self, document, load_options):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| document | `io.RawIOBase` | दस्तावेज़ सामग्री स्ट्रीम। |
| load_options | `LoadOptions` | दस्तावेज़ लोड विकल्प। |

## __init__ {#document-settings}

एक स्ट्रीम द्वारा प्रदान किए गए दस्तावेज़ और वैकल्पिक [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/) के साथ एक नया [`Signature`](/signature/python-net/groupdocs.signature/signature/) इंस्टेंस प्रारंभ करता है।

और अधिक जानें:

- More about file types supported by GroupDocs.Signature: Document formats supported by GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: Developer Guide (https://docs.groupdocs.com/display/signaturenet/Developer+Guide)

```python
def __init__(self, document, settings):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| document | `io.RawIOBase` | दस्तावेज़ सामग्री स्ट्रीम। |
| settings | `SignatureSettings` | हस्ताक्षर सेटिंग्स। |

## __init__ {#document-load_options-settings}

एक दस्तावेज़ स्ट्रीम, लोड विकल्प, और सिग्नेचर सेटिंग्स के साथ एक नया [`Signature`](/signature/python-net/groupdocs.signature/signature/) इंस्टेंस प्रारंभ करता है।

- More about file types supported by GroupDocs.Signature: Document formats supported by GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: Developer Guide (https://docs.groupdocs.com/display/signaturenet/Developer+Guide)
- More about how to open and eSign password-protected documents and document from different storages: Load and eSign documents using GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Loading)

```python
def __init__(self, document, load_options, settings):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| document | `io.RawIOBase` | दस्तावेज़ सामग्री स्ट्रीम। |
| load_options | `LoadOptions` | दस्तावेज़ लोड विकल्प। |
| settings | `SignatureSettings` | हस्ताक्षर सेटिंग्स। |

## __init__ {#file_path}

फ़ाइल पाथ द्वारा प्रदान किए गए दस्तावेज़ के साथ एक नया [`Signature`](/signature/python-net/groupdocs.signature/signature/) इंस्टेंस प्रारंभ करता है।

- More about file types supported by GroupDocs.Signature: Document formats supported by GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: Developer Guide (https://docs.groupdocs.com/display/signaturenet/Developer+Guide)

```python
def __init__(self, file_path):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| file_path | `str` | परिपूर्ण या सापेक्ष फ़ाइल पथ। |

### उदाहरण

```python
from groupdocs.signature import Signature

# हस्ताक्षर, खोज या सत्यापन के लिए दस्तावेज़ खोलें
with Signature("sample.pdf") as signature:
    # हस्ताक्षर ऑब्जेक्ट के साथ काम करें
    pass
```

## __init__ {#file_path-load_options}

फ़ाइल पाथ द्वारा प्रदान किए गए दस्तावेज़ और लोड विकल्पों के साथ एक नया Signature इंस्टेंस प्रारंभ करता है।

- More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: [Developer Guide](https://docs.groupdocs.com/display/signaturenet/Developer+Guide)
- More about how to open and eSign password-protected documents and document from different storages: [Load and eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Loading)

```python
def __init__(self, file_path, load_options):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| file_path | `str` | परिपूर्ण या सापेक्ष फ़ाइल पथ। |
| load_options | `LoadOptions` | दस्तावेज़ लोड विकल्प। |

### उदाहरण

```python
from groupdocs.signature import Signature

with Signature("sample.pdf") as signature:
    # हस्ताक्षर, खोज या सत्यापन संचालन करें
    pass
```

## __init__ {#file_path-settings}

फ़ाइल पाथ द्वारा प्रदान किए गए दस्तावेज़ और वैकल्पिक [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/) के साथ एक नया [`Signature`](/signature/python-net/groupdocs.signature/signature/) इंस्टेंस प्रारंभ करता है।

- More about file types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats
- More about GroupDocs.Signature for .NET features: https://docs.groupdocs.com/display/signaturenet/Developer+Guide

```python
def __init__(self, file_path, settings):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| file_path | `str` | परिपूर्ण या सापेक्ष फ़ाइल पथ। |
| settings | `SignatureSettings` | हस्ताक्षर सेटिंग्स। |

### उदाहरण

```python
from groupdocs.signature import Signature

# हस्ताक्षर या सत्यापन के लिए PDF दस्तावेज़ खोलें
with Signature("sample.pdf") as signature:
    # यहाँ हस्ताक्षर इंस्टेंस का उपयोग करें (जैसे, sign, verify, search)
    pass
```

## __init__ {#file_path-load_options-settings}

फ़ाइल पाथ द्वारा प्रदान किए गए दस्तावेज़, लोड विकल्प, और सिग्नेचर सेटिंग्स के साथ एक नया [`Signature`](/signature/python-net/groupdocs.signature/signature/) इंस्टेंस प्रारंभ करता है।

और अधिक जानें:
- More about file types supported by GroupDocs.Signature: Document formats supported by GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: Developer Guide (https://docs.groupdocs.com/display/signaturenet/Developer+Guide)
- More about how to open and eSign password-protected documents and document from different storages: Load and eSign documents using GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Loading)

```python
def __init__(self, file_path, load_options, settings):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| file_path | `str` | परिपूर्ण या सापेक्ष फ़ाइल पथ। |
| load_options | `LoadOptions` | दस्तावेज़ लोड विकल्प। |
| settings | `SignatureSettings` | हस्ताक्षर सेटिंग्स। |

### उदाहरण

```python
from groupdocs.signature import Signature

with Signature("sample.pdf") as signature:
    # हस्ताक्षर, सत्यापन या खोज संचालन करें
    pass
```

### संबंधित देखें
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
