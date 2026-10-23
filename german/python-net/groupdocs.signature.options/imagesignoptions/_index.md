---
title: "Klasse ImageSignOptions"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Stellt die Bildsignatur-Optionen dar."
type: docs
url: /de/python-net/groupdocs.signature.options/imagesignoptions/
is_root: false
weight: 250
---


## ImageSignOptions class

Stellt die Bildsignatur-Optionen dar.

Mehr erfahren:
- Basic usage of creating Image electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Image+signature
- Advanced usage of settings of Image electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Image+signature+-+advanced

Der Typ ImageSignOptions stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/imagesignoptions/__init__/) | Initialisiert eine neue Instanz der Klasse ImageSignOptions mit Standardwerten. |
| [__init__](/signature/python-net/groupdocs.signature.options/imagesignoptions/__init__/#image_file_path) | Initialisiert ImageSignOptions mit einer Bilddatei. |
| [__init__](/signature/python-net/groupdocs.signature.options/imagesignoptions/__init__/#image_stream) | Initialisiert eine neue ImageSignOptions-Instanz mit einem Bild-Stream. |

### Methoden
| Methode | Beschreibung |
| :- | :- |
| [dispose](/signature/python-net/groupdocs.signature.options/imagesignoptions/dispose/) | Löscht interne Ressourcen. |
| [from_base64](/signature/python-net/groupdocs.signature.options/imagesignoptions/from_base64/#base_64_content) | Erstellt eine neue ImageSignOptions-Instanz mit einem vordefinierten Bild aus einem Base64-String. |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [border](/signature/python-net/groupdocs.signature.options/imagesignoptions/border/) | Die Rahmeneinstellungen für die Bildsignatur. |
| [height](/signature/python-net/groupdocs.signature.options/imagesignoptions/height/) | Die Höhe der Signatur auf der Dokumentenseite in Messwerten (Pixel, Prozent oder Millimeter; siehe `MeasureType` SizeMeasureType). |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/imagesignoptions/horizontal_alignment/) | Die horizontale Ausrichtung der Signatur auf der Dokumentenseite. |
| [image_file_path](/signature/python-net/groupdocs.signature.options/imagesignoptions/image_file_path/) | Der Dateipfad des Signaturbildes, wird nur verwendet, wenn `image_stream` nicht angegeben ist. |
| [image_stream](/signature/python-net/groupdocs.signature.options/imagesignoptions/image_stream/) | Der Signaturbild-Stream. Wenn angegeben, wird er immer anstelle von ImageFilePath verwendet. |
| [left](/signature/python-net/groupdocs.signature.options/imagesignoptions/left/) | Die linke X‑Position der Signatur auf der Dokumentenseite in Messwerten (Pixel, Prozente oder Millimeter). Funktioniert, wenn die horizontale Ausrichtung nicht angegeben ist. Siehe `MeasureType` für den Ort‑Messtyp. |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/imagesignoptions/location_measure_type/) | Der Messtyp (Pixel, Prozente oder Millimeter) für die linken und oberen Eigenschaften. |
| [margin](/signature/python-net/groupdocs.signature.options/imagesignoptions/margin/) | Der Abstand zwischen der Signatur und den Dokumentenkanten. Funktioniert nur, wenn horizontale oder vertikale Ausrichtung angegeben ist. |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/imagesignoptions/margin_measure_type/) | Der Messtyp (Pixel, Prozente oder Millimeter) für den Rand. |
| [rectangle](/signature/python-net/groupdocs.signature.options/imagesignoptions/rectangle/) | Das Rechteck des Bereichs, in dem das Bild im Dokument platziert wird. |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/imagesignoptions/rotation_angle/) | Der Rotationswinkel der Signatur auf der Dokumentenseite (im Uhrzeigersinn). |
| [shape_position](/signature/python-net/groupdocs.signature.options/imagesignoptions/shape_position/) | Die Formposition definiert, wo die Form im Dokumentlayout dargestellt werden soll. Nur für Word‑Dokumente verfügbar. |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/imagesignoptions/size_measure_type/) | Der Messungstyp (Pixel, Prozente oder Millimeter) für die Eigenschaften Width und Height. |
| [stretch](/signature/python-net/groupdocs.signature.options/imagesignoptions/stretch/) | Der Dehnungsmodus auf der Dokumentenseite. |
| [top](/signature/python-net/groupdocs.signature.options/imagesignoptions/top/) | Die obere Y‑Position der Signatur auf der Dokumentenseite in Messwerten (Pixel, Prozente oder Millimeter) wie durch `MeasureType` LocationMeasureType definiert. Funktioniert, wenn die vertikale Ausrichtung nicht angegeben ist. |
| [transparency](/signature/python-net/groupdocs.signature.options/imagesignoptions/transparency/) | Die Transparenz der Signatur, von 0,0 (undurchsichtig) bis 1,0 (transparent), standardmäßig 0 (undurchsichtig). |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/imagesignoptions/vertical_alignment/) | Die vertikale Ausrichtung der Signatur auf der Dokumentenseite. |
| [width](/signature/python-net/groupdocs.signature.options/imagesignoptions/width/) | Die Breite der Signatur auf der Dokumentenseite in Messwerten (Pixel, Prozente oder Millimeter `MeasureType` Größen‑Messtyp). |
| [all_pages](/signature/python-net/groupdocs.signature.options/signoptions/all_pages/) | Die Signatur wird auf allen Dokumentenseiten platziert. (geerbt von [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [appearance](/signature/python-net/groupdocs.signature.options/signoptions/appearance/) | Das zusätzliche Signatur‑Aussehen. (geerbt von [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [document_type](/signature/python-net/groupdocs.signature.options/signoptions/document_type/) | Der Dokumenttyp der Signaturoptionen (`DocumentType`). (geerbt von [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/signoptions/extensions/) | Die Signatur‑Erweiterungen. (geerbt von [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [hash_algorithm](/signature/python-net/groupdocs.signature.options/signoptions/hash_algorithm/) | Der Hash‑Algorithmus, der für kryptografische Vorgänge verwendet wird. Unterstützt ausschließlich für digitale Signaturen in PDF‑Dateien. (geerbt von [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/signoptions/page_number/) | Die Dokumentenseitenzahl zum Signieren. (geerbt von [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/signoptions/pages_setup/) | Die Optionen, um die zu signierenden Seiten anzugeben. (geerbt von [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [signature_type](/signature/python-net/groupdocs.signature.options/signoptions/signature_type/) | Der Signaturtyp (`SignatureType`). (geerbt von [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [zorder](/signature/python-net/groupdocs.signature.options/signoptions/zorder/) | Die Z‑Reihenfolge‑Position der Textsignatur, die die Anzeigereihenfolge überlappender Signaturen bestimmt. (geerbt von [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |

### Beispiel

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import ImageSignOptions

def sign_with_image_signature():
    with Signature("sample.pdf") as signature:
        # Erstelle Bildsignatur‑Optionen mit der Bilddatei
        options = ImageSignOptions("signature.jpg")
        # Setze Signaturposition und -größe
        options.left = 100
        options.top = 400
        options.width = 120
        options.height = 100

        result = signature.sign("signed_image.pdf", options)
        print(f"Signed with {len(result.succeeded)} image signature(s)")
```

### Guides
Aufgabenleitfäden, die `ImageSignOptions` verwenden:

* [eSign Document with Image Signature](/signature/python-net/guides/esign-document-with-image-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)

### Siehe auch
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
