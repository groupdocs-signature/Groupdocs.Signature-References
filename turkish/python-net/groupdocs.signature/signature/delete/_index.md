---
title: "delete yöntemi"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "Belirtilen BaseSignature'ı belgeden siler."
type: docs
url: /tr/python-net/groupdocs.signature/signature/delete/
is_root: false
weight: 1010
---


## delete {#signature}

Belgeden belirtilen [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) öğesini siler.

Daha fazla bilgi:
- More about how to delete electronic signature from document in C#: <https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents>
- Advanced use cases of deleting document eSignatures: <https://docs.groupdocs.com/display/signaturenet/Deleting>

```python
def delete(self, signature):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| signature | `BaseSignature` | Belgeden kaldırılacak BaseSignature nesnesi. |

**Returns:** bool: True if the operation was successful, otherwise False.

### Örnek

```python
import shutil
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def delete_first_text_signature():
    # delete() açılan belgeye değişiklikleri kaydeder, bu yüzden bir kopya üzerinde çalışın
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

Belgeden sağlanan imza listesini siler.

- More about how to delete electronic signature from document in C#: [How to delete eSignature from document with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
- Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

```python
def delete(self, signatures):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| signatures | `List[BaseSignature]` | Belgeden kaldırılacak imzaların listesi. |

**Returns:** DeleteResult: Result containing lists of successfully deleted signatures and those that failed.

### Örnek

```python
import shutil
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def delete_text_signature():
    # delete() açılan belgeye değişiklikleri kaydettiği için bir kopya üzerinde çalışın
    shutil.copy("signed.docx", "text_signature_deleted.docx")

    with Signature("text_signature_deleted.docx") as signature:
        options = TextSearchOptions()
        options.skip_external = True
        signatures = signature.search([options]).signatures
        print(f"Found {len(signatures)} text signature(s)")
        if not signatures:
            return

        # İlk bulunan imzayı sil
        if signature.delete([signatures[0]]):
            print("Signature deleted successfully")
        else:
            print("Signature could not be deleted")
```

## delete {#signature_type}

Belirtilen türdeki imzaları belgeden siler.

Yalnızca `Sign` yöntemiyle eklenen ve imza olarak işaretlenen imzalar ([`BaseSignature.IsSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/is_signature/)) kaldırılacaktır. Desteklenen imza türleri Metin, Görüntü, Dijital, Barkod ve QR‑Kod'dur.

```python
def delete(self, signature_type):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| signature_type | `SignatureType` | Belgeden kaldırılacak imza türü. |

**Returns:** DeleteResult: Contains lists of successfully deleted signatures and those that failed to delete.

| Kaldırır | Açıklama |
| :- | :- |
| `Remarks` | - Daha fazla bilgi: - C#'ta belgelerden elektronik imza nasıl silinir hakkında daha fazla bilgi: https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+type/ - Belge e-imzalarını silmenin gelişmiş kullanım durumları: https://docs.groupdocs.com/display/signaturenet/Deleting |

## delete {#signature_types}

Belirtilen `SignatureType` listesindeki imzaları belgeden siler.

Yalnızca `Sign` yöntemiyle eklenen ve imza olarak işaretlenen imzalar ([`BaseSignature.is_signature`](/signature/python-net/groupdocs.signature.domain/basesignature/is_signature/)) kaldırılacaktır. Desteklenen imza türleri Metin, Görüntü, Dijital, Barkod ve QR‑Kod'dur.

Daha fazla bilgi edinin
- More about how to delete electronic signature from document in C#: <https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+types/>
- Advanced use cases of deleting document eSignatures: <https://docs.groupdocs.com/display/signaturenet/Deleting>

```python
def delete(self, signature_types):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| signature_types | `List[SignatureType]` | Belgeden kaldırılacak imza türlerinin listesi. |

**Returns:** `DeleteResult` with list of successfully deleted signatures and failed ones.

## delete {#signature_id}

Belirli imza kimliğine göre bir imzayı belgeden siler.

Daha fazla bilgi:

- More about how to delete electronic signature from document in C#: https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents
- Advanced use cases of deleting document eSignatures: https://docs.groupdocs.com/display/signaturenet/Deleting

```python
def delete(self, signature_id):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| signature_id | `str` | Belgeden kaldırılacak imzanın Id'si. |

**Returns:** bool: True if the operation was successful.

## delete {#signature_ids}

Belirtilen imzaları belgeden siler.

Daha fazla bilgi:
- More about how to delete electronic signature from document in C#: https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents
- Advanced use cases of deleting document eSignatures: https://docs.groupdocs.com/display/signaturenet/Deleting

```python
def delete(self, signature_ids):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| signature_ids | `List[str]` | Belgeden kaldırılacak imzaların tanımlayıcılarının listesi. |

**Returns:** DeleteResult: `DeleteResult` with lists of successfully deleted signatures and failed ones.

### Örnek

```python
import shutil
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def delete_text_signature():
    # delete() açılan belgeye değişiklikleri kaydettiği için bir kopya üzerinde çalışın
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

### Ayrıca Bakınız
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
