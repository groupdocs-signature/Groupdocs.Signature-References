---
title: "Methode delete"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Löscht die angegebene BaseSignature aus dem Dokument."
type: docs
url: /de/python-net/groupdocs.signature/signature/delete/
is_root: false
weight: 1010
---


## delete {#signature}

Löscht die angegebene [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) aus dem Dokument.

Mehr erfahren:
- More about how to delete electronic signature from document in C#: <https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents>
- Advanced use cases of deleting document eSignatures: <https://docs.groupdocs.com/display/signaturenet/Deleting>

```python
def delete(self, signature):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| signature | `BaseSignature` | BaseSignature-Objekt, das aus dem Dokument entfernt werden soll. |

**Returns:** bool: True if the operation was successful, otherwise False.

### Beispiel

```python
import shutil
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def delete_first_text_signature():
    # delete() speichert Änderungen im geöffneten Dokument, daher mit einer Kopie arbeiten
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

Löscht die bereitgestellte Liste von Signaturen aus dem Dokument.

- More about how to delete electronic signature from document in C#: [How to delete eSignature from document with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
- Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

```python
def delete(self, signatures):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| signatures | `List[BaseSignature]` | Liste der Signaturen, die aus dem Dokument entfernt werden sollen. |

**Returns:** DeleteResult: Result containing lists of successfully deleted signatures and those that failed.

### Beispiel

```python
import shutil
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def delete_text_signature():
    # Arbeiten Sie mit einer Kopie, weil delete() Änderungen im geöffneten Dokument speichert
    shutil.copy("signed.docx", "text_signature_deleted.docx")

    with Signature("text_signature_deleted.docx") as signature:
        options = TextSearchOptions()
        options.skip_external = True
        signatures = signature.search([options]).signatures
        print(f"Found {len(signatures)} text signature(s)")
        if not signatures:
            return

        # Lösche die zuerst gefundene Signatur
        if signature.delete([signatures[0]]):
            print("Signature deleted successfully")
        else:
            print("Signature could not be deleted")
```

## delete {#signature_type}

Löscht Signaturen des angegebenen Typs aus dem Dokument.

Nur Signaturen, die durch die `Sign`-Methode hinzugefügt und als Signaturen markiert wurden ([`BaseSignature.IsSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/is_signature/)), werden entfernt. Unterstützte Signaturtypen sind Text, Bild, Digital, Barcode und QR‑Code.

```python
def delete(self, signature_type):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| signature_type | `SignatureType` | Der Typ der Signaturen, die aus dem Dokument entfernt werden sollen. |

**Returns:** DeleteResult: Contains lists of successfully deleted signatures and those that failed to delete.

| Ausnahmen | Beschreibung |
| :- | :- |
| `Remarks` | - Mehr erfahren: - Mehr darüber, wie man elektronische Signaturen aus einem Dokument in C# löscht: https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+type/ - Fortgeschrittene Anwendungsfälle zum Löschen von Dokumenten‑eSignaturen: https://docs.groupdocs.com/display/signaturenet/Deleting |

## delete {#signature_types}

Löscht Signaturen der angegebenen `SignatureType`-Liste aus dem Dokument.

Nur Signaturen, die durch die `Sign`-Methode hinzugefügt und als Signaturen markiert wurden ([`BaseSignature.is_signature`](/signature/python-net/groupdocs.signature.domain/basesignature/is_signature/)), werden entfernt. Unterstützte Signaturtypen sind Text, Bild, Digital, Barcode und QR‑Code.

Mehr erfahren
- More about how to delete electronic signature from document in C#: <https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+types/>
- Advanced use cases of deleting document eSignatures: <https://docs.groupdocs.com/display/signaturenet/Deleting>

```python
def delete(self, signature_types):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| signature_types | `List[SignatureType]` | Die Liste der Signaturtypen, die aus dem Dokument entfernt werden sollen. |

**Returns:** `DeleteResult` with list of successfully deleted signatures and failed ones.

## delete {#signature_id}

Löscht eine Signatur anhand ihrer spezifischen Signatur‑Id aus dem Dokument.

Mehr erfahren:

- More about how to delete electronic signature from document in C#: https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents
- Advanced use cases of deleting document eSignatures: https://docs.groupdocs.com/display/signaturenet/Deleting

```python
def delete(self, signature_id):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| signature_id | `str` | Die Id der Signatur, die aus dem Dokument entfernt werden soll. |

**Returns:** bool: True if the operation was successful.

## delete {#signature_ids}

Löscht die angegebenen Signaturen aus dem Dokument.

Mehr erfahren:
- More about how to delete electronic signature from document in C#: https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents
- Advanced use cases of deleting document eSignatures: https://docs.groupdocs.com/display/signaturenet/Deleting

```python
def delete(self, signature_ids):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| signature_ids | `List[str]` | Liste der Kennungen der Signaturen, die aus dem Dokument entfernt werden sollen. |

**Returns:** DeleteResult: `DeleteResult` with lists of successfully deleted signatures and failed ones.

### Beispiel

```python
import shutil
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def delete_text_signature():
    # Arbeiten Sie mit einer Kopie, weil delete() Änderungen im geöffneten Dokument speichert
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

### Siehe auch
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
