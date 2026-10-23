---
title: "add_range विधि"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "मेटाडेटा हस्ताक्षरों का संग्रह जोड़ता है।"
type: docs
url: /hi/python-net/groupdocs.signature.domain/metadatasignaturecollection/add_range/
is_root: false
weight: 1030
---


## add_range {#signatures}

मेटाडेटा हस्ताक्षरों का संग्रह जोड़ता है।

```python
def add_range(self, signatures):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| signatures | `Iterable[MetadataSignature]` | जोड़ने के लिए हस्ताक्षरों का संग्रह। |

### उदाहरण

```python
from datetime import datetime
from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSignOptions
from groupdocs.signature.domain import WordProcessingMetadataSignature

def sign_docx():
    with Signature("sample.docx") as signature:
        options = MetadataSignOptions()
        signatures = [
            WordProcessingMetadataSignature("Author", "Mr.Scherlock Holmes"),
            WordProcessingMetadataSignature("DateCreated", datetime.now()),
            WordProcessingMetadataSignature("DocumentId", 123456),
            WordProcessingMetadataSignature("SignatureId", 123.456),
        ]
        options.signatures.add_range(signatures)
        result = signature.sign("signed.docx", options)
        print(f"Signed with {len(result.succeeded)} metadata signature(s):")
        for item in result.succeeded:
            print(f"  {item.name}")
```

### संबंधित देखें
* class [`MetadataSignatureCollection`](/signature/python-net/groupdocs.signature.domain/metadatasignaturecollection/)
