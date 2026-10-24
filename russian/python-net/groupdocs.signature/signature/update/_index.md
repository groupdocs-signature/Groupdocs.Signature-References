---
title: "метод update"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Обновляет переданную подпись BaseSignature в документе."
type: docs
url: /ru/python-net/groupdocs.signature/signature/update/
is_root: false
weight: 1240
---


## update {#signature}

Обновляет переданную подпись BaseSignature в документе.

- More about how to update existing electronic signature properties using GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Update+signatures+in+documents
- More advanced use cases of updating document electronic signatures dependent on signature type: https://docs.groupdocs.com/display/signaturenet/Updating

```python
def update(self, signature):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| signature | `BaseSignature` | Объект Signature, который будет обновлён в документе. |

**Returns:** bool: True if operation was successful.

### Пример

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

Обновляет переданные подписи [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) в документе.

- More about how to update existing electronic signature properties using GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Update+signatures+in+documents
- More advanced use cases of updating document electronic signatures dependent on signature type: https://docs.groupdocs.com/display/signaturenet/Updating

```python
def update(self, signatures):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| signatures | `List[BaseSignature]` | Список подписей для обновления в документе. |

**Returns:** UpdateResult `UpdateResult` with list of successfully updated signatures and failed ones.

### Пример

```python
import shutil
from groupdocs.signature import Signature
from groupdocs.signature.options import BarcodeSearchOptions

def update_barcode_signature():
    # update() сохраняет изменения в открытом документе, поэтому работайте с копией
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

### См. также
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
