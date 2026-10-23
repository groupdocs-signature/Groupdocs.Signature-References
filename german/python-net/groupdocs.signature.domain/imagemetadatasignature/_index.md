---
title: "ImageMetadataSignature Klasse"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Stellt eine Bild-Metadaten-Signatur dar."
type: docs
url: /de/python-net/groupdocs.signature.domain/imagemetadatasignature/
is_root: false
weight: 320
---


## ImageMetadataSignature class

Stellt eine Bild-Metadaten-Signatur dar.

Metadaten‑Signaturen für Bilddokumente sind elektronische Signaturen, die auf Bild‑Metadaten‑Standards wie EXIF basieren. Jede Signatur wird durch einen numerischen Bezeichner (0‑65535) identifiziert und speichert einen Wert verschiedener Typen (Text, Datum/Uhrzeit, Ganzzahl, Fließkomma).

Der ImageMetadataSignature Typ stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/__init__/#id-value) | Initialisiert eine Bild‑Metadaten‑Signatur mit dem angegebenen Bezeichner und Wert. |

### Methoden
| Methode | Beschreibung |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/clone/) | Klone Metadaten-Signatur-Instanz. |
| [clone](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/clone/#value) | Klont eine ImageMetadataSignature‑Instanz mit dem angegebenen Wert. |
| [clone_object](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/clone_object/) |  |
| [equals](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/equals/#obj) | Bestimmt, ob das angegebene Signatur‑Objekt gleich dieser Instanz ist. |
| [equals_object](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/equals_object/) |  |
| [get_hash_code](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/get_hash_code/) | Gibt den Hashcode für die Signatur zurück. |
| [to_boolean](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_boolean/) | Konvertiert den Metadaten‑Signaturwert zu einem Boolean. |
| [to_date_time](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_date_time/) | Konvertiert den Metadaten‑Signaturwert zu einem `datetime.datetime`. |
| [to_date_time](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_date_time/#provider) | Konvertiert den Metadaten‑Signaturwert zu einem `datetime`. |
| [to_date_time_iformat_provider](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_date_time_iformat_provider/) |  |
| [to_decimal](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_decimal/) | Konvertiert zu Decimal. |
| [to_decimal](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_decimal/#provider) | Konvertiert den Metadaten‑Signaturwert zu einem Dezimalwert. |
| [to_decimal_iformat_provider](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_decimal_iformat_provider/) |  |
| [to_double](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_double/) | Konvertiert zu einem Float. |
| [to_double](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_double/#provider) | Konvertiert den Wert der metadata signature in einen float. |
| [to_double_iformat_provider](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_double_iformat_provider/) |  |
| [to_integer](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_integer/) | Konvertiert den Wert der metadata signature in einen Integer. |
| [to_long](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_long/) | Konvertiert zu einem Long. |
| [to_single](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_single/) | Konvertiert zu float. |
| [to_single](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_single/#provider) | Konvertiert den Wert der metadata signature in einen float. |
| [to_single_iformat_provider](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_single_iformat_provider/) |  |
| [to_string](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_string/) | Konvertiert den Metadaten‑Signaturwert zu einem String. |
| [to_string](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_string/#format) | Konvertiert den Metadaten‑Signaturwert zu einem String unter Verwendung des angegebenen Formats. |
| [to_string](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_string/#format-provider) | Konvertiert in einen String mit dem angegebenen Format. |
| [to_string_file](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_string_file/) |  |
| [to_string_string](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_string_string/) |  |
| [get_data](/signature/python-net/groupdocs.signature.domain/metadatasignature/get_data/) | (geerbt von [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [get_data_idata_encryption](/signature/python-net/groupdocs.signature.domain/metadatasignature/get_data_idata_encryption/) | (geerbt von [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [description](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/description/) | Die Beschreibung der Standard‑Image‑Metadata‑Signatur. |
| [id](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/id/) | Der Bezeichner der Image Metadata Signatur. Siehe die Klasse `GroupDocs.Signature.Domain.ImageMetadataSignatures`, die die Standard‑Signature mit vordefiniertem Id‑Wert enthält. |
| [size](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/size/) | Die Größe des Metadatenwerts. |
| [created_on](/signature/python-net/groupdocs.signature.domain/basesignature/created_on/) | Das Erstellungsdatum der Signatur. (geerbt von [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [data_encryption](/signature/python-net/groupdocs.signature.domain/metadatasignature/data_encryption/) | Die Implementierung von [`IDataEncryption`](/signature/python-net/groupdocs.signature.domain.extensions/idataencryption/) wird verwendet, um Signaturwert-Eigenschaften zu kodieren und zu dekodieren. (geerbt von [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [deleted](/signature/python-net/groupdocs.signature.domain/basesignature/deleted/) | Das Flag, das angibt, ob diese Signatur aus dem Dokument gelöscht wurde. (geerbt von [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [height](/signature/python-net/groupdocs.signature.domain/basesignature/height/) | Die Höhe der Signatur. (geerbt von [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [is_signature](/signature/python-net/groupdocs.signature.domain/basesignature/is_signature/) | Das Flag, das angibt, ob diese Komponente eine Signatur (`True`) oder Dokumentinhalt (`False`) darstellt. (geerbt von [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [left](/signature/python-net/groupdocs.signature.domain/basesignature/left/) | Die linke Position der Signatur. (geerbt von [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [modified_on](/signature/python-net/groupdocs.signature.domain/basesignature/modified_on/) | Das Änderungsdatum der Signatur. (geerbt von [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [name](/signature/python-net/groupdocs.signature.domain/metadatasignature/name/) | Der eindeutige Metadatenname. (geerbt von [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [page_number](/signature/python-net/groupdocs.signature.domain/basesignature/page_number/) | Die Seitenzahl, auf der die Signatur gefunden wurde. (geerbt von [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [signature_id](/signature/python-net/groupdocs.signature.domain/basesignature/signature_id/) | Der eindeutige Bezeichner der Signatur, der verwendet wird, um die Signatur im Dokument über Update- oder Löschvorgänge zu ändern. (geerbt von [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [signature_type](/signature/python-net/groupdocs.signature.domain/basesignature/signature_type/) | Der Typ der Signatur. (geerbt von [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [top](/signature/python-net/groupdocs.signature.domain/basesignature/top/) | Die obere Position der Signatur. (geerbt von [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [type](/signature/python-net/groupdocs.signature.domain/metadatasignature/type/) | Der Metadatenwerttyp. (geerbt von [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [value](/signature/python-net/groupdocs.signature.domain/metadatasignature/value/) | Das Metadatenobjekt. (geerbt von [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [width](/signature/python-net/groupdocs.signature.domain/basesignature/width/) | Die Breite der Signatur. (geerbt von [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |

### Beispiel

```python
from datetime import datetime

from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSignOptions
from groupdocs.signature.domain import ImageMetadataSignature


def sign_png():
    with Signature("sample.png") as signature:
        options = MetadataSignOptions()

        metadata_id = 41996
        options.add(ImageMetadataSignature(metadata_id, "Mr.Scherlock Holmes"))   # text
        options.add(ImageMetadataSignature(metadata_id + 1, datetime.now()))    # date and time
        options.add(ImageMetadataSignature(metadata_id + 2, 123456))            # whole number
        options.add(ImageMetadataSignature(metadata_id + 3, 123.456))           # floating‑point number

        result = signature.sign("signed.png", options)
        print(f"Signed with {len(result.succeeded)} metadata signature(s):")
        for item in result.succeeded:
            print(f"  {item.id}")
```

### Siehe auch
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
