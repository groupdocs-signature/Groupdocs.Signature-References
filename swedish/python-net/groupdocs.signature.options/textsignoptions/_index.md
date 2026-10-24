---
title: "TextSignOptions-klass"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Representerar Textsignaturalternativen."
type: docs
url: /sv/python-net/groupdocs.signature.options/textsignoptions/
is_root: false
weight: 590
---


## TextSignOptions class

Representerar Textsignaturalternativen.

Läs mer

- Basic usage of creating Text electronic signature by GroupDocs.Signature: [How to eSign document with Text signature](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Text+signature)
- Advanced usage of settings of Text electronic signature with GroupDocs.Signature: [Advanced usage to eSign document with Text signature and additional settings](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Text+signature+-+advanced)

TextSignOptions‑typen visar följande medlemmar:

### Konstruktörer
| Konstruktor | Beskrivning |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/textsignoptions/__init__/) | Initierar en ny instans av TextSignOptions‑klassen med standardvärden. |
| [__init__](/signature/python-net/groupdocs.signature.options/textsignoptions/__init__/#text) | Initierar en ny instans av TextSignOptions‑klassen med text. |

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [background](/signature/python-net/groupdocs.signature.options/textsignoptions/background/) | Inställningarna för signaturens bakgrund. |
| [border](/signature/python-net/groupdocs.signature.options/textsignoptions/border/) | Kantinställningarna. |
| [font](/signature/python-net/groupdocs.signature.options/textsignoptions/font/) | Teckensnittet för signaturen. |
| [fore_color](/signature/python-net/groupdocs.signature.options/textsignoptions/fore_color/) | Förgrundsfärgen för signaturen. |
| [form_text_field_title](/signature/python-net/groupdocs.signature.options/textsignoptions/form_text_field_title/) | Titeln på textformulärfältet där textsignaturen ska placeras. Kan endast användas när `signature_implementation` är satt till `TextSignatureImplementation.FORM_FIELD`. |
| [form_text_field_type](/signature/python-net/groupdocs.signature.options/textsignoptions/form_text_field_type/) | Typen av formulärfält att placera textsignaturen i. Denna egenskap är endast tillämplig när `signature_implementation` är inställd på `TextSignatureImplementation.FORM_FIELD` (dvs. TextToFormField). Standardvärdet är `FormTextFieldType.ALL_TEXT_TYPES`. |
| [height](/signature/python-net/groupdocs.signature.options/textsignoptions/height/) | Höjden på signaturen på dokumentsidan i måttenheter (pixlar, procent eller millimeter). Enheten bestäms av egenskapen `SizeMeasureType`. |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/textsignoptions/horizontal_alignment/) | Den horisontella justeringen av signaturen på dokumentsidan. |
| [left](/signature/python-net/groupdocs.signature.options/textsignoptions/left/) | Den vänstra X‑positionen för signaturen på dokumentsidan i måttenheter (pixlar, procent eller millimeter enligt `MeasureType` LocationMeasureType‑egenskapen). Fungerar om horisontell justering inte är specificerad. |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/textsignoptions/location_measure_type/) | Måtttypen (pixlar, procent eller millimeter) för egenskaperna `left` och `top`. |
| [margin](/signature/python-net/groupdocs.signature.options/textsignoptions/margin/) | Avståndet mellan signaturen och dokumentets kanter. Gäller endast när horisontell eller vertikal justering är specificerad. |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/textsignoptions/margin_measure_type/) | Måtttypen (pixlar, procent eller millimeter) för marginalen. |
| [native](/signature/python-net/groupdocs.signature.options/textsignoptions/native/) | Det inbyggda attributet. |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/textsignoptions/rotation_angle/) | Rotationsvinkeln för signaturen på dokumentsidan (medurs). |
| [shape_position](/signature/python-net/groupdocs.signature.options/textsignoptions/shape_position/) | Formens position definierar var formen ska visas i dokumentlayouten. Endast tillgänglig för Word‑dokument. |
| [shape_type](/signature/python-net/groupdocs.signature.options/textsignoptions/shape_type/) | Typen av form för att placera text. |
| [signature_id](/signature/python-net/groupdocs.signature.options/textsignoptions/signature_id/) | Det unika ID‑t för signaturen, kan användas i verifieringsalternativ och stöds endast för PDF‑dokument. |
| [signature_implementation](/signature/python-net/groupdocs.signature.options/textsignoptions/signature_implementation/) | Typen av textsignaturimplementation. |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/textsignoptions/size_measure_type/) | Måtttypen (pixlar, procent eller millimeter) för egenskaperna Width och Height. |
| [stretch](/signature/python-net/groupdocs.signature.options/textsignoptions/stretch/) | Sträckningsläget på dokumentets sida. |
| [text](/signature/python-net/groupdocs.signature.options/textsignoptions/text/) | Texten i signaturen. |
| [text_horizontal_alignment](/signature/python-net/groupdocs.signature.options/textsignoptions/text_horizontal_alignment/) | Den horisontella justeringen av text inom en signatur, stöds endast för bild‑ och annoteringssignaturimplementationer (se egenskapen `TextSignatureImplementation` SignatureImplementation). |
| [text_vertical_alignment](/signature/python-net/groupdocs.signature.options/textsignoptions/text_vertical_alignment/) | Den vertikala justeringen av text i en signatur. |
| [top](/signature/python-net/groupdocs.signature.options/textsignoptions/top/) | Den övre Y‑positionen för signaturen på dokumentsidan, uttryckt i måttenheter (pixlar, procent eller millimeter). |
| [transparency](/signature/python-net/groupdocs.signature.options/textsignoptions/transparency/) | Signaturens transparens, ett flyttal mellan 0,0 (opak) och 1,0 (klar). Standard är 0,0 (opak). |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/textsignoptions/vertical_alignment/) | Den vertikala justeringen av signaturen på dokumentsidan. |
| [width](/signature/python-net/groupdocs.signature.options/textsignoptions/width/) | Bredden på signaturen på dokumentsidan i måttenheter (pixlar, procent eller millimeter; se egenskaperna `MeasureType` och `SizeMeasureType`). |
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
Uppgiftsguider som använder `TextSignOptions`:

* [Quick Start Guide](/signature/python-net/guides/quick-start-guide/)
* [eSign Document with Text Signature](/signature/python-net/guides/esign-document-with-text-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)
* [Generate signatures preview](/signature/python-net/guides/generate-signatures-preview/)

### Se även
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
