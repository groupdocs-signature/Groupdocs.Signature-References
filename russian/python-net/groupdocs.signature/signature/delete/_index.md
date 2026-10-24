---
title: "метод delete"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Удаляет указанный BaseSignature из документа."
type: docs
url: /ru/python-net/groupdocs.signature/signature/delete/
is_root: false
weight: 1010
---


## delete {#signature}

Удаляет указанную [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) из документа.

Узнать больше:
- More about how to delete electronic signature from document in C#: <https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents>
- Advanced use cases of deleting document eSignatures: <https://docs.groupdocs.com/display/signaturenet/Deleting>

```python
def delete(self, signature):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| signature | `BaseSignature` | Объект BaseSignature, который будет удалён из документа. |

**Returns:** bool: True if the operation was successful, otherwise False.

### Пример

```python
import shutil
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def delete_first_text_signature():
    # delete() сохраняет изменения в открытом документе, поэтому работайте с копией.
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

Удаляет предоставленный список подписей из документа.

- More about how to delete electronic signature from document in C#: [How to delete eSignature from document with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
- Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

```python
def delete(self, signatures):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| signatures | `List[BaseSignature]` | Список подписей для удаления из документа. |

**Returns:** DeleteResult: Result containing lists of successfully deleted signatures and those that failed.

### Пример

```python
import shutil
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def delete_text_signature():
    # Работайте с копией, потому что delete() сохраняет изменения в открытом документе.
    shutil.copy("signed.docx", "text_signature_deleted.docx")

    with Signature("text_signature_deleted.docx") as signature:
        options = TextSearchOptions()
        options.skip_external = True
        signatures = signature.search([options]).signatures
        print(f"Found {len(signatures)} text signature(s)")
        if not signatures:
            return

        # Удалить первую найденную подпись.
        if signature.delete([signatures[0]]):
            print("Signature deleted successfully")
        else:
            print("Signature could not be deleted")
```

## delete {#signature_type}

Удаляет подписи указанного типа из документа.

Будут удалены только подписи, добавленные методом `Sign` и помеченные как подписи ([`BaseSignature.IsSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/is_signature/)). Поддерживаемые типы подписей: Text, Image, Digital, Barcode и QR‑Code.

```python
def delete(self, signature_type):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| signature_type | `SignatureType` | Тип подписей, которые будут удалены из документа. |

**Returns:** DeleteResult: Contains lists of successfully deleted signatures and those that failed to delete.

| Вызывает | Описание |
| :- | :- |
| `Remarks` | - Узнать больше: - Подробнее о том, как удалить электронную подпись из документа в C#: https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+type/ - Расширенные сценарии удаления электронных подписей из документа: https://docs.groupdocs.com/display/signaturenet/Deleting |

## delete {#signature_types}

Удаляет подписи из списка указанного `SignatureType` в документе.

Будут удалены только подписи, добавленные методом `Sign` и помеченные как подписи ([`BaseSignature.is_signature`](/signature/python-net/groupdocs.signature.domain/basesignature/is_signature/)). Поддерживаемые типы подписей: Text, Image, Digital, Barcode и QR‑Code.

Узнать больше
- More about how to delete electronic signature from document in C#: <https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+types/>
- Advanced use cases of deleting document eSignatures: <https://docs.groupdocs.com/display/signaturenet/Deleting>

```python
def delete(self, signature_types):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| signature_types | `List[SignatureType]` | Список типов подписей, которые будут удалены из документа. |

**Returns:** `DeleteResult` with list of successfully deleted signatures and failed ones.

## delete {#signature_id}

Удаляет подпись по её конкретному идентификатору подписи из документа.

Узнать больше:

- More about how to delete electronic signature from document in C#: https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents
- Advanced use cases of deleting document eSignatures: https://docs.groupdocs.com/display/signaturenet/Deleting

```python
def delete(self, signature_id):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| signature_id | `str` | Идентификатор (Id) подписи, которую нужно удалить из документа. |

**Returns:** bool: True if the operation was successful.

## delete {#signature_ids}

Удаляет указанные подписи из документа.

Узнать больше:
- More about how to delete electronic signature from document in C#: https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents
- Advanced use cases of deleting document eSignatures: https://docs.groupdocs.com/display/signaturenet/Deleting

```python
def delete(self, signature_ids):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| signature_ids | `List[str]` | Список идентификаторов подписей, которые будут удалены из документа. |

**Returns:** DeleteResult: `DeleteResult` with lists of successfully deleted signatures and failed ones.

### Пример

```python
import shutil
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def delete_text_signature():
    # Работайте с копией, потому что delete() сохраняет изменения в открытом документе.
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

### См. также
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
