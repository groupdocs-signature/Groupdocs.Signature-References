---
title: "update methode"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Werkt de meegegeven handtekening BaseSignature bij in het document."
type: docs
url: /nl/python-net/groupdocs.signature/signature/update/
is_root: false
weight: 1240
---


## update {#signature}

Werkt de meegegeven handtekening BaseSignature bij in het document.

- More about how to update existing electronic signature properties using GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Update+signatures+in+documents
- More advanced use cases of updating document electronic signatures dependent on signature type: https://docs.groupdocs.com/display/signaturenet/Updating

```python
def update(self, signature):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| signature | `BaseSignature` | Signature‑object dat moet worden bijgewerkt in het document. |

**Returns:** bool: True if operation was successful.

### Voorbeeld

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

Werkt de meegegeven handtekeningen [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) bij in het document.

- More about how to update existing electronic signature properties using GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Update+signatures+in+documents
- More advanced use cases of updating document electronic signatures dependent on signature type: https://docs.groupdocs.com/display/signaturenet/Updating

```python
def update(self, signatures):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| signatures | `List[BaseSignature]` | Lijst met handtekeningen die moeten worden bijgewerkt in het document. |

**Returns:** UpdateResult `UpdateResult` with list of successfully updated signatures and failed ones.

### Voorbeeld

```python
import shutil
from groupdocs.signature import Signature
from groupdocs.signature.options import BarcodeSearchOptions

def update_barcode_signature():
    # update() slaat wijzigingen op in het geopende document, dus werk op een kopie.
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

### Zie ook
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
