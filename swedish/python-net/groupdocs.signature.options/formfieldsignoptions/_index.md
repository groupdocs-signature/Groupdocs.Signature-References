---
title: "FormFieldSignOptions-klass"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Representerar FormField-signaturalternativen för PDF-dokument."
type: docs
url: /sv/python-net/groupdocs.signature.options/formfieldsignoptions/
is_root: false
weight: 180
---


## FormFieldSignOptions class

Representerar FormField-signaturalternativen för PDF-dokument.

Tillhandahåller alternativ för att skapa eller uppdatera formulärfältssignaturer i PDF-filer.

- Basic usage of creating FormField electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Form+Field+signature
- Advanced usage of settings of FormField electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Form+Field+signature+-+advanced

FormFieldSignOptions-typen visar följande medlemmar:

### Konstruktörer
| Konstruktor | Beskrivning |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/__init__/) | Initierar en ny instans av PdfFormFieldSignOptions-klassen med standardvärden. |
| [__init__](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/__init__/#signature) | Initierar en ny instans av PdfFormFieldSignOptions-klassen med FormField-signatur. |

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [height](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/height/) | Höjden på signaturområdet på dokumentets sida i mätenheter (pixlar, procent eller millimeter; se `MeasureType` SizeMeasureType). |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/horizontal_alignment/) | Den horisontella justeringen av bilden på en dokumentsida. |
| [left](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/left/) | Den vänstra X-positionen för signaturområdet på dokumentets sida i mätenheter (pixlar, procent eller millimeter). |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/location_measure_type/) | Måtttypen (pixlar, procent eller millimeter) för egenskaperna Left och Top. |
| [margin](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/margin/) | Standardavståndet mellan bilden och dokumentets kanter (gäller när horisontell eller vertikal justering är inställd). |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/margin_measure_type/) | Måtttypen för marginalen (pixlar, procent eller millimeter). |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/rotation_angle/) | Rotationsvinkeln, mätt medurs. |
| [signature](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/signature/) | FormField för signaturen. |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/size_measure_type/) | Måtttypen (pixlar, procent eller millimeter) för egenskaperna Width och Height. |
| [stretch](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/stretch/) | Sträckningsläget på dokumentets sida. |
| [top](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/top/) | Den övre Y-positionen för signaturområdet på dokumentsidan i mätenheter (pixlar, procent eller millimeter). Se `MeasureType` för platsmåtttypen. |
| [transparency](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/transparency/) | Transparensen för formulärfältssignaturen. Värdet varierar från 0.0 till 1.0, med standardvärdet 0. |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/vertical_alignment/) | Den vertikala justeringen av bilden på en dokumentsida. |
| [width](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/width/) | Bredden på signaturområdet på dokumentets sida i mätenheter (pixlar, procent eller millimeter; se `MeasureType` SizeMeasureType). |
| [all_pages](/signature/python-net/groupdocs.signature.options/signoptions/all_pages/) | Signaturen kommer att placeras på alla dokumentsidor. (ärvd från [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [appearance](/signature/python-net/groupdocs.signature.options/signoptions/appearance/) | Det ytterligare signaturutseendet. (ärvd från [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [background](/signature/python-net/groupdocs.signature.options/textsignoptions/background/) | Signaturens bakgrundsinställningar. (ärvd från [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [border](/signature/python-net/groupdocs.signature.options/textsignoptions/border/) | Kantinställningarna. (ärvd från [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [document_type](/signature/python-net/groupdocs.signature.options/signoptions/document_type/) | Dokumenttypen för signaturalternativen (`DocumentType`). (ärvd från [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/signoptions/extensions/) | Signaturens tillägg. (ärvd från [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [font](/signature/python-net/groupdocs.signature.options/textsignoptions/font/) | Signaturens teckensnitt. (ärvd från [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [fore_color](/signature/python-net/groupdocs.signature.options/textsignoptions/fore_color/) | Förgrundsfärgen för signaturen. (ärvd från [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [form_text_field_title](/signature/python-net/groupdocs.signature.options/textsignoptions/form_text_field_title/) | Titeln på textformulärfältet där textsignaturen ska placeras. Kan endast användas när `signature_implementation` är inställd på `TextSignatureImplementation.FORM_FIELD`. (ärvd från [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [form_text_field_type](/signature/python-net/groupdocs.signature.options/textsignoptions/form_text_field_type/) | Typen av formulärfält där textsignaturen ska placeras. Denna egenskap gäller endast när `signature_implementation` är inställd på `TextSignatureImplementation.FORM_FIELD` (dvs. TextToFormField). Standardvärdet är `FormTextFieldType.ALL_TEXT_TYPES`. (ärvd från [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [hash_algorithm](/signature/python-net/groupdocs.signature.options/signoptions/hash_algorithm/) | Hash‑algoritmen som ska användas för kryptografiska operationer. Stöds uteslutande för digitala signaturer i PDF‑filer. (ärvd från [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [native](/signature/python-net/groupdocs.signature.options/textsignoptions/native/) | Det inhemska attributet. (ärvd från [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/signoptions/page_number/) | Dokumentsidans nummer för signering. (ärvd från [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/signoptions/pages_setup/) | Alternativen för att ange vilka sidor som ska signeras. (ärvd från [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/textsignoptions/shape_position/) | Formens position definierar var formen ska visas i dokumentlayouten. Endast tillgänglig för Word-dokument. (ärvd från [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [shape_type](/signature/python-net/groupdocs.signature.options/textsignoptions/shape_type/) | Typen av form för att placera text. (ärvd från [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [signature_id](/signature/python-net/groupdocs.signature.options/textsignoptions/signature_id/) | Den unika ID‑n för signaturen, som kan användas i verifieringsalternativ och endast stöds för PDF-dokument. (ärvd från [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [signature_implementation](/signature/python-net/groupdocs.signature.options/textsignoptions/signature_implementation/) | Typen av textsignaturimplementation. (ärvd från [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [signature_type](/signature/python-net/groupdocs.signature.options/signoptions/signature_type/) | Signaturtypen (`SignatureType`). (ärvd från [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [text](/signature/python-net/groupdocs.signature.options/textsignoptions/text/) | Texten för signaturen. (ärvd från [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [text_horizontal_alignment](/signature/python-net/groupdocs.signature.options/textsignoptions/text_horizontal_alignment/) | Den horisontella justeringen av text inom en signatur, stöds endast för bild- och annoteringssignaturimplementationer (se `TextSignatureImplementation` SignatureImplementation‑egenskap). (ärvd från [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [text_vertical_alignment](/signature/python-net/groupdocs.signature.options/textsignoptions/text_vertical_alignment/) | Den vertikala justeringen av text inom en signatur. (ärvd från [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [zorder](/signature/python-net/groupdocs.signature.options/signoptions/zorder/) | Z‑ordningspositionen för textsignaturen, som bestämmer visningsordningen för överlappande signaturer. (ärvd från [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |

### Exempel

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import FormFieldSignOptions
from groupdocs.signature.domain import TextFormFieldSignature

def sign_with_form_field_signature():
    with Signature("sample.pdf") as signature:
        text_field = TextFormFieldSignature("FieldText", "Value1")
        options = FormFieldSignOptions(text_field)
        options.left = 100
        options.top = 400
        options.width = 200
        options.height = 20

        result = signature.sign("signed_form_field.pdf", options)
        for field in result.succeeded:
            print(f"Added form field '{field.name}' with value '{field.value}'")
```

### Se även
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
