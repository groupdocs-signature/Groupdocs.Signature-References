---
title: "verify मेथड"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "दिए गए VerifyOptions डेटा के साथ दस्तावेज़ हस्ताक्षरों को सत्यापित करता है।"
type: docs
url: /hi/python-net/groupdocs.signature/signature/verify/
is_root: false
weight: 1270
---


## verify {#verify_options}

दिए गए VerifyOptions डेटा के साथ दस्तावेज़ हस्ताक्षरों को सत्यापित करता है।

GroupDocs.Signature का उपयोग करके इलेक्ट्रॉनिक रूप से हस्ताक्षरित दस्तावेज़ों के सत्यापन के बारे में अधिक जानकारी:
- [How to verify document is electronically signed in C#](https://docs.groupdocs.com/display/signaturenet/Verify+document+for+signatures)

```python
def verify(self, verify_options):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| verify_options | `VerifyOptions` | हस्ताक्षर सत्यापन विकल्प। |

**Returns:** VerificationResult: Result of the verification. The `is_valid` property is True if verification succeeded.

### उदाहरण

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextVerifyOptions

def verify_text_signature():
    with Signature("signed.pdf") as signature:
        options = TextVerifyOptions("John Smith")
        result = signature.verify(options)
        print(f"Document is signed by John Smith: {result.is_valid}")

if __name__ == "__main__":
    verify_text_signature()
```

## verify {#verify_options-predicate}

प्रदान किए गए सत्यापन विकल्पों का उपयोग करके दस्तावेज़ हस्ताक्षरों को सत्यापित करता है और निर्दिष्ट प्रेडिकेट के आधार पर परिणामों को फ़िल्टर करता है।

और अधिक जानें

- More about electronically signed documents verification using GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Verify+document+for+signatures

```python
def verify(self, verify_options, predicate):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| verify_options | `VerifyOptions` | हस्ताक्षर सत्यापन विकल्प। |
| predicate | `Func[BaseSignature, bool]` | फ़िल्टर प्रेडिकेट जो निर्धारित करता है कि कौन से हस्ताक्षर सत्यापित किए जाने चाहिए। |

**Returns:** list[BaseSignature]: Instances that satisfy the provided predicate.

### उदाहरण

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextVerifyOptions

def verify_text_signature():
    with Signature("signed.pdf") as signature:
        options = TextVerifyOptions("John Smith")
        result = signature.verify(options, lambda s: True)
        print(f"Document is signed by John Smith: {result.is_valid}")

if __name__ == "__main__":
    verify_text_signature()
```

## verify {#verify_options_list}

VerifyOptions डेटा की सूची के साथ दस्तावेज़ हस्ताक्षरों को सत्यापित करता है।

GroupDocs.Signature का उपयोग करके इलेक्ट्रॉनिक रूप से हस्ताक्षरित दस्तावेज़ों के सत्यापन के बारे में अधिक जानकारी: [C# में दस्तावेज़ को इलेक्ट्रॉनिक रूप से हस्ताक्षरित कैसे सत्यापित करें](https://docs.groupdocs.com/display/signaturenet/Verify+document+for+signatures).

```python
def verify(self, verify_options_list):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| verify_options_list | `List[VerifyOptions]` | हस्ताक्षर सत्यापन विकल्प संग्रह। `GroupDocs.Signature.Options.VerifyOptionsCollection` का उदाहरण। |

**Returns:** VerificationResult: The verification result. The `IsValid` property is True if the verification process was successful.

### उदाहरण

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextVerifyOptions

def verify_text_signature():
    with Signature("signed.pdf") as signature:
        options = TextVerifyOptions("John Smith")
        result = signature.verify(options)
        print(f"Document is signed by John Smith: {result.is_valid}")

if __name__ == "__main__":
    verify_text_signature()
```

## verify {#verify_options_list-predicate}

प्रदान किए गए सत्यापन विकल्पों का उपयोग करके दस्तावेज़ हस्ताक्षरों को सत्यापित करता है और दिए गए प्रेडिकेट के साथ परिणामों को फ़िल्टर करता है।

यह मेथड पहले सत्यापन विकल्पों से मेल खाने वाले हस्ताक्षरों को खोजता है, प्रेडिकेट का उपयोग करके उन्हें फ़िल्टर करता है, और फिर केवल उन फ़िल्टर किए गए हस्ताक्षरों को सत्यापित करता है।

- Learn more: More about electronically signed documents verification using GroupDocs.Signature: How to verify document is electronically signed in C#.

```python
def verify(self, verify_options_list, predicate):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| verify_options_list | `List[VerifyOptions]` | हस्ताक्षर सत्यापन विकल्प संग्रह। |
| predicate | `Func[BaseSignature, bool]` | फ़िल्टर प्रेडिकेट जो निर्धारित करता है कि कौन से हस्ताक्षर सत्यापित किए जाने चाहिए। |

**Returns:** list[BaseSignature]: List of signatures that satisfy the provided predicate.

### उदाहरण

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextVerifyOptions

def verify_text_signature():
    with Signature("signed.pdf") as signature:
        options = TextVerifyOptions("John Smith")
        result = signature.verify([options], lambda s: s.text == "John Smith")
        print(f"Document is signed by John Smith: {result[0].is_valid}")

if __name__ == "__main__":
    verify_text_signature()
```

### संबंधित देखें
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
