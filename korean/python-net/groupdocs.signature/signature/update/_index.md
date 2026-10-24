---
title: "update 메서드"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "문서에서 전달된 서명 BaseSignature를 업데이트합니다."
type: docs
url: /ko/python-net/groupdocs.signature/signature/update/
is_root: false
weight: 1240
---


## update {#signature}

문서에서 전달된 서명 BaseSignature를 업데이트합니다.

- More about how to update existing electronic signature properties using GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Update+signatures+in+documents
- More advanced use cases of updating document electronic signatures dependent on signature type: https://docs.groupdocs.com/display/signaturenet/Updating

```python
def update(self, signature):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| signature | `BaseSignature` | 문서에서 업데이트될 Signature 객체. |

**Returns:** bool: True if operation was successful.

### 예시

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

문서에서 전달된 서명 [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)을 업데이트합니다.

- More about how to update existing electronic signature properties using GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Update+signatures+in+documents
- More advanced use cases of updating document electronic signatures dependent on signature type: https://docs.groupdocs.com/display/signaturenet/Updating

```python
def update(self, signatures):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| signatures | `List[BaseSignature]` | 문서에서 업데이트할 서명 목록. |

**Returns:** UpdateResult `UpdateResult` with list of successfully updated signatures and failed ones.

### 예시

```python
import shutil
from groupdocs.signature import Signature
from groupdocs.signature.options import BarcodeSearchOptions

def update_barcode_signature():
    # update()는 열린 문서에 변경 사항을 저장하므로 복사본에서 작업하십시오.
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

### 또 보기
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
