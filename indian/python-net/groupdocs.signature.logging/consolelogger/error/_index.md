---
title: "error मेथड"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "कंसोल में एक त्रुटि संदेश लिखता है।"
type: docs
url: /hi/python-net/groupdocs.signature.logging/consolelogger/error/
is_root: false
weight: 1010
---


## error {#message-ex}

कंसोल में एक त्रुटि संदेश लिखता है।

Error लॉग संदेश एप्लिकेशन प्रवाह में अपरिवर्तनीय घटनाओं के बारे में जानकारी प्रदान करते हैं।

```python
def error(self, message, ex):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| message | `str` | error संदेश। |
| ex | `Exception` | अपवाद। |

| उठाता है | विवरण |
| :- | :- |
| `ValueError` | जब `ex` None हो। |

### संबंधित देखें
* class [`ConsoleLogger`](/signature/python-net/groupdocs.signature.logging/consolelogger/)
