---
title: "QrCodeSignOptions klasse"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Vertegenwoordigt de QR-codehandtekeningopties."
type: docs
url: /nl/python-net/groupdocs.signature.options/qrcodesignoptions/
is_root: false
weight: 480
---


## QrCodeSignOptions class

Vertegenwoordigt de QR-codehandtekeningopties.

- Basic usage of creating QR-Code electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/eSign+document+with+QR-code+signature
- Advanced usage of settings of QR-Code electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Sign+document+with+QR-code+signature+-+advanced

Het type QrCodeSignOptions exposeert de volgende leden:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/__init__/) | Initialiseert een nieuw exemplaar van de QRCodeSignOptions‑klasse met standaardwaarden. |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/__init__/#text) | Initialiseert een QR‑codehandtekeningopties‑instantie met de opgegeven tekst. |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/__init__/#text-encode_type) | Initialiseert een nieuw exemplaar van de QrCodeSignOptions‑klasse met tekst. |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [code_text_alignment](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/code_text_alignment/) | De uitlijning van tekst in de resulterende QR‑code‑afbeelding, standaardwaarde is None. |
| [data](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/data/) | Het aangepaste object om te serialiseren naar QR‑Code‑inhoud. |
| [data_encryption](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/data_encryption/) | De implementatie van gegevensversleuteling die wordt gebruikt om QR‑codehandtekeningtekst of -gegevens te coderen en decoderen. |
| [encode_type](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/encode_type/) | Het QR-Code type. |
| [fore_color](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/fore_color/) | De voorgrondkleur van QR code-balken; het gebruik van deze eigenschap kan verificatieproblemen veroorzaken, dus gebruik deze voorzichtig. |
| [height](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/height/) | De hoogte van het handtekeninggebied op de documentpagina in meeteenheden (pixels, procenten of millimeters; zie `MeasureType` SizeMeasureType). |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/horizontal_alignment/) | De horizontale uitlijning van de QR code op een documentpagina. |
| [inner_margins](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/inner_margins/) | De ruimte tussen QR code-elementen en de randen van de resulterende afbeelding. |
| [left](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/left/) | De linker X-positie van het handtekeninggebied op een documentpagina in meeteenheden (pixels, procenten of millimeters). |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/location_measure_type/) | Het meettype (pixels, procenten of millimeters) voor de linker- en bovenste eigenschappen. |
| [logo_file_path](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/logo_file_path/) | De bestandsnaam van het QR-code logo‑afbeelding. |
| [logo_stream](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/logo_stream/) | De QR-code logo‑afbeeldingsstroom. |
| [margin](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/margin/) | De ruimte die standaard wordt gespecificeerd tussen afbeelding- en documentranden (werkt als horizontale of verticale uitlijning is opgegeven). |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/margin_measure_type/) | Het type marge‑meting (pixels, procenten of millimeters). |
| [return_content](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/return_content/) | De vlag om de QR-Code afbeeldinginhoud van een handtekening op een documentpagina op te halen. |
| [return_content_type](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/return_content_type/) | Het bestandstype van de geretourneerde afbeeldinginhoud van de QR‑Code handtekening wanneer de `return_content` eigenschap is ingeschakeld. |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/rotation_angle/) | De rotatiehoek in graden, met de klok mee. |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/size_measure_type/) | Het meettype (pixels, procenten of millimeters) voor de eigenschappen Width en Height. |
| [stretch](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/stretch/) | De uitrekmodus op de documentpagina. |
| [top](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/top/) | De bovenste Y-positie van het handtekeninggebied op een documentpagina in meeteenheden (pixels, procenten of millimeters). De eenheid wordt gedefinieerd door de `LocationMeasureType` eigenschap van type `MeasureType`. |
| [transparency](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/transparency/) | De transparantie van de QR code-handtekening. De waarde varieert van 0,0 tot 1,0, met standaard 0. |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/vertical_alignment/) | De verticale uitlijning van de afbeelding op een documentpagina. |
| [width](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/width/) | De breedte van het handtekeninggebied op de documentpagina in meetwaarden (pixels, procent of millimeters zoals gedefinieerd door `MeasureType`). |
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
from groupdocs.signature.options import QrCodeSignOptions
from groupdocs.signature.domain import (
    Background, Border, DashStyle, HorizontalAlignment, Padding,
    QrCodeTypes, VerticalAlignment)
from groupdocs.pydrawing import Color

def sign_with_qr_code_signature_advanced():
    with Signature("sample.pdf") as signature:
        # Geef de tekst en het QR code-type door aan de constructor
        options = QrCodeSignOptions("https://www.example.com/verify-document", QrCodeTypes.QR)

        # Plaats de QR code in de rechteronderhoek van de pagina
        options.width = 120
        options.height = 120
        options.horizontal_alignment = HorizontalAlignment.RIGHT
        options.vertical_alignment = VerticalAlignment.BOTTOM
        options.margin = Padding(right=40, bottom=60)

        # Modulkleur, achtergrond en een gestippelde rand met wat ruimte binnenin
        options.fore_color = Color.dark_blue
        background = Background()
        background.color = Color.light_yellow
        options.background = background
        border = Border()
        border.color = Color.dark_blue
        border.dash_style = DashStyle.DOT
        border.weight = 2
        border.visible = True

        signature.sign("signed.pdf", options)
```

### Guides
Taakgidsen die `QrCodeSignOptions` gebruiken:

* [eSign Document with QR Code Signature](/signature/python-net/guides/esign-document-with-qr-code-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)
* [Generate signatures preview](/signature/python-net/guides/generate-signatures-preview/)

### Zie ook
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
