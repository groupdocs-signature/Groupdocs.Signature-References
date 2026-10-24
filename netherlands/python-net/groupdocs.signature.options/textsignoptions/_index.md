---
title: "TextSignOptions klasse"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Stelt de teksthandtekeningopties voor."
type: docs
url: /nl/python-net/groupdocs.signature.options/textsignoptions/
is_root: false
weight: 590
---


## TextSignOptions class

Stelt de teksthandtekeningopties voor.

Meer informatie

- Basic usage of creating Text electronic signature by GroupDocs.Signature: [How to eSign document with Text signature](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Text+signature)
- Advanced usage of settings of Text electronic signature with GroupDocs.Signature: [Advanced usage to eSign document with Text signature and additional settings](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Text+signature+-+advanced)

Het type TextSignOptions exposeert de volgende leden:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/textsignoptions/__init__/) | Initialiseert een nieuw exemplaar van de TextSignOptions klasse met standaardwaarden. |
| [__init__](/signature/python-net/groupdocs.signature.options/textsignoptions/__init__/#text) | Initialiseert een nieuw exemplaar van de TextSignOptions klasse met tekst. |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [background](/signature/python-net/groupdocs.signature.options/textsignoptions/background/) | De achtergrondinstellingen van de handtekening. |
| [border](/signature/python-net/groupdocs.signature.options/textsignoptions/border/) | De randinstellingen. |
| [font](/signature/python-net/groupdocs.signature.options/textsignoptions/font/) | Het lettertype van de handtekening. |
| [fore_color](/signature/python-net/groupdocs.signature.options/textsignoptions/fore_color/) | De voorgrondkleur van de handtekening. |
| [form_text_field_title](/signature/python-net/groupdocs.signature.options/textsignoptions/form_text_field_title/) | De titel van het tekstformulierveld waarin de teksthandtekening moet worden geplaatst. Alleen bruikbaar wanneer `signature_implementation` is ingesteld op `TextSignatureImplementation.FORM_FIELD`. |
| [form_text_field_type](/signature/python-net/groupdocs.signature.options/textsignoptions/form_text_field_type/) | Het type formulierveld waarin de tekstopdracht moet worden geplaatst. Deze eigenschap is alleen van toepassing wanneer `signature_implementation` is ingesteld op `TextSignatureImplementation.FORM_FIELD` (d.w.z. TextToFormField). De standaardwaarde is `FormTextFieldType.ALL_TEXT_TYPES`. |
| [height](/signature/python-net/groupdocs.signature.options/textsignoptions/height/) | De hoogte van de handtekening op de documentpagina in meetwaarden (pixels, procenten of millimeters). De eenheid wordt bepaald door de eigenschap `SizeMeasureType`. |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/textsignoptions/horizontal_alignment/) | De horizontale uitlijning van de handtekening op de documentpagina. |
| [left](/signature/python-net/groupdocs.signature.options/textsignoptions/left/) | De linkse X‑positie van de handtekening op de documentpagina in meetwaarden (pixels, procenten of millimeters zoals gedefinieerd door de eigenschap `MeasureType` LocationMeasureType). Werkt als horizontale uitlijning niet is gespecificeerd. |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/textsignoptions/location_measure_type/) | Het meettype (pixels, procenten of millimeters) voor de eigenschappen `left` en `top`. |
| [margin](/signature/python-net/groupdocs.signature.options/textsignoptions/margin/) | De ruimte tussen de handtekening en de documentranden. Geldt alleen wanneer horizontale of verticale uitlijning is gespecificeerd. |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/textsignoptions/margin_measure_type/) | Het meettype (pixels, procenten of millimeters) voor de marge. |
| [native](/signature/python-net/groupdocs.signature.options/textsignoptions/native/) | Het native‑attribuut. |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/textsignoptions/rotation_angle/) | De rotatiehoek van de handtekening op de documentpagina (met de klok mee). |
| [shape_position](/signature/python-net/groupdocs.signature.options/textsignoptions/shape_position/) | De vormpositie bepaalt waar de vorm moet worden weergegeven in de documentlay-out. Alleen beschikbaar voor Word‑documenten. |
| [shape_type](/signature/python-net/groupdocs.signature.options/textsignoptions/shape_type/) | Het type vorm om tekst in te plaatsen. |
| [signature_id](/signature/python-net/groupdocs.signature.options/textsignoptions/signature_id/) | De unieke ID van de handtekening, bruikbaar in verificatie‑opties en alleen ondersteund voor PDF‑documenten. |
| [signature_implementation](/signature/python-net/groupdocs.signature.options/textsignoptions/signature_implementation/) | Het type implementatie van tekstopdracht. |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/textsignoptions/size_measure_type/) | Het meettype (pixels, procenten of millimeters) voor de eigenschappen Width en Height. |
| [stretch](/signature/python-net/groupdocs.signature.options/textsignoptions/stretch/) | De stretch-modus op de documentpagina. |
| [text](/signature/python-net/groupdocs.signature.options/textsignoptions/text/) | De tekst van de handtekening. |
| [text_horizontal_alignment](/signature/python-net/groupdocs.signature.options/textsignoptions/text_horizontal_alignment/) | De horizontale uitlijning van tekst binnen een handtekening, alleen ondersteund voor Image‑ en Annotation‑handtekeningimplementaties (zie de eigenschap `TextSignatureImplementation` SignatureImplementation). |
| [text_vertical_alignment](/signature/python-net/groupdocs.signature.options/textsignoptions/text_vertical_alignment/) | De verticale uitlijning van tekst binnen een handtekening. |
| [top](/signature/python-net/groupdocs.signature.options/textsignoptions/top/) | De bovenste Y‑positie van de handtekening op de documentpagina, uitgedrukt in meeteenheden (pixels, procent of millimeters). |
| [transparency](/signature/python-net/groupdocs.signature.options/textsignoptions/transparency/) | De transparantie van de handtekening, een float tussen 0,0 (ondoorzichtig) en 1,0 (doorzichtig). Standaard is 0,0 (ondoorzichtig). |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/textsignoptions/vertical_alignment/) | De verticale uitlijning van de handtekening op de documentpagina. |
| [width](/signature/python-net/groupdocs.signature.options/textsignoptions/width/) | De breedte van de handtekening op de documentpagina in meetwaarden (pixels, procenten of millimeters; zie de eigenschap `MeasureType` `SizeMeasureType`). |
| [all_pages](/signature/python-net/groupdocs.signature.options/signoptions/all_pages/) | De handtekening wordt op alle documentpagina's geplaatst. (geërfd van [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [appearance](/signature/python-net/groupdocs.signature.options/signoptions/appearance/) | Het aanvullende handtekeninguiterlijk. (geërfd van [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [document_type](/signature/python-net/groupdocs.signature.options/signoptions/document_type/) | Het documenttype van de handtekeningopties (`DocumentType`). (geërfd van [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/signoptions/extensions/) | De handtekeningextensies. (geërfd van [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [hash_algorithm](/signature/python-net/groupdocs.signature.options/signoptions/hash_algorithm/) | Het hash‑algoritme dat moet worden gebruikt voor cryptografische bewerkingen. Exclusief ondersteund voor digitale handtekeningen in PDF‑bestanden. (geërfd van [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/signoptions/page_number/) | Het paginanummer van het document voor ondertekening. (geërfd van [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/signoptions/pages_setup/) | De opties om pagina's op te geven die moeten worden ondertekend. (geërfd van [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [signature_type](/signature/python-net/groupdocs.signature.options/signoptions/signature_type/) | Het handtekeningtype (`SignatureType`). (geërfd van [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [zorder](/signature/python-net/groupdocs.signature.options/signoptions/zorder/) | De Z‑orde positie van de tekshandtekening, die de weergavevolgorde van overlappende handtekeningen bepaalt. (geërfd van [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |

### Voorbeeld

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

def sign_pdf_with_text_signature():
    with Signature("sample.pdf") as signature:
        options = TextSignOptions("John Smith")
        options.left = 100
        options.top = 100
        result = signature.sign("signed_sample.pdf", options)
        print(f"Signatures added: {len(result.succeeded)}")
```

### Guides
Taakgidsen die `TextSignOptions` gebruiken:

* [Quick Start Guide](/signature/python-net/guides/quick-start-guide/)
* [eSign Document with Text Signature](/signature/python-net/guides/esign-document-with-text-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)
* [Generate signatures preview](/signature/python-net/guides/generate-signatures-preview/)

### Zie ook
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
