---
title: "update Methode"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Aktualisiert die übergebene Signatur BaseSignature im Dokument."
type: docs
url: /de/python-net/groupdocs.signature/signature/update/
is_root: false
weight: 1240
---


## update {#signature}

Aktualisiert die übergebene Signatur BaseSignature im Dokument.

- More about how to update existing electronic signature properties using GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Update+signatures+in+documents
- More advanced use cases of updating document electronic signatures dependent on signature type: https://docs.groupdocs.com/display/signaturenet/Updating

```python
def update(self, signature):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| signature | `BaseSignature` | Signature-Objekt, das im Dokument aktualisiert werden soll. |

**Returns:** bool: True if operation was successful.

### Beispiel

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

Aktualisiert übergebene Signaturen [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) im Dokument.

- More about how to update existing electronic signature properties using GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Update+signatures+in+documents
- More advanced use cases of updating document electronic signatures dependent on signature type: https://docs.groupdocs.com/display/signaturenet/Updating

```python
def update(self, signatures):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| signatures | `List[BaseSignature]` | Liste der Signaturen, die im Dokument aktualisiert werden sollen. |

**Returns:** UpdateResult `UpdateResult` with list of successfully updated signatures and failed ones.

### Beispiel

```python
import shutil
from groupdocs.signature import Signature
from groupdocs.signature.options import BarcodeSearchOptions

def update_barcode_signature():
    # update() speichert Änderungen im geöffneten Dokument, arbeiten Sie also an einer Kopie
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

### Siehe auch
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
