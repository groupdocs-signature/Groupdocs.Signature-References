---
title: "delete 方法"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "从文档中删除指定的 BaseSignature。"
type: docs
url: /zh/python-net/groupdocs.signature/signature/delete/
is_root: false
weight: 1010
---


## delete {#signature}

从文档中删除指定的 [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)。

了解更多：
- More about how to delete electronic signature from document in C#: <https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents>
- Advanced use cases of deleting document eSignatures: <https://docs.groupdocs.com/display/signaturenet/Deleting>

```python
def delete(self, signature):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| signature | `BaseSignature` | 文档中要移除的 BaseSignature 对象。 |

**Returns:** bool: True if the operation was successful, otherwise False.

### 示例

```python
import shutil
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def delete_first_text_signature():
    # delete() 会将更改保存到已打开的文档中，因此请在副本上操作。
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

从文档中删除提供的签名列表。

- More about how to delete electronic signature from document in C#: [How to delete eSignature from document with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
- Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

```python
def delete(self, signatures):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| signatures | `List[BaseSignature]` | 文档中要移除的签名列表。 |

**Returns:** DeleteResult: Result containing lists of successfully deleted signatures and those that failed.

### 示例

```python
import shutil
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def delete_text_signature():
    # 请在副本上操作，因为 delete() 会将更改保存到已打开的文档中。
    shutil.copy("signed.docx", "text_signature_deleted.docx")

    with Signature("text_signature_deleted.docx") as signature:
        options = TextSearchOptions()
        options.skip_external = True
        signatures = signature.search([options]).signatures
        print(f"Found {len(signatures)} text signature(s)")
        if not signatures:
            return

        # 删除找到的第一个签名
        if signature.delete([signatures[0]]):
            print("Signature deleted successfully")
        else:
            print("Signature could not be deleted")
```

## delete {#signature_type}

从文档中删除指定类型的签名。

仅会删除通过 `Sign` 方法添加并标记为签名的签名（[`BaseSignature.IsSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/is_signature/)）。支持的签名类型包括文本、图像、数字、条形码和二维码。

```python
def delete(self, signature_type):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| signature_type | `SignatureType` | 文档中要移除的签名类型。 |

**Returns:** DeleteResult: Contains lists of successfully deleted signatures and those that failed to delete.

| 引发 | 描述 |
| :- | :- |
| `Remarks` | - 了解更多： - 有关如何在 C# 中删除文档电子签名的更多信息：https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+type/ - 删除文档电子签名的高级用例：https://docs.groupdocs.com/display/signaturenet/Deleting |

## delete {#signature_types}

从文档中删除指定 `SignatureType` 列表的签名。

仅会删除通过 `Sign` 方法添加并标记为签名的签名（[`BaseSignature.is_signature`](/signature/python-net/groupdocs.signature.domain/basesignature/is_signature/)）。支持的签名类型包括文本、图像、数字、条形码和二维码。

了解更多
- More about how to delete electronic signature from document in C#: <https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+types/>
- Advanced use cases of deleting document eSignatures: <https://docs.groupdocs.com/display/signaturenet/Deleting>

```python
def delete(self, signature_types):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| signature_types | `List[SignatureType]` | 文档中要移除的签名类型列表。 |

**Returns:** `DeleteResult` with list of successfully deleted signatures and failed ones.

## delete {#signature_id}

从文档中根据特定的签名 Id 删除签名。

了解更多：

- More about how to delete electronic signature from document in C#: https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents
- Advanced use cases of deleting document eSignatures: https://docs.groupdocs.com/display/signaturenet/Deleting

```python
def delete(self, signature_id):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| signature_id | `str` | 文档中要移除的签名 Id。 |

**Returns:** bool: True if the operation was successful.

## delete {#signature_ids}

从文档中删除指定的签名。

了解更多：
- More about how to delete electronic signature from document in C#: https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents
- Advanced use cases of deleting document eSignatures: https://docs.groupdocs.com/display/signaturenet/Deleting

```python
def delete(self, signature_ids):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| signature_ids | `List[str]` | 文档中要移除的签名标识符列表。 |

**Returns:** DeleteResult: `DeleteResult` with lists of successfully deleted signatures and failed ones.

### 示例

```python
import shutil
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def delete_text_signature():
    # 请在副本上操作，因为 delete() 会将更改保存到已打开的文档中。
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

### 另见
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
