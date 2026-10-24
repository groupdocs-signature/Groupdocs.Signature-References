---
title: "delete‑metod"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Tar bort den angivna BaseSignature från dokumentet."
type: docs
url: /sv/python-net/groupdocs.signature/signature/delete/
is_root: false
weight: 1010
---


## delete {#signature}

Tar bort den angivna [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) från dokumentet.

Läs mer:
- More about how to delete electronic signature from document in C#: <https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents>
- Advanced use cases of deleting document eSignatures: <https://docs.groupdocs.com/display/signaturenet/Deleting>

```python
def delete(self, signature):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| signature | `BaseSignature` | BaseSignature‑objekt som ska tas bort från dokumentet. |

**Returns:** bool: True if the operation was successful, otherwise False.

### Exempel

```python
import shutil
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def delete_first_text_signature():
    # `delete()` sparar ändringar i det öppnade dokumentet, så arbeta på en kopia
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

Tar bort den angivna listan med signaturer från dokumentet.

- More about how to delete electronic signature from document in C#: [How to delete eSignature from document with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
- Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

```python
def delete(self, signatures):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| signatures | `List[BaseSignature]` | Lista över signaturer att ta bort från dokumentet. |

**Returns:** DeleteResult: Result containing lists of successfully deleted signatures and those that failed.

### Exempel

```python
import shutil
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def delete_text_signature():
    # Arbeta på en kopia eftersom `delete()` sparar ändringar i det öppnade dokumentet
    shutil.copy("signed.docx", "text_signature_deleted.docx")

    with Signature("text_signature_deleted.docx") as signature:
        options = TextSearchOptions()
        options.skip_external = True
        signatures = signature.search([options]).signatures
        print(f"Found {len(signatures)} text signature(s)")
        if not signatures:
            return

        # Ta bort den först hittade signaturen
        if signature.delete([signatures[0]]):
            print("Signature deleted successfully")
        else:
            print("Signature could not be deleted")
```

## delete {#signature_type}

Tar bort signaturer av den angivna typen från dokumentet.

Endast signaturer som lades till med `Sign`‑metoden och markerades som signaturer ([`BaseSignature.IsSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/is_signature/)) kommer att tas bort. Stödda signaturtyper är Text, Image, Digital, Barcode och QR‑Code.

```python
def delete(self, signature_type):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| signature_type | `SignatureType` | Typen av signaturer som ska tas bort från dokumentet. |

**Returns:** DeleteResult: Contains lists of successfully deleted signatures and those that failed to delete.

| Utlöser | Beskrivning |
| :- | :- |
| `Remarks` | - Läs mer: - Mer om hur man tar bort elektronisk signatur från dokument i C#: https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+type/ - Avancerade användningsfall för att ta bort dokument‑eSignaturer: https://docs.groupdocs.com/display/signaturenet/Deleting |

## delete {#signature_types}

Tar bort signaturer från den angivna `SignatureType`-listan i dokumentet.

Endast signaturer som lades till med `Sign`‑metoden och markerades som signaturer ([`BaseSignature.is_signature`](/signature/python-net/groupdocs.signature.domain/basesignature/is_signature/)) kommer att tas bort. Stödda signaturtyper är Text, Image, Digital, Barcode och QR‑Code.

Läs mer
- More about how to delete electronic signature from document in C#: <https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+types/>
- Advanced use cases of deleting document eSignatures: <https://docs.groupdocs.com/display/signaturenet/Deleting>

```python
def delete(self, signature_types):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| signature_types | `List[SignatureType]` | Listan över signaturtyper som ska tas bort från dokumentet. |

**Returns:** `DeleteResult` with list of successfully deleted signatures and failed ones.

## delete {#signature_id}

Tar bort en signatur med dess specifika signatur‑Id från dokumentet.

Läs mer:

- More about how to delete electronic signature from document in C#: https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents
- Advanced use cases of deleting document eSignatures: https://docs.groupdocs.com/display/signaturenet/Deleting

```python
def delete(self, signature_id):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| signature_id | `str` | Id‑et för signaturen som ska tas bort från dokumentet. |

**Returns:** bool: True if the operation was successful.

## delete {#signature_ids}

Tar bort de angivna signaturerna från dokumentet.

Läs mer:
- More about how to delete electronic signature from document in C#: https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents
- Advanced use cases of deleting document eSignatures: https://docs.groupdocs.com/display/signaturenet/Deleting

```python
def delete(self, signature_ids):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| signature_ids | `List[str]` | Lista över identifierarna för signaturerna som ska tas bort från dokumentet. |

**Returns:** DeleteResult: `DeleteResult` with lists of successfully deleted signatures and failed ones.

### Exempel

```python
import shutil
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def delete_text_signature():
    # Arbeta på en kopia eftersom `delete()` sparar ändringar i det öppnade dokumentet
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

### Se även
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
