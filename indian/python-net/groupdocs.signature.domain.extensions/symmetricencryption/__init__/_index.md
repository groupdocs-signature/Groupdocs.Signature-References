---
title: "__init__ कंस्ट्रक्टर"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "निर्दिष्ट पैरामीटरों के साथ एक सममित एन्क्रिप्शन एल्गोरिद्म को आरंभ करता है।"
type: docs
url: /hi/python-net/groupdocs.signature.domain.extensions/symmetricencryption/__init__/
is_root: false
weight: 10
---


## __init__ {#algorithm_type-key-salt}

निर्दिष्ट पैरामीटरों के साथ एक सममित एन्क्रिप्शन एल्गोरिद्म को आरंभ करता है।

```python
def __init__(self, algorithm_type, key, salt):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| algorithm_type | `SymmetricAlgorithmType` | सिमेट्रिक एल्गोरिदम प्रकार निर्दिष्ट करें |
| key | `str` | एन्क्रिप्शन कुंजी |
| salt | `str` | एन्क्रिप्शन के लिए पासफ़्रेज़ |

## __init__ {#algorithm_type-key}

डिफ़ॉल्ट पासफ़्रेज़ के साथ एक सममित एन्क्रिप्शन एल्गोरिद्म को आरंभ करता है।

```python
def __init__(self, algorithm_type, key):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| algorithm_type | `SymmetricAlgorithmType` | सिमेट्रिक एल्गोरिदम प्रकार निर्दिष्ट करें। |
| key | `str` | एन्क्रिप्शन कुंजी। |

### संबंधित देखें
* class [`SymmetricEncryption`](/signature/python-net/groupdocs.signature.domain.extensions/symmetricencryption/)
