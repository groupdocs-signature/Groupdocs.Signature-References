---
title: "méthode delete"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Supprime le BaseSignature spécifié du document."
type: docs
url: /fr/python-net/groupdocs.signature/signature/delete/
is_root: false
weight: 1010
---


## delete {#signature}

Supprime le [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) spécifié du document.

En savoir plus :
- More about how to delete electronic signature from document in C#: <https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents>
- Advanced use cases of deleting document eSignatures: <https://docs.groupdocs.com/display/signaturenet/Deleting>

```python
def delete(self, signature):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| signature | `BaseSignature` | Objet BaseSignature à supprimer du document. |

**Returns:** bool: True if the operation was successful, otherwise False.

### Exemple

```python
import shutil
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def delete_first_text_signature():
    # delete() enregistre les modifications dans le document ouvert, donc travaillez sur une copie
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

Supprime la liste fournie de signatures du document.

- More about how to delete electronic signature from document in C#: [How to delete eSignature from document with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
- Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

```python
def delete(self, signatures):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| signatures | `List[BaseSignature]` | Liste des signatures à supprimer du document. |

**Returns:** DeleteResult: Result containing lists of successfully deleted signatures and those that failed.

### Exemple

```python
import shutil
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def delete_text_signature():
    # Travaillez sur une copie car delete() enregistre les modifications dans le document ouvert
    shutil.copy("signed.docx", "text_signature_deleted.docx")

    with Signature("text_signature_deleted.docx") as signature:
        options = TextSearchOptions()
        options.skip_external = True
        signatures = signature.search([options]).signatures
        print(f"Found {len(signatures)} text signature(s)")
        if not signatures:
            return

        # Supprimer la première signature trouvée
        if signature.delete([signatures[0]]):
            print("Signature deleted successfully")
        else:
            print("Signature could not be deleted")
```

## delete {#signature_type}

Supprime les signatures du type spécifié du document.

Seules les signatures qui ont été ajoutées par la méthode `Sign` et marquées comme signatures ([`BaseSignature.IsSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/is_signature/)) seront supprimées. Les types de signatures pris en charge sont Texte, Image, Numérique, Code-barres et QR‑Code.

```python
def delete(self, signature_type):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| signature_type | `SignatureType` | Le type de signatures à supprimer du document. |

**Returns:** DeleteResult: Contains lists of successfully deleted signatures and those that failed to delete.

| Lève | Description |
| :- | :- |
| `Remarks` | - En savoir plus : - Plus d'informations sur la façon de supprimer une signature électronique d'un document en C# : https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+type/ - Cas d'utilisation avancés de la suppression de signatures électroniques de documents : https://docs.groupdocs.com/display/signaturenet/Deleting |

## delete {#signature_types}

Supprime les signatures de la liste `SignatureType` spécifiée du document.

Seules les signatures qui ont été ajoutées par la méthode `Sign` et marquées comme signatures ([`BaseSignature.is_signature`](/signature/python-net/groupdocs.signature.domain/basesignature/is_signature/)) seront supprimées. Les types de signatures pris en charge sont Texte, Image, Numérique, Code-barres et QR‑Code.

En savoir plus
- More about how to delete electronic signature from document in C#: <https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+types/>
- Advanced use cases of deleting document eSignatures: <https://docs.groupdocs.com/display/signaturenet/Deleting>

```python
def delete(self, signature_types):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| signature_types | `List[SignatureType]` | La liste des types de signatures à supprimer du document. |

**Returns:** `DeleteResult` with list of successfully deleted signatures and failed ones.

## delete {#signature_id}

Supprime une signature par son Id de signature spécifique du document.

En savoir plus :

- More about how to delete electronic signature from document in C#: https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents
- Advanced use cases of deleting document eSignatures: https://docs.groupdocs.com/display/signaturenet/Deleting

```python
def delete(self, signature_id):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| signature_id | `str` | L'Id de la signature à supprimer du document. |

**Returns:** bool: True if the operation was successful.

## delete {#signature_ids}

Supprime les signatures spécifiées du document.

En savoir plus :
- More about how to delete electronic signature from document in C#: https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents
- Advanced use cases of deleting document eSignatures: https://docs.groupdocs.com/display/signaturenet/Deleting

```python
def delete(self, signature_ids):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| signature_ids | `List[str]` | Liste des identifiants des signatures à supprimer du document. |

**Returns:** DeleteResult: `DeleteResult` with lists of successfully deleted signatures and failed ones.

### Exemple

```python
import shutil
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def delete_text_signature():
    # Travaillez sur une copie car delete() enregistre les modifications dans le document ouvert
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

### Voir aussi
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
