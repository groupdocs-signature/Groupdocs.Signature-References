---
title: "método update"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Actualiza la BaseSignature de firma pasada en el documento."
type: docs
url: /es/python-net/groupdocs.signature/signature/update/
is_root: false
weight: 1240
---


## update {#signature}

Actualiza la BaseSignature de firma pasada en el documento.

- More about how to update existing electronic signature properties using GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Update+signatures+in+documents
- More advanced use cases of updating document electronic signatures dependent on signature type: https://docs.groupdocs.com/display/signaturenet/Updating

```python
def update(self, signature):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| signature | `BaseSignature` | Objeto Signature que se actualizará en el documento. |

**Returns:** bool: True if operation was successful.

### Ejemplo

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

Actualiza las firmas [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) pasadas en el documento.

- More about how to update existing electronic signature properties using GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Update+signatures+in+documents
- More advanced use cases of updating document electronic signatures dependent on signature type: https://docs.groupdocs.com/display/signaturenet/Updating

```python
def update(self, signatures):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| signatures | `List[BaseSignature]` | Lista de firmas para actualizar en el documento. |

**Returns:** UpdateResult `UpdateResult` with list of successfully updated signatures and failed ones.

### Ejemplo

```python
import shutil
from groupdocs.signature import Signature
from groupdocs.signature.options import BarcodeSearchOptions

def update_barcode_signature():
    # update() guarda los cambios en el documento abierto, así que trabaja sobre una copia
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

### Ver también
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
