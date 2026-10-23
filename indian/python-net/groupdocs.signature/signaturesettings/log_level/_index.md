---
title: "log_level प्रॉपर्टी"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "लॉग लेवल फ़्लैग्स जो निर्धारित करते हैं कि कौन से प्रकार के संदेश SignatureSettings.Logger को पास किए जाते हैं।"
type: docs
url: /hi/python-net/groupdocs.signature/signaturesettings/log_level/
is_root: false
weight: 2030
---


## log_level property

लॉग स्तर के फ़्लैग जो निर्धारित करते हैं कि कौन से प्रकार के संदेश [`SignatureSettings.Logger`](/signature/python-net/groupdocs.signature/signaturesettings/logger/) को पास किए जाते हैं।

यह मान `LogLevel` फ़्लैग्स का सेट है जिसे संयोजित किया जा सकता है, उदाहरण के लिए `LogLevel.Error | LogLevel.Warning`। `LogLevel.None` कुछ भी लॉग नहीं करता। डिफ़ॉल्ट `LogLevel.All` है: त्रुटियाँ, चेतावनियाँ और ट्रेस।

### Definition:
```python
@property
def log_level(self):
    ...
@log_level.setter
def log_level(self, value):
    ...
```

### संबंधित देखें
* class [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/)
