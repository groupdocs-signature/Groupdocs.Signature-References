---
title: "delete methode"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Verwijdert de opgegeven BaseSignature uit het document."
type: docs
url: /nl/python-net/groupdocs.signature/signature/delete/
is_root: false
weight: 1010
---


## delete {#signature}

Verwijdert de opgegeven [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) uit het document.

Meer informatie:
- More about how to delete electronic signature from document in C#: <https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents>
- Advanced use cases of deleting document eSignatures: <https://docs.groupdocs.com/display/signaturenet/Deleting>

```python
def delete(self, signature):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| signature | `BaseSignature` | BaseSignature-object dat uit het document moet worden verwijderd. |

**Returns:** bool: True if the operation was successful, otherwise False.

### Voorbeeld

```python
import shutil
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def delete_first_text_signature():
    # delete() slaat wijzigingen op in het geopende document, dus werk op een kopie.
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

Verwijdert de opgegeven lijst met handtekeningen uit het document.

- More about how to delete electronic signature from document in C#: [How to delete eSignature from document with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
- Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

```python
def delete(self, signatures):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| signatures | `List[BaseSignature]` | Lijst met handtekeningen die uit het document moeten worden verwijderd. |

**Returns:** DeleteResult: Result containing lists of successfully deleted signatures and those that failed.

### Voorbeeld

```python
import shutil
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def delete_text_signature():
    # Werk op een kopie omdat delete() wijzigingen opslaat in het geopende document.
    shutil.copy("signed.docx", "text_signature_deleted.docx")

    with Signature("text_signature_deleted.docx") as signature:
        options = TextSearchOptions()
        options.skip_external = True
        signatures = signature.search([options]).signatures
        print(f"Found {len(signatures)} text signature(s)")
        if not signatures:
            return

        # Verwijder de eerst gevonden handtekening.
        if signature.delete([signatures[0]]):
            print("Signature deleted successfully")
        else:
            print("Signature could not be deleted")
```

## delete {#signature_type}

Verwijdert handtekeningen van het opgegeven type uit het document.

Alleen handtekeningen die zijn toegevoegd met de `Sign`-methode en gemarkeerd als handtekeningen ([`BaseSignature.IsSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/is_signature/)) worden verwijderd. Ondersteunde handtekeningtypen zijn Tekst, Afbeelding, Digitaal, Barcode en QR‑Code.

```python
def delete(self, signature_type):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| signature_type | `SignatureType` | Het type handtekeningen dat uit het document moet worden verwijderd. |

**Returns:** DeleteResult: Contains lists of successfully deleted signatures and those that failed to delete.

| Verhoogt | Beschrijving |
| :- | :- |
| `Remarks` | - Meer info: - Meer over hoe elektronische handtekening uit document te verwijderen in C#: https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+type/ - Geavanceerde use‑cases van het verwijderen van document eSignatures: https://docs.groupdocs.com/display/signaturenet/Deleting |

## delete {#signature_types}

Verwijdert handtekeningen van de opgegeven `SignatureType`-lijst uit het document.

Alleen handtekeningen die zijn toegevoegd met de `Sign`-methode en gemarkeerd als handtekeningen ([`BaseSignature.is_signature`](/signature/python-net/groupdocs.signature.domain/basesignature/is_signature/)) worden verwijderd. Ondersteunde handtekeningtypen zijn Tekst, Afbeelding, Digitaal, Barcode en QR‑Code.

Meer informatie
- More about how to delete electronic signature from document in C#: <https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+types/>
- Advanced use cases of deleting document eSignatures: <https://docs.groupdocs.com/display/signaturenet/Deleting>

```python
def delete(self, signature_types):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| signature_types | `List[SignatureType]` | De lijst met handtekeningtypen die uit het document moeten worden verwijderd. |

**Returns:** `DeleteResult` with list of successfully deleted signatures and failed ones.

## delete {#signature_id}

Verwijdert een handtekening op basis van zijn specifieke handtekening‑Id uit het document.

Meer informatie:

- More about how to delete electronic signature from document in C#: https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents
- Advanced use cases of deleting document eSignatures: https://docs.groupdocs.com/display/signaturenet/Deleting

```python
def delete(self, signature_id):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| signature_id | `str` | De Id van de handtekening die uit het document moet worden verwijderd. |

**Returns:** bool: True if the operation was successful.

## delete {#signature_ids}

Verwijdert de opgegeven handtekeningen uit het document.

Meer informatie:
- More about how to delete electronic signature from document in C#: https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents
- Advanced use cases of deleting document eSignatures: https://docs.groupdocs.com/display/signaturenet/Deleting

```python
def delete(self, signature_ids):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| signature_ids | `List[str]` | Lijst met de identifiers van de handtekeningen die uit het document moeten worden verwijderd. |

**Returns:** DeleteResult: `DeleteResult` with lists of successfully deleted signatures and failed ones.

### Voorbeeld

```python
import shutil
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def delete_text_signature():
    # Werk op een kopie omdat delete() wijzigingen opslaat in het geopende document.
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

### Zie ook
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
