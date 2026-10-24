---
title: "StampSignOptions klasse"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Stelt de stempelhandtekeningopties voor."
type: docs
url: /nl/python-net/groupdocs.signature.options/stampsignoptions/
is_root: false
weight: 570
---


## StampSignOptions class

Stelt de stempelhandtekeningopties voor.

Meer informatie:
- Basic usage of creating Stamp electronic signature by GroupDocs.Signature: How to eSign document with Stamp signature (https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Stamp+signature)
- Advanced usage of settings of Stamp electronic signature with GroupDocs.Signature: Advanced usage to eSign document with Stamp signature and additional settings (https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Stamp+signature+-+advanced)

Het StampSignOptions-type biedt de volgende leden:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/stampsignoptions/__init__/) | Initialiseert een nieuwe instantie van de StampSignOptions-klasse met standaardwaarden. |
| [__init__](/signature/python-net/groupdocs.signature.options/stampsignoptions/__init__/#left-top-width-height) | Initialiseert een nieuwe instantie van de StampSignOptions-klasse met uitlijningsopties. |

### Methoden
| Methode | Beschrijving |
| :- | :- |
| [dispose](/signature/python-net/groupdocs.signature.options/imagesignoptions/dispose/) | Wis interne bronnen. (geërfd van [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |
| [from_base64](/signature/python-net/groupdocs.signature.options/imagesignoptions/from_base64/) | Maakt een nieuw ImageSignOptions-exemplaar met een vooraf gedefinieerde afbeelding uit een Base64‑string. (geërfd van [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [background](/signature/python-net/groupdocs.signature.options/stampsignoptions/background/) | De achtergrond van de stempel. |
| [background_color_crop_type](/signature/python-net/groupdocs.signature.options/stampsignoptions/background_color_crop_type/) | Het bijsnijdtype van de achtergrondkleur van de handtekening. |
| [background_image_crop_type](/signature/python-net/groupdocs.signature.options/stampsignoptions/background_image_crop_type/) | Het bijsnijdtype van de achtergrondafbeelding van de handtekening. |
| [height](/signature/python-net/groupdocs.signature.options/stampsignoptions/height/) | De hoogte van het handtekeninggebied op de documentpagina in meeteenheden (pixels, procenten of millimeters). |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/stampsignoptions/horizontal_alignment/) | De horizontale uitlijning van de afbeelding op een documentpagina. |
| [inner_lines](/signature/python-net/groupdocs.signature.options/stampsignoptions/inner_lines/) | De lijst met binnenste lijnen weergegeven als een reeks rechthoeken. |
| [left](/signature/python-net/groupdocs.signature.options/stampsignoptions/left/) | De linkse X-positie van het handtekeninggebied op de documentpagina in meeteenheden (pixels, procenten of millimeters). Zie `MeasureType` `LocationMeasureType`. |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/stampsignoptions/location_measure_type/) | Het meettype (pixels, procenten of millimeters) voor de left en top eigenschappen. |
| [margin](/signature/python-net/groupdocs.signature.options/stampsignoptions/margin/) | De ruimte die standaard wordt opgegeven tussen de afbeelding en de documentranden (werkt als horizontale of verticale uitlijning is opgegeven). |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/stampsignoptions/margin_measure_type/) | Het type marge‑meting (pixels, procenten of millimeters). |
| [outer_lines](/signature/python-net/groupdocs.signature.options/stampsignoptions/outer_lines/) | De lijst met buitenste lijnen weergegeven als concentrische cirkels. |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/stampsignoptions/rotation_angle/) | De rotatiehoek met de klok mee. |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/stampsignoptions/size_measure_type/) | Het meettype (pixels, procenten of millimeters) voor de eigenschappen Width en Height. |
| [stamp_type](/signature/python-net/groupdocs.signature.options/stampsignoptions/stamp_type/) | Het stempeltype. Standaard is `Round`. |
| [stretch](/signature/python-net/groupdocs.signature.options/stampsignoptions/stretch/) | De uitrekmodus op de documentpagina. |
| [top](/signature/python-net/groupdocs.signature.options/stampsignoptions/top/) | De bovenste Y-positie van het handtekeninggebied op de documentpagina in meeteenheden (pixels, procenten of millimeters). Zie `MeasureType` `LocationMeasureType`. |
| [transparency](/signature/python-net/groupdocs.signature.options/stampsignoptions/transparency/) | De transparantie van de stempelhandtekening. De waarde varieert van 0.0 tot 1.0, met een standaardwaarde van 0. |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/stampsignoptions/vertical_alignment/) | De verticale uitlijning van de stempel op een documentpagina. |
| [width](/signature/python-net/groupdocs.signature.options/stampsignoptions/width/) | De breedte van het handtekeninggebied op de documentpagina in meetwaarden (pixels, procenten of millimeters). De meeteenheid wordt gedefinieerd door `MeasureType` SizeMeasureType. |
| [all_pages](/signature/python-net/groupdocs.signature.options/signoptions/all_pages/) | De handtekening wordt op alle documentpagina's geplaatst. (geërfd van [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [appearance](/signature/python-net/groupdocs.signature.options/signoptions/appearance/) | Het aanvullende handtekeninguiterlijk. (geërfd van [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [border](/signature/python-net/groupdocs.signature.options/imagesignoptions/border/) | De randinstellingen voor de afbeeldingondertekening. (geërfd van [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |
| [document_type](/signature/python-net/groupdocs.signature.options/signoptions/document_type/) | Het documenttype van de handtekeningopties (`DocumentType`). (geërfd van [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/signoptions/extensions/) | De handtekeningextensies. (geërfd van [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [hash_algorithm](/signature/python-net/groupdocs.signature.options/signoptions/hash_algorithm/) | Het hash‑algoritme dat moet worden gebruikt voor cryptografische bewerkingen. Exclusief ondersteund voor digitale handtekeningen in PDF‑bestanden. (geërfd van [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [image_file_path](/signature/python-net/groupdocs.signature.options/imagesignoptions/image_file_path/) | Het bestandspad van de ondertekeningsafbeelding, alleen gebruikt als `image_stream` niet is opgegeven. (geërfd van [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |
| [image_stream](/signature/python-net/groupdocs.signature.options/imagesignoptions/image_stream/) | De ondertekenings‑afbeeldingsstroom. Indien opgegeven, wordt deze altijd gebruikt in plaats van ImageFilePath. (geërfd van [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/signoptions/page_number/) | Het paginanummer van het document voor ondertekening. (geërfd van [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/signoptions/pages_setup/) | De opties om pagina's op te geven die moeten worden ondertekend. (geërfd van [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [rectangle](/signature/python-net/groupdocs.signature.options/imagesignoptions/rectangle/) | De rechthoek van het gebied om de afbeelding op het document te plaatsen. (geërfd van [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/imagesignoptions/shape_position/) | De vormpositie bepaalt waar de vorm moet worden weergegeven in de documentlay-out. Alleen beschikbaar voor Word‑documenten. (geërfd van [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |
| [signature_type](/signature/python-net/groupdocs.signature.options/signoptions/signature_type/) | Het handtekeningtype (`SignatureType`). (geërfd van [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [zorder](/signature/python-net/groupdocs.signature.options/signoptions/zorder/) | De Z‑orde positie van de tekshandtekening, die de weergavevolgorde van overlappende handtekeningen bepaalt. (geërfd van [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |

### Voorbeeld

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import StampSignOptions

with Signature("sample.docx") as signature:
    options = StampSignOptions()
    options.left = 380
    options.top = 520
    options.width = 160
    options.height = 160
    # configureer aanvullende stempelopties indien nodig
    signature.sign(options)
```

### Zie ook
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
