---
title: "metodo delete"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Elimina il BaseSignature specificato dal documento."
type: docs
url: /it/python-net/groupdocs.signature/signature/delete/
is_root: false
weight: 1010
---


## delete {#signature}

Elimina il [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) specificato dal documento.

Per saperne di più:
- More about how to delete electronic signature from document in C#: <https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents>
- Advanced use cases of deleting document eSignatures: <https://docs.groupdocs.com/display/signaturenet/Deleting>

```python
def delete(self, signature):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| signature | `BaseSignature` | Oggetto BaseSignature da rimuovere dal documento. |

**Returns:** bool: True if the operation was successful, otherwise False.

### Esempio

```python
import shutil
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def delete_first_text_signature():
    # delete() salva le modifiche al documento aperto, quindi lavora su una copia.
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

Elimina l'elenco fornito di firme dal documento.

- More about how to delete electronic signature from document in C#: [How to delete eSignature from document with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
- Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

```python
def delete(self, signatures):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| signatures | `List[BaseSignature]` | Elenco delle firme da rimuovere dal documento. |

**Returns:** DeleteResult: Result containing lists of successfully deleted signatures and those that failed.

### Esempio

```python
import shutil
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def delete_text_signature():
    # Lavora su una copia perché delete() salva le modifiche al documento aperto.
    shutil.copy("signed.docx", "text_signature_deleted.docx")

    with Signature("text_signature_deleted.docx") as signature:
        options = TextSearchOptions()
        options.skip_external = True
        signatures = signature.search([options]).signatures
        print(f"Found {len(signatures)} text signature(s)")
        if not signatures:
            return

        # Elimina la prima firma trovata.
        if signature.delete([signatures[0]]):
            print("Signature deleted successfully")
        else:
            print("Signature could not be deleted")
```

## delete {#signature_type}

Elimina le firme del tipo specificato dal documento.

Solo le firme aggiunte con il metodo `Sign` e contrassegnate come firme ([`BaseSignature.IsSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/is_signature/)) saranno rimosse. I tipi di firma supportati sono Testo, Immagine, Digitale, Codice a barre e QR‑Code.

```python
def delete(self, signature_type):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| signature_type | `SignatureType` | Il tipo di firme da rimuovere dal documento. |

**Returns:** DeleteResult: Contains lists of successfully deleted signatures and those that failed to delete.

| Genera | Descrizione |
| :- | :- |
| `Remarks` | - Per saperne di più: - Maggiori informazioni su come eliminare firme elettroniche da un documento in C#: https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+type/ - Casi d'uso avanzati per l'eliminazione di eSignature nei documenti: https://docs.groupdocs.com/display/signaturenet/Deleting |

## delete {#signature_types}

Elimina le firme dell'elenco `SignatureType` specificato dal documento.

Solo le firme aggiunte con il metodo `Sign` e contrassegnate come firme ([`BaseSignature.is_signature`](/signature/python-net/groupdocs.signature.domain/basesignature/is_signature/)) saranno rimosse. I tipi di firma supportati sono Testo, Immagine, Digitale, Codice a barre e QR‑Code.

Maggiori informazioni
- More about how to delete electronic signature from document in C#: <https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+types/>
- Advanced use cases of deleting document eSignatures: <https://docs.groupdocs.com/display/signaturenet/Deleting>

```python
def delete(self, signature_types):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| signature_types | `List[SignatureType]` | L'elenco dei tipi di firma da rimuovere dal documento. |

**Returns:** `DeleteResult` with list of successfully deleted signatures and failed ones.

## delete {#signature_id}

Elimina una firma dal documento tramite il suo ID firma specifico.

Per saperne di più:

- More about how to delete electronic signature from document in C#: https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents
- Advanced use cases of deleting document eSignatures: https://docs.groupdocs.com/display/signaturenet/Deleting

```python
def delete(self, signature_id):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| signature_id | `str` | L'Id della firma da rimuovere dal documento. |

**Returns:** bool: True if the operation was successful.

## delete {#signature_ids}

Elimina le firme specificate dal documento.

Per saperne di più:
- More about how to delete electronic signature from document in C#: https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents
- Advanced use cases of deleting document eSignatures: https://docs.groupdocs.com/display/signaturenet/Deleting

```python
def delete(self, signature_ids):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| signature_ids | `List[str]` | Elenco degli identificatori delle firme da rimuovere dal documento. |

**Returns:** DeleteResult: `DeleteResult` with lists of successfully deleted signatures and failed ones.

### Esempio

```python
import shutil
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def delete_text_signature():
    # Lavora su una copia perché delete() salva le modifiche al documento aperto.
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

### Vedi anche
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
