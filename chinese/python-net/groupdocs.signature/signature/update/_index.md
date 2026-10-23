---
title: "update 方法"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "更新文档中传入的签名 BaseSignature。"
type: docs
url: /zh/python-net/groupdocs.signature/signature/update/
is_root: false
weight: 1240
---


## update {#signature}

更新文档中传入的签名 BaseSignature。

- More about how to update existing electronic signature properties using GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Update+signatures+in+documents
- More advanced use cases of updating document electronic signatures dependent on signature type: https://docs.groupdocs.com/display/signaturenet/Updating

```python
def update(self, signature):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| signature | `BaseSignature` | 文档中要更新的 Signature 对象。 |

**Returns:** bool: True if operation was successful.

### 示例

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

更新文档中传入的签名 [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)。

- More about how to update existing electronic signature properties using GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Update+signatures+in+documents
- More advanced use cases of updating document electronic signatures dependent on signature type: https://docs.groupdocs.com/display/signaturenet/Updating

```python
def update(self, signatures):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| signatures | `List[BaseSignature]` | 文档中要更新的签名列表。 |

**Returns:** UpdateResult `UpdateResult` with list of successfully updated signatures and failed ones.

### 示例

```python
import shutil
from groupdocs.signature import Signature
from groupdocs.signature.options import BarcodeSearchOptions

def update_barcode_signature():
    # update() 会将更改保存到已打开的文档中，因此请在副本上操作。
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

### 另见
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
