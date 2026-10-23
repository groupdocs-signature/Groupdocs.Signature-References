---
title: "ImageSignature Klasse"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Die Klasse enthält Eigenschaften von Bildsignaturen."
type: docs
url: /de/python-net/groupdocs.signature.domain/imagesignature/
is_root: false
weight: 340
---


## ImageSignature class

Die Klasse enthält Eigenschaften von Bildsignaturen.

Der ImageSignature-Typ stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/imagesignature/__init__/#signature_id) | Initialisiert ein ImageSignature-Objekt mit einem eindeutigen Signaturbezeichner, der aus der Sign- oder Search-Methode der [`GroupDocs.Signature`](/signature/python-net/groupdocs.signature/signature/) Klasse erhalten wurde. |

### Methoden
| Methode | Beschreibung |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/imagesignature/clone/) | Klone ImageSignature-Instanz. |
| [equals](/signature/python-net/groupdocs.signature.domain/imagesignature/equals/#obj) | Bestimmt, ob die angegebene Signatur dieser Instanz gleich ist. |
| [equals_object](/signature/python-net/groupdocs.signature.domain/imagesignature/equals_object/) |  |
| [get_hash_code](/signature/python-net/groupdocs.signature.domain/imagesignature/get_hash_code/) | Gibt den Hashcode für die Signatur zurück. |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [content](/signature/python-net/groupdocs.signature.domain/imagesignature/content/) | Die binären Bilddaten der Signatur im von [`ImageSignature.Format`](/signature/python-net/groupdocs.signature.domain/imagesignature/format/) angegebenen Format. |
| [format](/signature/python-net/groupdocs.signature.domain/imagesignature/format/) | Das Format des Signaturbildes. |
| [size](/signature/python-net/groupdocs.signature.domain/imagesignature/size/) | Die Größe des Signaturbildes in Bytes. |
| [created_on](/signature/python-net/groupdocs.signature.domain/basesignature/created_on/) | Das Erstellungsdatum der Signatur. (geerbt von [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [deleted](/signature/python-net/groupdocs.signature.domain/basesignature/deleted/) | Das Flag, das angibt, ob diese Signatur aus dem Dokument gelöscht wurde. (geerbt von [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [height](/signature/python-net/groupdocs.signature.domain/basesignature/height/) | Die Höhe der Signatur. (geerbt von [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [is_signature](/signature/python-net/groupdocs.signature.domain/basesignature/is_signature/) | Das Flag, das angibt, ob diese Komponente eine Signatur (`True`) oder Dokumentinhalt (`False`) darstellt. (geerbt von [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [left](/signature/python-net/groupdocs.signature.domain/basesignature/left/) | Die linke Position der Signatur. (geerbt von [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [modified_on](/signature/python-net/groupdocs.signature.domain/basesignature/modified_on/) | Das Änderungsdatum der Signatur. (geerbt von [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [page_number](/signature/python-net/groupdocs.signature.domain/basesignature/page_number/) | Die Seitenzahl, auf der die Signatur gefunden wurde. (geerbt von [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [signature_id](/signature/python-net/groupdocs.signature.domain/basesignature/signature_id/) | Der eindeutige Bezeichner der Signatur, der verwendet wird, um die Signatur im Dokument über Update- oder Löschvorgänge zu ändern. (geerbt von [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [signature_type](/signature/python-net/groupdocs.signature.domain/basesignature/signature_type/) | Der Typ der Signatur. (geerbt von [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [top](/signature/python-net/groupdocs.signature.domain/basesignature/top/) | Die obere Position der Signatur. (geerbt von [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [width](/signature/python-net/groupdocs.signature.domain/basesignature/width/) | Die Breite der Signatur. (geerbt von [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |

### Beispiel

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import ImageSearchOptions

with Signature("signed.pdf") as signature:
    result = signature.search([ImageSearchOptions()])
    for image in result.signatures:
        print(
            f"Page {image.page_number}: {image.size} bytes at ({image.left}, {image.top}), "
            f"size {image.width}x{image.height}"
        )
```

### Siehe auch
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
