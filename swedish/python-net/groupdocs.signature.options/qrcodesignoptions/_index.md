---
title: "Klassen QrCodeSignOptions"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Representerar QR‑Kod‑signaturalternativen."
type: docs
url: /sv/python-net/groupdocs.signature.options/qrcodesignoptions/
is_root: false
weight: 480
---


## QrCodeSignOptions class

Representerar QR‑Kod‑signaturalternativen.

- Basic usage of creating QR-Code electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/eSign+document+with+QR-code+signature
- Advanced usage of settings of QR-Code electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Sign+document+with+QR-code+signature+-+advanced

Typen QrCodeSignOptions exponerar följande medlemmar:

### Konstruktörer
| Konstruktor | Beskrivning |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/__init__/) | Initierar en ny instans av klassen QRCodeSignOptions med standardvärden. |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/__init__/#text) | Initierar en QR-kod signaturalternativ-instans med den angivna texten. |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/__init__/#text-encode_type) | Initierar en ny instans av klassen QrCodeSignOptions med text. |

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [code_text_alignment](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/code_text_alignment/) | Justeringen av text i den resulterande QR-kodbilden, standardvärdet är None. |
| [data](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/data/) | Det anpassade objektet att serialisera till QR-kodinnehåll. |
| [data_encryption](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/data_encryption/) | Datakrypteringsimplementationen som används för att koda och avkoda QR-kodsignaturtext eller data. |
| [encode_type](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/encode_type/) | QR‑Kod‑typen. |
| [fore_color](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/fore_color/) | Förgrundsfärgen för QR‑kod‑staplar; att använda denna egenskap kan orsaka verifieringsproblem, så använd den försiktigt. |
| [height](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/height/) | Höjden på signaturområdet på dokumentets sida i mätenheter (pixlar, procent eller millimeter; se `MeasureType` SizeMeasureType). |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/horizontal_alignment/) | Den horisontella justeringen av QR‑koden på en dokumentsida. |
| [inner_margins](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/inner_margins/) | Utrymmet mellan QR‑kodselement och resultatbildens kanter. |
| [left](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/left/) | Den vänstra X‑positionen för signaturområdet på en dokumentsida i mätenheter (pixlar, procent eller millimeter). |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/location_measure_type/) | Måtttypen (pixlar, procent eller millimeter) för vänster‑ och topp‑egenskaperna. |
| [logo_file_path](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/logo_file_path/) | Filnamnet för QR‑kod‑logobilden. |
| [logo_stream](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/logo_stream/) | Strömmen för QR‑kod‑logobilden. |
| [margin](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/margin/) | Utrymmet som som standard anges mellan bild- och dokumentkanter (fungerar om horisontell eller vertikal justering har angetts). |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/margin_measure_type/) | Måtttypen för marginalen (pixlar, procent eller millimeter). |
| [return_content](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/return_content/) | Flaggan för att hämta QR‑Kod‑bildinnehåll för en signatur placerad på en dokumentsida. |
| [return_content_type](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/return_content_type/) | Filtypen för det returnerade bildinnehållet för QR‑Kod‑signaturen när egenskapen `return_content` är aktiverad. |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/rotation_angle/) | Rotationsvinkeln i grader, medurs. |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/size_measure_type/) | Måtttypen (pixlar, procent eller millimeter) för egenskaperna Width och Height. |
| [stretch](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/stretch/) | Sträckningsläget på dokumentsidan. |
| [top](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/top/) | Den övre Y‑positionen för signaturområdet på en dokumentsida i mätenheter (pixlar, procent eller millimeter). Enheten definieras av egenskapen `LocationMeasureType` av typen `MeasureType`. |
| [transparency](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/transparency/) | Genomskinligheten för QR‑kod‑signaturen. Värdet varierar från 0,0 till 1,0, med standardvärdet 0. |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/vertical_alignment/) | Den vertikala justeringen av bilden på en dokumentsida. |
| [width](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/width/) | Bredden på signaturområdet på dokumentsidan i måttvärden (pixlar, procent eller millimeter enligt `MeasureType`). |
| [all_pages](/signature/python-net/groupdocs.signature.options/signoptions/all_pages/) | Signaturen kommer att placeras på alla dokumentsidor. (ärvd från [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [appearance](/signature/python-net/groupdocs.signature.options/signoptions/appearance/) | Det ytterligare signaturutseendet. (ärvd från [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [background](/signature/python-net/groupdocs.signature.options/textsignoptions/background/) | Signaturens bakgrundsinställningar. (ärvd från [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [border](/signature/python-net/groupdocs.signature.options/textsignoptions/border/) | Kantinställningarna. (ärvd från [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [document_type](/signature/python-net/groupdocs.signature.options/signoptions/document_type/) | Dokumenttypen för signaturalternativen (`DocumentType`). (ärvd från [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/signoptions/extensions/) | Signaturens tillägg. (ärvd från [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [font](/signature/python-net/groupdocs.signature.options/textsignoptions/font/) | Signaturens teckensnitt. (ärvd från [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
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
from groupdocs.signature.options import QrCodeSignOptions
from groupdocs.signature.domain import (
    Background, Border, DashStyle, HorizontalAlignment, Padding,
    QrCodeTypes, VerticalAlignment)
from groupdocs.pydrawing import Color

def sign_with_qr_code_signature_advanced():
    with Signature("sample.pdf") as signature:
        # Skicka texten och QR‑kod‑typen till konstruktorn
        options = QrCodeSignOptions("https://www.example.com/verify-document", QrCodeTypes.QR)

        # Placera QR‑koden i nedre högra hörnet av sidan
        options.width = 120
        options.height = 120
        options.horizontal_alignment = HorizontalAlignment.RIGHT
        options.vertical_alignment = VerticalAlignment.BOTTOM
        options.margin = Padding(right=40, bottom=60)

        # Modulfärg, bakgrund och en prickad ram med lite utrymme inuti
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
Uppgiftsguider som använder `QrCodeSignOptions`:

* [eSign Document with QR Code Signature](/signature/python-net/guides/esign-document-with-qr-code-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)
* [Generate signatures preview](/signature/python-net/guides/generate-signatures-preview/)

### Se även
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
