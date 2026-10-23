---
title: "reference प्रॉपर्टी"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "लेनदार भुगतान संदर्भ।"
type: docs
url: /hi/python-net/groupdocs.signature.domain.extensions/swissqr/reference/
is_root: false
weight: 2070
---


## reference property

लेनदार भुगतान संदर्भ।

SwissQR IBANs (CHxx30000xxxxxx से CHxx31999xxxxx तक की रेंज वाले IBAN) के लिए यह अनिवार्य है। यदि निर्दिष्ट किया गया है, तो रेफ़रेंस वैध SwissQR रेफ़रेंस (ISR रेफ़रेंस फ़ॉर्म के अनुरूप) या ISO 11649 (\"RFxxxx\") के अनुसार वैध लेनदार रेफ़रेंस होना चाहिए। दोनों में फ़ॉर्मेटिंग के लिए स्पेस हो सकते हैं।

### Definition:
```python
@property
def reference(self):
    ...
@reference.setter
def reference(self, value):
    ...
```

### संबंधित देखें
* class [`SwissQR`](/signature/python-net/groupdocs.signature.domain.extensions/swissqr/)
