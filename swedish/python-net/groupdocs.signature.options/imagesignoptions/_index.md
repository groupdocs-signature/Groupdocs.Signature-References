---
title: "Klassen ImageSignOptions"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Representerar bildsignaturalternativen."
type: docs
url: /sv/python-net/groupdocs.signature.options/imagesignoptions/
is_root: false
weight: 250
---


## ImageSignOptions class

Representerar bildsignaturalternativen.

Läs mer:
- Basic usage of creating Image electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Image+signature
- Advanced usage of settings of Image electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Image+signature+-+advanced

Typen ImageSignOptions visar följande medlemmar:

### Konstruktörer
| Konstruktor | Beskrivning |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/imagesignoptions/__init__/) | Initierar en ny instans av klassen ImageSignOptions med standardvärden. |
| [__init__](/signature/python-net/groupdocs.signature.options/imagesignoptions/__init__/#image_file_path) | Initierar ImageSignOptions med en bildfil. |
| [__init__](/signature/python-net/groupdocs.signature.options/imagesignoptions/__init__/#image_stream) | Initierar en ny ImageSignOptions-instans med en bildström. |

### Metoder
| Metod | Beskrivning |
| :- | :- |
| [dispose](/signature/python-net/groupdocs.signature.options/imagesignoptions/dispose/) | Rensar interna resurser. |
| [from_base64](/signature/python-net/groupdocs.signature.options/imagesignoptions/from_base64/#base_64_content) | Skapar en ny ImageSignOptions-instans med en fördefinierad bild från en Base64-sträng. |

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [border](/signature/python-net/groupdocs.signature.options/imagesignoptions/border/) | Kantinställningarna för bildsignaturen. |
| [height](/signature/python-net/groupdocs.signature.options/imagesignoptions/height/) | Höjden på signaturen på dokumentsidan i måttenheter (pixlar, procent eller millimeter; se `MeasureType` SizeMeasureType). |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/imagesignoptions/horizontal_alignment/) | Den horisontella justeringen av signaturen på dokumentsidan. |
| [image_file_path](/signature/python-net/groupdocs.signature.options/imagesignoptions/image_file_path/) | Filvägen till signaturbilden, används endast om `image_stream` inte är angivet. |
| [image_stream](/signature/python-net/groupdocs.signature.options/imagesignoptions/image_stream/) | Signaturens bildström. Om den anges används den alltid istället för ImageFilePath. |
| [left](/signature/python-net/groupdocs.signature.options/imagesignoptions/left/) | Den vänstra X‑positionen för signaturen på dokumentsidan i mätenheter (pixlar, procent eller millimeter). Fungerar om horisontell justering inte är angiven. Se `MeasureType` för platsens mättyp. |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/imagesignoptions/location_measure_type/) | Måtttypen (pixlar, procent eller millimeter) för vänster‑ och topp‑egenskaperna. |
| [margin](/signature/python-net/groupdocs.signature.options/imagesignoptions/margin/) | Avståndet mellan signaturen och dokumentets kanter. Fungerar endast om horisontell eller vertikal justering är angiven. |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/imagesignoptions/margin_measure_type/) | Måtttypen (pixlar, procent eller millimeter) för marginalen. |
| [rectangle](/signature/python-net/groupdocs.signature.options/imagesignoptions/rectangle/) | Rektangeln för området där bilden ska placeras i dokumentet. |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/imagesignoptions/rotation_angle/) | Rotationsvinkeln för signaturen på dokumentsidan (medurs). |
| [shape_position](/signature/python-net/groupdocs.signature.options/imagesignoptions/shape_position/) | Formens position definierar var formen ska visas i dokumentlayouten. Endast tillgänglig för Word‑dokument. |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/imagesignoptions/size_measure_type/) | Måtttypen (pixlar, procent eller millimeter) för egenskaperna Width och Height. |
| [stretch](/signature/python-net/groupdocs.signature.options/imagesignoptions/stretch/) | Sträckningsläget på dokumentsidan. |
| [top](/signature/python-net/groupdocs.signature.options/imagesignoptions/top/) | Den övre Y‑positionen för signaturen på dokumentsidan i mätenheter (pixlar, procent eller millimeter) enligt `MeasureType` LocationMeasureType. Fungerar om vertikal justering inte är angiven. |
| [transparency](/signature/python-net/groupdocs.signature.options/imagesignoptions/transparency/) | Signaturens transparens, från 0,0 (opak) till 1,0 (klar), standardvärdet är 0 (opak). |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/imagesignoptions/vertical_alignment/) | Den vertikala justeringen av signaturen på dokumentsidan. |
| [width](/signature/python-net/groupdocs.signature.options/imagesignoptions/width/) | Bredden på signaturen på dokumentsidan i mätenheter (pixlar, procent eller millimeter, `MeasureType` storleksmått). |
| [all_pages](/signature/python-net/groupdocs.signature.options/signoptions/all_pages/) | Signaturen kommer att placeras på alla dokumentsidor. (ärvd från [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [appearance](/signature/python-net/groupdocs.signature.options/signoptions/appearance/) | Det ytterligare signaturutseendet. (ärvd från [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [document_type](/signature/python-net/groupdocs.signature.options/signoptions/document_type/) | Dokumenttypen för signaturalternativen (`DocumentType`). (ärvd från [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/signoptions/extensions/) | Signaturens tillägg. (ärvd från [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [hash_algorithm](/signature/python-net/groupdocs.signature.options/signoptions/hash_algorithm/) | Hash‑algoritmen som ska användas för kryptografiska operationer. Stöds uteslutande för digitala signaturer i PDF‑filer. (ärvd från [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/signoptions/page_number/) | Dokumentsidans nummer för signering. (ärvd från [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/signoptions/pages_setup/) | Alternativen för att ange vilka sidor som ska signeras. (ärvd från [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [signature_type](/signature/python-net/groupdocs.signature.options/signoptions/signature_type/) | Signaturtypen (`SignatureType`). (ärvd från [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [zorder](/signature/python-net/groupdocs.signature.options/signoptions/zorder/) | Z‑ordningspositionen för textsignaturen, som bestämmer visningsordningen för överlappande signaturer. (ärvd från [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |

### Exempel

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import ImageSignOptions

def sign_with_image_signature():
    with Signature("sample.pdf") as signature:
        # Skapa bildsignaturalternativ med bildfilen
        options = ImageSignOptions("signature.jpg")
        # Ange signaturens position och storlek
        options.left = 100
        options.top = 400
        options.width = 120
        options.height = 100

        result = signature.sign("signed_image.pdf", options)
        print(f"Signed with {len(result.succeeded)} image signature(s)")
```

### Guides
Uppgiftsguider som använder `ImageSignOptions`:

* [eSign Document with Image Signature](/signature/python-net/guides/esign-document-with-image-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)

### Se även
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
