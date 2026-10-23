---
title: "Klasse StampSignOptions"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Stellt die Stempel‑Signaturoptionen dar."
type: docs
url: /de/python-net/groupdocs.signature.options/stampsignoptions/
is_root: false
weight: 570
---


## StampSignOptions class

Stellt die Stempel‑Signaturoptionen dar.

Mehr erfahren:
- Basic usage of creating Stamp electronic signature by GroupDocs.Signature: How to eSign document with Stamp signature (https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Stamp+signature)
- Advanced usage of settings of Stamp electronic signature with GroupDocs.Signature: Advanced usage to eSign document with Stamp signature and additional settings (https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Stamp+signature+-+advanced)

Der Typ StampSignOptions stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/stampsignoptions/__init__/) | Initialisiert eine neue Instanz der Klasse StampSignOptions mit Standardwerten. |
| [__init__](/signature/python-net/groupdocs.signature.options/stampsignoptions/__init__/#left-top-width-height) | Initialisiert eine neue Instanz der Klasse StampSignOptions mit Ausrichtungsoptionen. |

### Methoden
| Methode | Beschreibung |
| :- | :- |
| [dispose](/signature/python-net/groupdocs.signature.options/imagesignoptions/dispose/) | Löscht interne Ressourcen. (geerbt von [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |
| [from_base64](/signature/python-net/groupdocs.signature.options/imagesignoptions/from_base64/) | Erstellt eine neue ImageSignOptions-Instanz mit einem vordefinierten Bild aus einem Base64-String. (geerbt von [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [background](/signature/python-net/groupdocs.signature.options/stampsignoptions/background/) | Der Hintergrund des Stempels. |
| [background_color_crop_type](/signature/python-net/groupdocs.signature.options/stampsignoptions/background_color_crop_type/) | Der Zuschnitttyp der Hintergrundfarbe der Signatur. |
| [background_image_crop_type](/signature/python-net/groupdocs.signature.options/stampsignoptions/background_image_crop_type/) | Der Zuschnitttyp des Hintergrundbildes der Signatur. |
| [height](/signature/python-net/groupdocs.signature.options/stampsignoptions/height/) | Die Höhe des Signaturbereichs auf der Dokumentenseite in Maßeinheiten (Pixel, Prozente oder Millimeter). |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/stampsignoptions/horizontal_alignment/) | Die horizontale Ausrichtung des Bildes auf einer Dokumentseite. |
| [inner_lines](/signature/python-net/groupdocs.signature.options/stampsignoptions/inner_lines/) | Die Liste der inneren Linien, dargestellt als Satz von Rechtecken. |
| [left](/signature/python-net/groupdocs.signature.options/stampsignoptions/left/) | Die linke X-Position des Signaturbereichs auf der Dokumentenseite in Maßeinheiten (Pixel, Prozente oder Millimeter). Siehe `MeasureType` `LocationMeasureType`. |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/stampsignoptions/location_measure_type/) | Der Maßtyp (Pixel, Prozente oder Millimeter) für die linken und oberen Eigenschaften. |
| [margin](/signature/python-net/groupdocs.signature.options/stampsignoptions/margin/) | Der standardmäßig angegebene Abstand zwischen Bild und Dokumentenkanten (funktioniert, wenn horizontale oder vertikale Ausrichtung angegeben ist). |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/stampsignoptions/margin_measure_type/) | Der Messungstyp für den Rand (Pixel, Prozente oder Millimeter). |
| [outer_lines](/signature/python-net/groupdocs.signature.options/stampsignoptions/outer_lines/) | Die Liste der äußeren Linien, dargestellt als konzentrische Kreise. |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/stampsignoptions/rotation_angle/) | Der Rotationswinkel im Uhrzeigersinn. |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/stampsignoptions/size_measure_type/) | Der Messungstyp (Pixel, Prozente oder Millimeter) für die Eigenschaften Width und Height. |
| [stamp_type](/signature/python-net/groupdocs.signature.options/stampsignoptions/stamp_type/) | Der Stempeltyp. Standard ist `Round`. |
| [stretch](/signature/python-net/groupdocs.signature.options/stampsignoptions/stretch/) | Der Dehnungsmodus auf der Dokumentenseite. |
| [top](/signature/python-net/groupdocs.signature.options/stampsignoptions/top/) | Die obere Y‑Position des Signaturbereichs auf der Dokumentenseite in Maßeinheiten (Pixel, Prozent oder Millimeter). Siehe `MeasureType` `LocationMeasureType`. |
| [transparency](/signature/python-net/groupdocs.signature.options/stampsignoptions/transparency/) | Die Transparenz der Stempel‑Signatur. Der Wert liegt im Bereich von 0,0 bis 1,0, wobei der Standardwert 0 ist. |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/stampsignoptions/vertical_alignment/) | Die vertikale Ausrichtung des Stempels auf einer Dokumentenseite. |
| [width](/signature/python-net/groupdocs.signature.options/stampsignoptions/width/) | Die Breite des Signaturbereichs auf der Dokumentenseite in Messwerten (Pixel, Prozent oder Millimeter). Die Maßeinheit wird durch `MeasureType` SizeMeasureType definiert. |
| [all_pages](/signature/python-net/groupdocs.signature.options/signoptions/all_pages/) | Die Signatur wird auf allen Dokumentenseiten platziert. (geerbt von [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [appearance](/signature/python-net/groupdocs.signature.options/signoptions/appearance/) | Das zusätzliche Signatur‑Aussehen. (geerbt von [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [border](/signature/python-net/groupdocs.signature.options/imagesignoptions/border/) | Die Rahmen‑Einstellungen für die Bildsignatur. (geerbt von [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |
| [document_type](/signature/python-net/groupdocs.signature.options/signoptions/document_type/) | Der Dokumenttyp der Signaturoptionen (`DocumentType`). (geerbt von [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/signoptions/extensions/) | Die Signatur‑Erweiterungen. (geerbt von [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [hash_algorithm](/signature/python-net/groupdocs.signature.options/signoptions/hash_algorithm/) | Der Hash‑Algorithmus, der für kryptografische Vorgänge verwendet wird. Unterstützt ausschließlich für digitale Signaturen in PDF‑Dateien. (geerbt von [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [image_file_path](/signature/python-net/groupdocs.signature.options/imagesignoptions/image_file_path/) | Der Dateipfad des Signatur‑Bildes, der nur verwendet wird, wenn `image_stream` nicht angegeben ist. (geerbt von [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |
| [image_stream](/signature/python-net/groupdocs.signature.options/imagesignoptions/image_stream/) | Der Signatur‑Bild‑Stream. Wenn angegeben, wird er stets anstelle von ImageFilePath verwendet. (geerbt von [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/signoptions/page_number/) | Die Dokumentenseitenzahl zum Signieren. (geerbt von [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/signoptions/pages_setup/) | Die Optionen, um die zu signierenden Seiten anzugeben. (geerbt von [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [rectangle](/signature/python-net/groupdocs.signature.options/imagesignoptions/rectangle/) | Das Rechteck des Bereichs, in dem das Bild im Dokument platziert wird. (geerbt von [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/imagesignoptions/shape_position/) | Die Position der Form definiert, wo die Form im Dokumentlayout dargestellt werden soll. Nur für Word-Dokumente verfügbar. (geerbt von [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |
| [signature_type](/signature/python-net/groupdocs.signature.options/signoptions/signature_type/) | Der Signaturtyp (`SignatureType`). (geerbt von [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [zorder](/signature/python-net/groupdocs.signature.options/signoptions/zorder/) | Die Z‑Reihenfolge‑Position der Textsignatur, die die Anzeigereihenfolge überlappender Signaturen bestimmt. (geerbt von [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |

### Beispiel

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import StampSignOptions

with Signature("sample.docx") as signature:
    options = StampSignOptions()
    options.left = 380
    options.top = 520
    options.width = 160
    options.height = 160
    # Zusätzliche Stempeloptionen nach Bedarf konfigurieren
    signature.sign(options)
```

### Siehe auch
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
