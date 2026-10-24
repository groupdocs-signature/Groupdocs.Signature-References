---
title: "StampSignOptions-klass"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Representerar stämpelsignaturalternativen."
type: docs
url: /sv/python-net/groupdocs.signature.options/stampsignoptions/
is_root: false
weight: 570
---


## StampSignOptions class

Representerar stämpelsignaturalternativen.

Läs mer:
- Basic usage of creating Stamp electronic signature by GroupDocs.Signature: How to eSign document with Stamp signature (https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Stamp+signature)
- Advanced usage of settings of Stamp electronic signature with GroupDocs.Signature: Advanced usage to eSign document with Stamp signature and additional settings (https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Stamp+signature+-+advanced)

StampSignOptions-typen visar följande medlemmar:

### Konstruktörer
| Konstruktor | Beskrivning |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/stampsignoptions/__init__/) | Initierar en ny instans av StampSignOptions-klassen med standardvärden. |
| [__init__](/signature/python-net/groupdocs.signature.options/stampsignoptions/__init__/#left-top-width-height) | Initierar en ny instans av StampSignOptions-klassen med justeringsalternativ. |

### Metoder
| Metod | Beskrivning |
| :- | :- |
| [dispose](/signature/python-net/groupdocs.signature.options/imagesignoptions/dispose/) | Rensar interna resurser. (ärvd från [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |
| [from_base64](/signature/python-net/groupdocs.signature.options/imagesignoptions/from_base64/) | Skapar en ny ImageSignOptions-instans med en fördefinierad bild från en Base64-sträng. (ärvd från [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [background](/signature/python-net/groupdocs.signature.options/stampsignoptions/background/) | Bakgrunden för stämpeln. |
| [background_color_crop_type](/signature/python-net/groupdocs.signature.options/stampsignoptions/background_color_crop_type/) | Bakgrundsfärgens beskärningstyp för signaturen. |
| [background_image_crop_type](/signature/python-net/groupdocs.signature.options/stampsignoptions/background_image_crop_type/) | Bakgrundsbildens beskärningstyp för signaturen. |
| [height](/signature/python-net/groupdocs.signature.options/stampsignoptions/height/) | Höjden på signaturområdet på dokumentsidan i måttenheter (pixlar, procent eller millimeter). |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/stampsignoptions/horizontal_alignment/) | Den horisontella justeringen av bilden på en dokumentsida. |
| [inner_lines](/signature/python-net/groupdocs.signature.options/stampsignoptions/inner_lines/) | Listan över inre linjer renderade som en uppsättning rektanglar. |
| [left](/signature/python-net/groupdocs.signature.options/stampsignoptions/left/) | Den vänstra X‑positionen för signaturområdet på dokumentsidan i måttenheter (pixlar, procent eller millimeter). Se `MeasureType` `LocationMeasureType`. |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/stampsignoptions/location_measure_type/) | Måtttypen (pixlar, procent eller millimeter) för vänster‑ och topp‑egenskaperna. |
| [margin](/signature/python-net/groupdocs.signature.options/stampsignoptions/margin/) | Utrymmet som som standard anges mellan bilden och dokumentets kanter (fungerar om horisontell eller vertikal justering anges). |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/stampsignoptions/margin_measure_type/) | Måtttypen för marginalen (pixlar, procent eller millimeter). |
| [outer_lines](/signature/python-net/groupdocs.signature.options/stampsignoptions/outer_lines/) | Listan över yttre linjer renderade som koncentriska cirklar. |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/stampsignoptions/rotation_angle/) | Rotationsvinkeln medurs. |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/stampsignoptions/size_measure_type/) | Måtttypen (pixlar, procent eller millimeter) för egenskaperna Width och Height. |
| [stamp_type](/signature/python-net/groupdocs.signature.options/stampsignoptions/stamp_type/) | Stämpeltypen. Standard är `Round`. |
| [stretch](/signature/python-net/groupdocs.signature.options/stampsignoptions/stretch/) | Sträckningsläget på dokumentsidan. |
| [top](/signature/python-net/groupdocs.signature.options/stampsignoptions/top/) | Den övre Y‑positionen för signaturområdet på dokumentsidan i måttenheter (pixlar, procent eller millimeter). Se `MeasureType` `LocationMeasureType`. |
| [transparency](/signature/python-net/groupdocs.signature.options/stampsignoptions/transparency/) | Genomskinligheten för stämpelsignaturen. Värdet varierar från 0,0 till 1,0, med standardvärdet 0. |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/stampsignoptions/vertical_alignment/) | Den vertikala justeringen av stämpeln på en dokumentsida. |
| [width](/signature/python-net/groupdocs.signature.options/stampsignoptions/width/) | Bredden på signaturområdet på dokumentsidan i mätningsvärden (pixlar, procent eller millimeter). Mätningsenheten definieras av `MeasureType` SizeMeasureType. |
| [all_pages](/signature/python-net/groupdocs.signature.options/signoptions/all_pages/) | Signaturen kommer att placeras på alla dokumentsidor. (ärvd från [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [appearance](/signature/python-net/groupdocs.signature.options/signoptions/appearance/) | Det ytterligare signaturutseendet. (ärvd från [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [border](/signature/python-net/groupdocs.signature.options/imagesignoptions/border/) | Kantinställningarna för bildsignaturen. (ärvd från [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |
| [document_type](/signature/python-net/groupdocs.signature.options/signoptions/document_type/) | Dokumenttypen för signaturalternativen (`DocumentType`). (ärvd från [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/signoptions/extensions/) | Signaturens tillägg. (ärvd från [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [hash_algorithm](/signature/python-net/groupdocs.signature.options/signoptions/hash_algorithm/) | Hash‑algoritmen som ska användas för kryptografiska operationer. Stöds uteslutande för digitala signaturer i PDF‑filer. (ärvd från [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [image_file_path](/signature/python-net/groupdocs.signature.options/imagesignoptions/image_file_path/) | Sökvägen till signaturbilden, används endast om `image_stream` inte är angivet. (ärvd från [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |
| [image_stream](/signature/python-net/groupdocs.signature.options/imagesignoptions/image_stream/) | Strömmen för signaturbilden. Om angiven används den alltid istället för ImageFilePath. (ärvd från [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/signoptions/page_number/) | Dokumentsidans nummer för signering. (ärvd från [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/signoptions/pages_setup/) | Alternativen för att ange vilka sidor som ska signeras. (ärvd från [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [rectangle](/signature/python-net/groupdocs.signature.options/imagesignoptions/rectangle/) | Rektangeln för området där bilden ska placeras i dokumentet. (ärvd från [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/imagesignoptions/shape_position/) | Formens position definierar var formen ska visas i dokumentlayouten. Endast tillgänglig för Word‑dokument. (ärvd från [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |
| [signature_type](/signature/python-net/groupdocs.signature.options/signoptions/signature_type/) | Signaturtypen (`SignatureType`). (ärvd från [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [zorder](/signature/python-net/groupdocs.signature.options/signoptions/zorder/) | Z‑ordningspositionen för textsignaturen, som bestämmer visningsordningen för överlappande signaturer. (ärvd från [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |

### Exempel

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import StampSignOptions

with Signature("sample.docx") as signature:
    options = StampSignOptions()
    options.left = 380
    options.top = 520
    options.width = 160
    options.height = 160
    # konfigurera ytterligare stämpelalternativ vid behov
    signature.sign(options)
```

### Se även
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
