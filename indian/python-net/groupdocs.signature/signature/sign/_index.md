---
title: "sign मेथड"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "दस्तावेज़ को SignOptions के साथ साइन करता है और परिणाम को स्ट्रीम में सहेजता है।"
type: docs
url: /hi/python-net/groupdocs.signature/signature/sign/
is_root: false
weight: 1190
---


## sign {#document-sign_options}

दस्तावेज़ पर [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) के साथ हस्ताक्षर करता है और परिणाम को एक स्ट्रीम में सहेजता है।

```python
def sign(self, document, sign_options):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| document | `io.RawIOBase` | आउटपुट दस्तावेज़ स्ट्रीम। |
| sign_options | `SignOptions` | हस्ताक्षर विकल्प। |

**Returns:** SignResult: Instance containing list of newly created signatures.

टिप्पणियाँ:
- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing

### उदाहरण

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

def sign_pdf():
    with Signature("sample.pdf") as signature:
        options = TextSignOptions("John Smith")
        options.left = 100
        options.top = 100
        result = signature.sign("signed_sample.pdf", options)
        print(f"Signatures added: {len(result.succeeded)}")
```

## sign {#document-sign_options-save_options}

दस्तावेज़ पर [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) के साथ हस्ताक्षर करता है और पूर्वनिर्धारित [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/) का उपयोग करके परिणाम को एक स्ट्रीम में सहेजता है।

और अधिक जानें
- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing
- More about how save electronically signed documents and customize saving process: https://docs.groupdocs.com/display/signaturenet/Saving

```python
def sign(self, document, sign_options, save_options):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| document | `io.RawIOBase` | आउटपुट दस्तावेज़ स्ट्रीम। |
| sign_options | `SignOptions` | हस्ताक्षर विकल्प। |
| save_options | `SaveOptions` | सेव विकल्प। |

**Returns:** SignResult: Instance with list of newly created signatures.

## sign {#document-sign_options_list}

दस्तावेज़ पर [`SignOptions`] की एक संग्रह के साथ हस्ताक्षर करता है और परिणाम को एक स्ट्रीम में सहेजता है।

और अधिक जानें

- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing

```python
def sign(self, document, sign_options_list):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| document | `io.RawIOBase` | आउटपुट दस्तावेज़ स्ट्रीम। |
| sign_options_list | `List[SignOptions]` | हस्ताक्षर विकल्पों की सूची। |

**Returns:** SignResult: Instance with list of newly created signatures.

## sign {#document-sign_options_list-save_options}

दस्तावेज़ पर [`SignOptions`] की एक संग्रह के साथ हस्ताक्षर करता है और पूर्वनिर्धारित [`SaveOptions`] का उपयोग करके परिणाम को एक स्ट्रीम में सहेजता है।

```python
def sign(self, document, sign_options_list, save_options):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| document | `io.RawIOBase` | आउटपुट दस्तावेज़ स्ट्रीम। |
| sign_options_list | `List[SignOptions]` | हस्ताक्षर विकल्पों की सूची। |
| save_options | `SaveOptions` | सेव विकल्प। |

**Returns:** SignResult: Instance containing the list of newly created signatures.

टिप्पणियाँ:
- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing
- More about how to save electronically signed documents and customize the saving process: https://docs.groupdocs.com/display/signaturenet/Saving

### उदाहरण

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

def sign_pdf_with_text_signature():
    with Signature("sample.pdf") as signature:
        options = TextSignOptions("John Smith")
        options.left = 100
        options.top = 100

        # साइन करें और परिणाम को नई फ़ाइल में सहेजें; स्रोत अपरिवर्तित रहता है
        result = signature.sign("signed_sample.pdf", options)
        print(f"Signatures added: {len(result.succeeded)}")
```

## sign {#file_path-sign_options}

दस्तावेज़ पर SignOptions के साथ हस्ताक्षर करता है और परिणाम को निर्दिष्ट फ़ाइल पथ पर सहेजता है।

और अधिक जानें

- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing

```python
def sign(self, file_path, sign_options):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| file_path | `str` | आउटपुट फ़ाइल पथ। |
| sign_options | `SignOptions` | हस्ताक्षर विकल्प। |

**Returns:** SignResult: Instance of SignResult with list of newly created signatures.

### उदाहरण

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

def sign_pdf_with_text_signature():
    with Signature("sample.pdf") as signature:
        options = TextSignOptions("John Smith")
        options.left = 100
        options.top = 100
        result = signature.sign("signed_sample.pdf", options)
        print(f"Signatures added: {len(result.succeeded)}")
```

## sign {#file_path-sign_options-save_options}

दस्तावेज़ पर [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) के साथ हस्ताक्षर करता है और पूर्वनिर्धारित [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/) के साथ परिणाम को निर्दिष्ट फ़ाइल पथ पर सहेजता है।

- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing
- More about how save electronically signed documents and customize saving process: https://docs.groupdocs.com/display/signaturenet/Saving

```python
def sign(self, file_path, sign_options, save_options):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| file_path | `str` | आउटपुट फ़ाइल पथ। |
| sign_options | `SignOptions` | हस्ताक्षर विकल्प। |
| save_options | `SaveOptions` | सेव विकल्प। |

**Returns:** SignResult: Instance with list of newly created signatures.

### उदाहरण

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

def sign_pdf_with_text_signature():
    # दस्तावेज़ खोलें; with-block समाप्त होने पर फ़ाइल को रिलीज़ करता है
    with Signature("sample.pdf") as signature:
        # पहले पृष्ठ के बाएँ और ऊपर किनारों से 100 पिक्सेल दूर एक टेक्स्ट सिग्नेचर
        options = TextSignOptions("John Smith")
        options.left = 100
        options.top = 100

        # साइन करें और परिणाम को नई फ़ाइल में सहेजें; स्रोत अपरिवर्तित रहता है
        result = signature.sign("signed_sample.pdf", options)
        print(f"Signatures added: {len(result.succeeded)}")
```

## sign {#file_path-sign_options_list}

दस्तावेज़ पर [`SignOptions`] की संग्रह के साथ हस्ताक्षर करता है और परिणाम को निर्दिष्ट फ़ाइल पथ पर सहेजता है।

और अधिक जानें:
- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing

```python
def sign(self, file_path, sign_options_list):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| file_path | `str` | आउटपुट फ़ाइल पथ। |
| sign_options_list | `List[SignOptions]` | हस्ताक्षर विकल्पों की सूची। |

**Returns:** SignResult: Instance with list of newly created signatures.

### उदाहरण

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

with Signature("sample.pdf") as signature:
    options = TextSignOptions("John Smith")
    options.left = 100
    options.top = 100
    result = signature.sign("signed_sample.pdf", options)
    print(f"Signatures added: {len(result.succeeded)}")
```

## sign {#file_path-sign_options_list-save_options}

दस्तावेज़ पर [`SignOptions`] की एक संग्रह के साथ हस्ताक्षर करता है और पूर्वनिर्धारित [`SaveOptions`] का उपयोग करके परिणाम को निर्दिष्ट फ़ाइल पथ पर सहेजता है।

और अधिक जानें:
- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing
- More about how save electronically signed documents and customize saving process: https://docs.groupdocs.com/display/signaturenet/Saving

```python
def sign(self, file_path, sign_options_list, save_options):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| file_path | `str` | आउटपुट फ़ाइल पथ। |
| sign_options_list | `List[SignOptions]` | हस्ताक्षर विकल्पों की सूची। |
| save_options | `SaveOptions` | सेव विकल्प। |

**Returns:** SignResult: Instance with list of newly created signatures.

### उदाहरण

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

with Signature("sample.pdf") as signature:
    options = TextSignOptions("John Smith")
    result = signature.sign("signed_sample.pdf", [options])
    print(f"Signatures added: {len(result.succeeded)}")
```

### संबंधित देखें
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
