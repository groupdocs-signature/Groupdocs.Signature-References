---
title: "update मेथड"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "दस्तावेज़ में पास किए गए हस्ताक्षर BaseSignature को अपडेट करता है।"
type: docs
url: /hi/python-net/groupdocs.signature/signature/update/
is_root: false
weight: 1240
---


## update {#signature}

दस्तावेज़ में पास किए गए हस्ताक्षर BaseSignature को अपडेट करता है।

- More about how to update existing electronic signature properties using GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Update+signatures+in+documents
- More advanced use cases of updating document electronic signatures dependent on signature type: https://docs.groupdocs.com/display/signaturenet/Updating

```python
def update(self, signature):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| signature | `BaseSignature` | दस्तावेज़ में अपडेट किए जाने वाले Signature ऑब्जेक्ट। |

**Returns:** bool: True if operation was successful.

### उदाहरण

```python
import shutil
from groupdocs.signature import Signature
from groupdocs.signature.options import ImageSearchOptions

shutil.copy("signed.docx", "updated_image_signature.docx")
with Signature("updated_image_signature.docx") as signature:
    options = ImageSearchOptions()
    options.skip_external = True
    img_sig = signature.search([options]).signatures[0]
    img_sig.left = 240
    img_sig.top = 450
    img_sig.width = 150
    img_sig.height = 125

    if signature.update(img_sig):
        print("Image signature updated")
```

## update {#signatures}

दस्तावेज़ में पास किए गए हस्ताक्षर [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) को अपडेट करता है।

- More about how to update existing electronic signature properties using GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Update+signatures+in+documents
- More advanced use cases of updating document electronic signatures dependent on signature type: https://docs.groupdocs.com/display/signaturenet/Updating

```python
def update(self, signatures):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| signatures | `List[BaseSignature]` | दस्तावेज़ में अपडेट करने के लिए हस्ताक्षरों की सूची। |

**Returns:** UpdateResult `UpdateResult` with list of successfully updated signatures and failed ones.

### उदाहरण

```python
import shutil
from groupdocs.signature import Signature
from groupdocs.signature.options import BarcodeSearchOptions

def update_barcode_signature():
    # update() खुले दस्तावेज़ में बदलाव सहेजता है, इसलिए एक कॉपी पर काम करें
    shutil.copy("signed.docx", "updated_barcode_signature.docx")
    with Signature("updated_barcode_signature.docx") as signature:
        options = BarcodeSearchOptions()
        options.skip_external = True
        signatures = signature.search([options]).signatures
        if not signatures:
            return
        barcode = signatures[0]
        barcode.left = 60
        barcode.top = 700
        barcode.width = 320
        barcode.height = 80
        if signature.update(barcode):
            print(f"Barcode '{barcode.text}' moved to ({barcode.left}, {barcode.top})")
```

### संबंधित देखें
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
