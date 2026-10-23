---
title: "__init__ कंस्ट्रक्टर"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "Padding क्लास का नया इंस्टेंस शून्य मानों के साथ आरंभ करता है।"
type: docs
url: /hi/python-net/groupdocs.signature.domain/padding/__init__/
is_root: false
weight: 10
---


## __init__

Padding क्लास का नया इंस्टेंस शून्य मानों के साथ आरंभ करता है।

```python
def __init__(self):
    ...
```

### उदाहरण

```python
from groupdocs.signature.domain import Padding

# डिफ़ॉल्ट (शून्य) मानों के साथ एक पैडिंग ऑब्जेक्ट बनाएं
default_padding = Padding()
```

## __init__ {#all}

Padding क्लास का नया इंस्टेंस सभी किनारों के लिए प्रदान किए गए पैडिंग आकार का उपयोग करके आरंभ करता है।

```python
def __init__(self, all):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| all | `int` | सभी किनारों के लिए पैडिंग में उपयोग किए जाने वाले माप इकाइयों की संख्या। |

### उदाहरण

```python
# सभी पक्षों पर 5 इकाइयों की समान पैडिंग
margin = Padding(5)
```

## __init__ {#left-right-top-bottom}

Padding क्लास का नया इंस्टेंस प्रदान किए गए पैडिंग आकारों का उपयोग करके आरंभ करता है।

```python
def __init__(self, left, right, top, bottom):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| left | `int` | बाएँ पैडिंग का आकार। |
| right | `int` | दाएँ पैडिंग का आकार। |
| top | `int` | ऊपर पैडिंग का आकार। |
| bottom | `int` | नीचे पैडिंग का आकार। |

### उदाहरण

```python
from groupdocs.signature.domain import Padding

# दाएँ और नीचे ऑफ़सेट के साथ एक पैडिंग बनाएं
margin = Padding(right=40, bottom=60)
```

### संबंधित देखें
* class [`Padding`](/signature/python-net/groupdocs.signature.domain/padding/)
