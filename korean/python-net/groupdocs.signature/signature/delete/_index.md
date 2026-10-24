---
title: "delete 메서드"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "지정된 BaseSignature를 문서에서 삭제합니다."
type: docs
url: /ko/python-net/groupdocs.signature/signature/delete/
is_root: false
weight: 1010
---


## delete {#signature}

문서에서 지정된 [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)을 삭제합니다.

자세히 보기:
- More about how to delete electronic signature from document in C#: <https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents>
- Advanced use cases of deleting document eSignatures: <https://docs.groupdocs.com/display/signaturenet/Deleting>

```python
def delete(self, signature):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| signature | `BaseSignature` | 문서에서 제거될 BaseSignature 객체. |

**Returns:** bool: True if the operation was successful, otherwise False.

### 예시

```python
import shutil
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def delete_first_text_signature():
    # delete()는 열린 문서에 변경 사항을 저장하므로 복사본에서 작업하십시오.
    shutil.copy("signed.docx", "text_signature_deleted.docx")
    with Signature("text_signature_deleted.docx") as signature:
        options = TextSearchOptions()
        options.skip_external = True
        signatures = signature.search([options]).signatures
        if not signatures:
            return
        if signature.delete(signatures[0]):
            print("Signature deleted")
```

## delete {#signatures}

문서에서 제공된 서명 목록을 삭제합니다.

- More about how to delete electronic signature from document in C#: [How to delete eSignature from document with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
- Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

```python
def delete(self, signatures):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| signatures | `List[BaseSignature]` | 문서에서 제거할 서명 목록. |

**Returns:** DeleteResult: Result containing lists of successfully deleted signatures and those that failed.

### 예시

```python
import shutil
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def delete_text_signature():
    # delete()가 열린 문서에 변경 사항을 저장하므로 복사본에서 작업하십시오.
    shutil.copy("signed.docx", "text_signature_deleted.docx")

    with Signature("text_signature_deleted.docx") as signature:
        options = TextSearchOptions()
        options.skip_external = True
        signatures = signature.search([options]).signatures
        print(f"Found {len(signatures)} text signature(s)")
        if not signatures:
            return

        # 첫 번째로 발견된 서명을 삭제합니다.
        if signature.delete([signatures[0]]):
            print("Signature deleted successfully")
        else:
            print("Signature could not be deleted")
```

## delete {#signature_type}

문서에서 지정된 유형의 서명을 삭제합니다.

`Sign` 메서드로 추가되고 서명으로 표시된 ([`BaseSignature.IsSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/is_signature/)) 서명만 삭제됩니다. 지원되는 서명 유형은 텍스트, 이미지, 디지털, 바코드 및 QR‑Code입니다.

```python
def delete(self, signature_type):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| signature_type | `SignatureType` | 문서에서 제거될 서명의 유형. |

**Returns:** DeleteResult: Contains lists of successfully deleted signatures and those that failed to delete.

| 발생 | 설명 |
| :- | :- |
| `Remarks` | - 자세히 알아보기: - C#에서 문서의 전자 서명을 삭제하는 방법에 대한 자세한 내용: https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+type/ - 문서 eSignature 삭제에 대한 고급 사용 사례: https://docs.groupdocs.com/display/signaturenet/Deleting |

## delete {#signature_types}

문서에서 지정된 `SignatureType` 목록의 서명을 삭제합니다.

`Sign` 메서드로 추가되고 서명으로 표시된 ([`BaseSignature.is_signature`](/signature/python-net/groupdocs.signature.domain/basesignature/is_signature/)) 서명만 삭제됩니다. 지원되는 서명 유형은 텍스트, 이미지, 디지털, 바코드 및 QR‑Code입니다.

자세히 알아보기
- More about how to delete electronic signature from document in C#: <https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+types/>
- Advanced use cases of deleting document eSignatures: <https://docs.groupdocs.com/display/signaturenet/Deleting>

```python
def delete(self, signature_types):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| signature_types | `List[SignatureType]` | 문서에서 제거될 서명 유형 목록. |

**Returns:** `DeleteResult` with list of successfully deleted signatures and failed ones.

## delete {#signature_id}

문서에서 특정 서명 Id로 서명을 삭제합니다.

자세히 보기:

- More about how to delete electronic signature from document in C#: https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents
- Advanced use cases of deleting document eSignatures: https://docs.groupdocs.com/display/signaturenet/Deleting

```python
def delete(self, signature_id):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| signature_id | `str` | 문서에서 제거될 서명의 Id. |

**Returns:** bool: True if the operation was successful.

## delete {#signature_ids}

문서에서 지정된 서명을 삭제합니다.

자세히 보기:
- More about how to delete electronic signature from document in C#: https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents
- Advanced use cases of deleting document eSignatures: https://docs.groupdocs.com/display/signaturenet/Deleting

```python
def delete(self, signature_ids):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| signature_ids | `List[str]` | 문서에서 제거될 서명의 식별자 목록. |

**Returns:** DeleteResult: `DeleteResult` with lists of successfully deleted signatures and failed ones.

### 예시

```python
import shutil
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def delete_text_signature():
    # delete()가 열린 문서에 변경 사항을 저장하므로 복사본에서 작업하십시오.
    shutil.copy("signed.docx", "text_signature_deleted.docx")

    with Signature("text_signature_deleted.docx") as signature:
        options = TextSearchOptions()
        options.skip_external = True
        signatures = signature.search([options]).signatures
        if not signatures:
            return

        text_signature = signatures[0]
        result = signature.delete([text_signature.id])
        if result.successful:
            print(f"Deleted text signature '{text_signature.text}'")
        else:
            print(f"Failed to delete text signature '{text_signature.text}'")
```

### 또 보기
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
