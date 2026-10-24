---
title: "delete メソッド"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "指定された BaseSignature をドキュメントから削除します。"
type: docs
url: /ja/python-net/groupdocs.signature/signature/delete/
is_root: false
weight: 1010
---


## delete {#signature}

指定された [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) をドキュメントから削除します。

詳しくは以下をご覧ください:
- More about how to delete electronic signature from document in C#: <https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents>
- Advanced use cases of deleting document eSignatures: <https://docs.groupdocs.com/display/signaturenet/Deleting>

```python
def delete(self, signature):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| signature | `BaseSignature` | ドキュメントから削除される BaseSignature オブジェクトです。 |

**Returns:** bool: True if the operation was successful, otherwise False.

### 例

```python
import shutil
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def delete_first_text_signature():
    # delete() は開かれたドキュメントに変更を保存するため、コピーで作業してください。
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

提供された署名リストをドキュメントから削除します。

- More about how to delete electronic signature from document in C#: [How to delete eSignature from document with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
- Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

```python
def delete(self, signatures):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| signatures | `List[BaseSignature]` | ドキュメントから削除する署名の一覧です。 |

**Returns:** DeleteResult: Result containing lists of successfully deleted signatures and those that failed.

### 例

```python
import shutil
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def delete_text_signature():
    # delete() が開かれたドキュメントに変更を保存するため、コピーで作業してください。
    shutil.copy("signed.docx", "text_signature_deleted.docx")

    with Signature("text_signature_deleted.docx") as signature:
        options = TextSearchOptions()
        options.skip_external = True
        signatures = signature.search([options]).signatures
        print(f"Found {len(signatures)} text signature(s)")
        if not signatures:
            return

        # 最初に見つかった署名を削除します。
        if signature.delete([signatures[0]]):
            print("Signature deleted successfully")
        else:
            print("Signature could not be deleted")
```

## delete {#signature_type}

指定されたタイプの署名をドキュメントから削除します。

`Sign` メソッドで追加され、署名としてマークされた（[`BaseSignature.IsSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/is_signature/)）署名のみが削除されます。サポートされている署名タイプは Text、Image、Digital、Barcode、QR‑Code です。

```python
def delete(self, signature_type):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| signature_type | `SignatureType` | ドキュメントから削除される署名のタイプです。 |

**Returns:** DeleteResult: Contains lists of successfully deleted signatures and those that failed to delete.

| 例外 | 説明 |
| :- | :- |
| `Remarks` | - 詳細はこちら: - C# でドキュメントから電子署名を削除する方法の詳細: https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+type/ - ドキュメントの eSignature を削除する高度なユースケース: https://docs.groupdocs.com/display/signaturenet/Deleting |

## delete {#signature_types}

指定された `SignatureType` リストの署名をドキュメントから削除します。

`Sign` メソッドで追加され、署名としてマークされた（[`BaseSignature.is_signature`](/signature/python-net/groupdocs.signature.domain/basesignature/is_signature/)）署名のみが削除されます。サポートされている署名タイプは Text、Image、Digital、Barcode、QR‑Code です。

詳細を見る
- More about how to delete electronic signature from document in C#: <https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+types/>
- Advanced use cases of deleting document eSignatures: <https://docs.groupdocs.com/display/signaturenet/Deleting>

```python
def delete(self, signature_types):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| signature_types | `List[SignatureType]` | ドキュメントから削除される署名タイプの一覧です。 |

**Returns:** `DeleteResult` with list of successfully deleted signatures and failed ones.

## delete {#signature_id}

特定の署名 Id によって署名をドキュメントから削除します。

詳しくは以下をご覧ください:

- More about how to delete electronic signature from document in C#: https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents
- Advanced use cases of deleting document eSignatures: https://docs.groupdocs.com/display/signaturenet/Deleting

```python
def delete(self, signature_id):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| signature_id | `str` | ドキュメントから削除される署名の Id です。 |

**Returns:** bool: True if the operation was successful.

## delete {#signature_ids}

指定された署名をドキュメントから削除します。

詳しくは以下をご覧ください:
- More about how to delete electronic signature from document in C#: https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents
- Advanced use cases of deleting document eSignatures: https://docs.groupdocs.com/display/signaturenet/Deleting

```python
def delete(self, signature_ids):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| signature_ids | `List[str]` | ドキュメントから削除される署名の識別子の一覧です。 |

**Returns:** DeleteResult: `DeleteResult` with lists of successfully deleted signatures and failed ones.

### 例

```python
import shutil
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def delete_text_signature():
    # delete() が開かれたドキュメントに変更を保存するため、コピーで作業してください。
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

### 関連項目
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
