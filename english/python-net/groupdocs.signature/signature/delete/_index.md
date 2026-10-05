---
title: delete method
second_title: GroupDocs.Signature for Python via .NET API References
description: "Deletes the specified BaseSignature from the document."
type: docs
url: /python-net/groupdocs.signature/signature/delete/
is_root: false
weight: 1010
---


## delete {#signature}

Deletes the specified [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) from the document.

Learn more:
- More about how to delete electronic signature from document in C#: <https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents>
- Advanced use cases of deleting document eSignatures: <https://docs.groupdocs.com/display/signaturenet/Deleting>

```python
def delete(self, signature):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| signature | `BaseSignature` | BaseSignature object to be removed from the document. |

**Returns:** bool: True if the operation was successful, otherwise False.

### Example

```python
import shutil
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def delete_first_text_signature():
    # delete() saves changes to the opened document, so work on a copy
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

Deletes the provided list of signatures from the document.

- More about how to delete electronic signature from document in C#: [How to delete eSignature from document with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
- Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

```python
def delete(self, signatures):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| signatures | `List[BaseSignature]` | List of signatures to remove from the document. |

**Returns:** DeleteResult: Result containing lists of successfully deleted signatures and those that failed.

### Example

```python
import shutil
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def delete_text_signature():
    # Work on a copy because delete() saves changes to the opened document
    shutil.copy("signed.docx", "text_signature_deleted.docx")

    with Signature("text_signature_deleted.docx") as signature:
        options = TextSearchOptions()
        options.skip_external = True
        signatures = signature.search([options]).signatures
        print(f"Found {len(signatures)} text signature(s)")
        if not signatures:
            return

        # Delete the first found signature
        if signature.delete([signatures[0]]):
            print("Signature deleted successfully")
        else:
            print("Signature could not be deleted")
```

## delete {#signature_type}

Deletes signatures of the specified type from the document.

Only signatures that were added by the `Sign` method and marked as signatures ([`BaseSignature.IsSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/is_signature/)) will be removed. Supported signature types are Text, Image, Digital, Barcode, and QR‑Code.

```python
def delete(self, signature_type):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| signature_type | `SignatureType` | The type of signatures to be removed from the document. |

**Returns:** DeleteResult: Contains lists of successfully deleted signatures and those that failed to delete.

| Raises | Description |
| :- | :- |
| `Remarks` | - Learn more: - More about how to delete electronic signature from document in C#: https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+type/ - Advanced use cases of deleting document eSignatures: https://docs.groupdocs.com/display/signaturenet/Deleting |

## delete {#signature_types}

Deletes signatures of the specified `SignatureType` list from the document.

Only signatures that were added by the `Sign` method and marked as signatures ([`BaseSignature.is_signature`](/signature/python-net/groupdocs.signature.domain/basesignature/is_signature/)) will be removed. Supported signature types are Text, Image, Digital, Barcode, and QR‑Code.

Learn more
- More about how to delete electronic signature from document in C#: <https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+types/>
- Advanced use cases of deleting document eSignatures: <https://docs.groupdocs.com/display/signaturenet/Deleting>

```python
def delete(self, signature_types):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| signature_types | `List[SignatureType]` | The list of signature types to be removed from the document. |

**Returns:** `DeleteResult` with list of successfully deleted signatures and failed ones.

## delete {#signature_id}

Deletes a signature by its specific signature Id from the document.

Learn more:

- More about how to delete electronic signature from document in C#: https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents
- Advanced use cases of deleting document eSignatures: https://docs.groupdocs.com/display/signaturenet/Deleting

```python
def delete(self, signature_id):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| signature_id | `str` | The Id of the signature to be removed from the document. |

**Returns:** bool: True if the operation was successful.

## delete {#signature_ids}

Deletes the specified signatures from the document.

Learn more:
- More about how to delete electronic signature from document in C#: https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents
- Advanced use cases of deleting document eSignatures: https://docs.groupdocs.com/display/signaturenet/Deleting

```python
def delete(self, signature_ids):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| signature_ids | `List[str]` | List of the identifiers of the signatures to be removed from the document. |

**Returns:** DeleteResult: `DeleteResult` with lists of successfully deleted signatures and failed ones.

### Example

```python
import shutil
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def delete_text_signature():
    # Work on a copy because delete() saves changes to the opened document
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

### See Also
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
