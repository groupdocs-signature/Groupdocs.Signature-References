---
title: "custom_sign_hash मेथड"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "कस्टम साइनिंग कार्यान्वयन का उपयोग करके दिए गए हैश पर हस्ताक्षर करता है।"
type: docs
url: /hi/python-net/groupdocs.signature.options/icustomsignhash/custom_sign_hash/
is_root: false
weight: 1010
---


## custom_sign_hash {#signable_hash-hash_algorithm-signature_context}

कस्टम साइनिंग कार्यान्वयन का उपयोग करके दिए गए हैश पर हस्ताक्षर करता है।

```python
def custom_sign_hash(self, signable_hash, hash_algorithm, signature_context):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| signable_hash | `list[int]` | हैश मान जिसे हस्ताक्षर किया जाना है। |
| hash_algorithm | `HashAlgorithm` | हैश उत्पन्न करने के लिए उपयोग किया गया हैश एल्गोरिद्म। |
| signature_context | `SignatureContext` | संदर्भ जो अतिरिक्त हस्ताक्षर-संबंधी विकल्प प्रदान करता है। |

**Returns:** bytes: The signed hash as bytes.

### संबंधित देखें
* class [`ICustomSignHash`](/signature/python-net/groupdocs.signature.options/icustomsignhash/)
