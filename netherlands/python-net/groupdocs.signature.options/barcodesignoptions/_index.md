---
title: "BarcodeSignOptions klasse"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Vertegenwoordigt de barcode-handtekeningopties."
type: docs
url: /nl/python-net/groupdocs.signature.options/barcodesignoptions/
is_root: false
weight: 20
---


## BarcodeSignOptions class

Vertegenwoordigt de barcode-handtekeningopties.

Meer informatie

- Basic usage of creating Barcode electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Barcode+signature
- Advanced usage of settings of Barcode electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Barcode+signature+and+additional+settings

De BarcodeSignOptions type geeft de volgende leden weer:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodesignoptions/__init__/) | Initialiseert een nieuw exemplaar van de BarcodeSignOptions klasse met standaardwaarden. |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodesignoptions/__init__/#text) | Initialiseert een nieuw exemplaar van de BarcodeSignOptions klasse met tekst. |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodesignoptions/__init__/#text-encode_type) | Initialiseert een nieuw exemplaar van de BarcodeSignOptions klasse met tekst. |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [code_text_alignment](/signature/python-net/groupdocs.signature.options/barcodesignoptions/code_text_alignment/) | De uitlijning van tekst in de resulterende barcode‑afbeelding. Standaardwaarde is Geen. |
| [encode_type](/signature/python-net/groupdocs.signature.options/barcodesignoptions/encode_type/) | Het barcode‑type. |
| [fore_color](/signature/python-net/groupdocs.signature.options/barcodesignoptions/fore_color/) | De voorgrondkleur van de barcode‑balken; het gebruik ervan kan verificatieproblemen veroorzaken, dus gebruik het voorzichtig. |
| [height](/signature/python-net/groupdocs.signature.options/barcodesignoptions/height/) | De hoogte van het handtekeninggebied op de documentpagina in meeteenheden (pixels, procenten of millimeters). Zie `MeasureType` voor het type maat. |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/barcodesignoptions/horizontal_alignment/) | De horizontale uitlijning van de afbeelding op een documentpagina. |
| [inner_margins](/signature/python-net/groupdocs.signature.options/barcodesignoptions/inner_margins/) | De ruimte tussen barcode‑elementen en de randen van de resulterende afbeelding. |
| [left](/signature/python-net/groupdocs.signature.options/barcodesignoptions/left/) | De linker X‑positie van het handtekeninggebied op de documentpagina, uitgedrukt in meeteenheden (pixels, procenten of millimeters). Zie `MeasureType`. |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/barcodesignoptions/location_measure_type/) | Het meettype (pixels, procenten of millimeters) voor de linker- en bovenste eigenschappen. |
| [margin](/signature/python-net/groupdocs.signature.options/barcodesignoptions/margin/) | De ruimte die standaard wordt gespecificeerd tussen de afbeelding en de documentranden (geldt wanneer horizontale of verticale uitlijning is ingesteld). |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/barcodesignoptions/margin_measure_type/) | Het type marge‑meting (pixels, procenten of millimeters). |
| [return_content](/signature/python-net/groupdocs.signature.options/barcodesignoptions/return_content/) | De vlag die aangeeft of de barcode‑afbeeldingsinhoud van een handtekening op een documentpagina moet worden opgehaald. |
| [return_content_type](/signature/python-net/groupdocs.signature.options/barcodesignoptions/return_content_type/) | Het bestandstype van de geretourneerde afbeeldingsinhoud van de Barcode‑handtekening wanneer de eigenschap `return_content` is ingeschakeld. |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/barcodesignoptions/rotation_angle/) | De rotatiehoek met de klok mee. |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/barcodesignoptions/size_measure_type/) | Het meettype (pixels, procenten of millimeters) voor de eigenschappen Width en Height. |
| [stretch](/signature/python-net/groupdocs.signature.options/barcodesignoptions/stretch/) | De uitrekmodus op de documentpagina. |
| [top](/signature/python-net/groupdocs.signature.options/barcodesignoptions/top/) | De bovenste Y‑positie van het handtekeninggebied op de documentpagina in meeteenheden (pixels, procenten of millimeters). Zie `MeasureType` LocationMeasureType. |
| [transparency](/signature/python-net/groupdocs.signature.options/barcodesignoptions/transparency/) | De transparantie van de barcode‑handtekening, variërend van 0,0 (volledig ondoorzichtig) tot 1,0 (volledig transparant); standaard is 0. |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/barcodesignoptions/vertical_alignment/) | De verticale uitlijning van de barcode‑afbeelding op een documentpagina. |
| [width](/signature/python-net/groupdocs.signature.options/barcodesignoptions/width/) | De breedte van het handtekeninggebied op de documentpagina in meetwaarden (pixels, procenten of millimeters) zoals gedefinieerd door `MeasureType`. |
| [all_pages](/signature/python-net/groupdocs.signature.options/signoptions/all_pages/) | De handtekening wordt op alle documentpagina's geplaatst. (geërfd van [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [appearance](/signature/python-net/groupdocs.signature.options/signoptions/appearance/) | Het aanvullende handtekeninguiterlijk. (geërfd van [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [background](/signature/python-net/groupdocs.signature.options/textsignoptions/background/) | De achtergrondinstellingen van de handtekening. (inherited from [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [border](/signature/python-net/groupdocs.signature.options/textsignoptions/border/) | De randinstellingen. (inherited from [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [document_type](/signature/python-net/groupdocs.signature.options/signoptions/document_type/) | Het documenttype van de handtekeningopties (`DocumentType`). (geërfd van [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/signoptions/extensions/) | De handtekeningextensies. (geërfd van [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [font](/signature/python-net/groupdocs.signature.options/textsignoptions/font/) | Het lettertype van de handtekening. (inherited from [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [form_text_field_title](/signature/python-net/groupdocs.signature.options/textsignoptions/form_text_field_title/) | De titel van het tekstformulierveld waarin de teksthandtekening moet worden geplaatst. Kan alleen worden gebruikt wanneer `signature_implementation` is ingesteld op `TextSignatureImplementation.FORM_FIELD`. (inherited from [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [form_text_field_type](/signature/python-net/groupdocs.signature.options/textsignoptions/form_text_field_type/) | Het type formulierveld waarin de teksthandtekening moet worden geplaatst. Deze eigenschap is alleen van toepassing wanneer `signature_implementation` is ingesteld op `TextSignatureImplementation.FORM_FIELD` (d.w.z. TextToFormField). De standaardwaarde is `FormTextFieldType.ALL_TEXT_TYPES`. (inherited from [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [hash_algorithm](/signature/python-net/groupdocs.signature.options/signoptions/hash_algorithm/) | Het hash‑algoritme dat moet worden gebruikt voor cryptografische bewerkingen. Exclusief ondersteund voor digitale handtekeningen in PDF‑bestanden. (geërfd van [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [native](/signature/python-net/groupdocs.signature.options/textsignoptions/native/) | Het native attribuut. (inherited from [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/signoptions/page_number/) | Het paginanummer van het document voor ondertekening. (geërfd van [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/signoptions/pages_setup/) | De opties om pagina's op te geven die moeten worden ondertekend. (geërfd van [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/textsignoptions/shape_position/) | De vormpositie bepaalt waar de vorm moet worden weergegeven in de documentlay-out. Alleen beschikbaar voor Word‑documenten. (inherited from [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [shape_type](/signature/python-net/groupdocs.signature.options/textsignoptions/shape_type/) | Het type vorm om tekst in te plaatsen. (inherited from [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [signature_id](/signature/python-net/groupdocs.signature.options/textsignoptions/signature_id/) | De unieke ID van de handtekening, bruikbaar in verificatie‑opties en alleen ondersteund voor PDF‑documenten. (inherited from [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [signature_implementation](/signature/python-net/groupdocs.signature.options/textsignoptions/signature_implementation/) | Het type teksthandtekeningimplementatie. (geërfd van [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [signature_type](/signature/python-net/groupdocs.signature.options/signoptions/signature_type/) | Het handtekeningtype (`SignatureType`). (geërfd van [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [text](/signature/python-net/groupdocs.signature.options/textsignoptions/text/) | De tekst van de handtekening. (geërfd van [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [text_horizontal_alignment](/signature/python-net/groupdocs.signature.options/textsignoptions/text_horizontal_alignment/) | De horizontale uitlijning van tekst binnen een handtekening, alleen ondersteund voor Image- en Annotation-handtekeningimplementaties (zie `TextSignatureImplementation` SignatureImplementation‑eigenschap). (geërfd van [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [text_vertical_alignment](/signature/python-net/groupdocs.signature.options/textsignoptions/text_vertical_alignment/) | De verticale uitlijning van tekst binnen een handtekening. (geërfd van [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [zorder](/signature/python-net/groupdocs.signature.options/signoptions/zorder/) | De Z‑orde positie van de tekshandtekening, die de weergavevolgorde van overlappende handtekeningen bepaalt. (geërfd van [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |

### Voorbeeld

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import BarcodeSignOptions
from groupdocs.signature.domain import (
    Background, BarcodeTypes, Border, CodeTextAlignment,
    HorizontalAlignment, Padding, VerticalAlignment)
from groupdocs.pydrawing import Color

def sign_with_barcode():
    with Signature("sample.pdf") as signature:
        options = BarcodeSignOptions("JohnSmith", BarcodeTypes.CODE128)
        options.width = 220
        options.height = 80
        options.horizontal_alignment = HorizontalAlignment.RIGHT
        options.vertical_alignment = VerticalAlignment.BOTTOM
        options.margin = Padding(right=40, bottom=60)
        options.fore_color = Color.dark_blue
        options.code_text_alignment = CodeTextAlignment.BELOW
        options.inner_margins = Padding(5)

        background = Background()
        background.color = Color.light_yellow
        options.background = background

        border = Border()
        options.border = border

        signature.sign("signed.pdf", options)
```

### Guides
Taakgidsen die `BarcodeSignOptions` gebruiken:

* [eSign Document with Barcode Signature](/signature/python-net/guides/esign-document-with-barcode-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)
* [Generate signatures preview](/signature/python-net/guides/generate-signatures-preview/)

### Zie ook
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
