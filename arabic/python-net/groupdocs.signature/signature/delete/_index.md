---
title: "طريقة delete"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "يحذف BaseSignature المحدد من المستند."
type: docs
url: /ar/python-net/groupdocs.signature/signature/delete/
is_root: false
weight: 1010
---


## delete {#signature}

يحذف [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) المحدد من المستند.

تعرف على المزيد:
- More about how to delete electronic signature from document in C#: <https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents>
- Advanced use cases of deleting document eSignatures: <https://docs.groupdocs.com/display/signaturenet/Deleting>

```python
def delete(self, signature):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| signature | `BaseSignature` | كائن BaseSignature لإزالته من المستند. |

**Returns:** bool: True if the operation was successful, otherwise False.

### مثال

```python
import shutil
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def delete_first_text_signature():
    # تقوم delete() بحفظ التغييرات في المستند المفتوح، لذا اعمل على نسخة.
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

يحذف القائمة المقدمة من التوقيعات من المستند.

- More about how to delete electronic signature from document in C#: [How to delete eSignature from document with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
- Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

```python
def delete(self, signatures):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| signatures | `List[BaseSignature]` | قائمة التوقيعات لإزالتها من المستند. |

**Returns:** DeleteResult: Result containing lists of successfully deleted signatures and those that failed.

### مثال

```python
import shutil
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def delete_text_signature():
    # اعمل على نسخة لأن delete() تحفظ التغييرات في المستند المفتوح.
    shutil.copy("signed.docx", "text_signature_deleted.docx")

    with Signature("text_signature_deleted.docx") as signature:
        options = TextSearchOptions()
        options.skip_external = True
        signatures = signature.search([options]).signatures
        print(f"Found {len(signatures)} text signature(s)")
        if not signatures:
            return

        # احذف أول توقيع تم العثور عليه.
        if signature.delete([signatures[0]]):
            print("Signature deleted successfully")
        else:
            print("Signature could not be deleted")
```

## delete {#signature_type}

يحذف التوقيعات من النوع المحدد من المستند.

سيتم إزالة التوقيعات التي أضيفت فقط بواسطة طريقة `Sign` وتم وضع علامة عليها كتوقيعات ([`BaseSignature.IsSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/is_signature/)). الأنواع المدعومة للتوقيع هي النص، الصورة، الرقمي، الباركود، وQR‑Code.

```python
def delete(self, signature_type):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| signature_type | `SignatureType` | نوع التوقيعات التي سيتم إزالتها من المستند. |

**Returns:** DeleteResult: Contains lists of successfully deleted signatures and those that failed to delete.

| يُثير | الوصف |
| :- | :- |
| `Remarks` | - معرفة المزيد: - المزيد حول كيفية حذف التوقيع الإلكتروني من المستند في C#: https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+type/ - حالات الاستخدام المتقدمة لحذف التوقيعات الإلكترونية من المستند: https://docs.groupdocs.com/display/signaturenet/Deleting |

## delete {#signature_types}

يحذف التوقيعات من القائمة المحددة لـ `SignatureType` من المستند.

سيتم إزالة التوقيعات التي أضيفت فقط بواسطة طريقة `Sign` وتم وضع علامة عليها كتوقيعات ([`BaseSignature.is_signature`](/signature/python-net/groupdocs.signature.domain/basesignature/is_signature/)). الأنواع المدعومة للتوقيع هي النص، الصورة، الرقمي، الباركود، وQR‑Code.

اعرف المزيد
- More about how to delete electronic signature from document in C#: <https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+types/>
- Advanced use cases of deleting document eSignatures: <https://docs.groupdocs.com/display/signaturenet/Deleting>

```python
def delete(self, signature_types):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| signature_types | `List[SignatureType]` | قائمة أنواع التوقيعات التي سيتم إزالتها من المستند. |

**Returns:** `DeleteResult` with list of successfully deleted signatures and failed ones.

## delete {#signature_id}

يحذف توقيعًا باستخدام معرف التوقيع المحدد الخاص به من المستند.

تعرف على المزيد:

- More about how to delete electronic signature from document in C#: https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents
- Advanced use cases of deleting document eSignatures: https://docs.groupdocs.com/display/signaturenet/Deleting

```python
def delete(self, signature_id):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| signature_id | `str` | معرّف (Id) التوقيع الذي سيتم إزالته من المستند. |

**Returns:** bool: True if the operation was successful.

## delete {#signature_ids}

يحذف التوقيعات المحددة من المستند.

تعرف على المزيد:
- More about how to delete electronic signature from document in C#: https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents
- Advanced use cases of deleting document eSignatures: https://docs.groupdocs.com/display/signaturenet/Deleting

```python
def delete(self, signature_ids):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| signature_ids | `List[str]` | قائمة معرفات التوقيعات التي سيتم إزالتها من المستند. |

**Returns:** DeleteResult: `DeleteResult` with lists of successfully deleted signatures and failed ones.

### مثال

```python
import shutil
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def delete_text_signature():
    # اعمل على نسخة لأن delete() تحفظ التغييرات في المستند المفتوح.
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

### انظر أيضًا
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
