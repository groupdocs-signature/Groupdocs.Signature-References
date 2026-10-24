---
title: "DigitalSignOptions-klass"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Representerar alternativen för digital signatur."
type: docs
url: /sv/python-net/groupdocs.signature.options/digitalsignoptions/
is_root: false
weight: 140
---


## DigitalSignOptions class

Representerar alternativen för digital signatur.

Läs mer

- Basic usage of creating Digital electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Digital+signature
- Advanced usage of settings of Digital electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Digital+signature+-+advanced

DigitalSignOptions-typen exponerar följande medlemmar:

### Konstruktörer
| Konstruktor | Beskrivning |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/) | Initierar en ny instans av DigitalSignOptions-klassen med standardvärden. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/#certificate_file_path) | Initierar en ny DigitalSignOptions-instans med en certifikatfil. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/#certificate_stream) | Initierar en ny DigitalSignOptions-instans med ett certifikatflöde. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/#certificate_file_path-image_file_path) | Initierar en ny instans av DigitalSignOptions-klassen med en certifikatfil och en bildfil för utseende. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/#certificate_file_path-appearence_image_stream) | Initierar en ny instans av DigitalSignOptions med en certifikatfil och ett bildflöde för utseende. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/#certificate_stream-image_file_path) | Initierar en ny instans av DigitalSignOptions med ett certifikatflöde och en bildfil för utseende. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/#certificate_stream-appearence_image_stream) | Initierar en ny DigitalSignOptions-instans med ett certifikatflöde och ett bildflöde för utseende. |

### Metoder
| Metod | Beskrivning |
| :- | :- |
| [dispose](/signature/python-net/groupdocs.signature.options/imagesignoptions/dispose/) | Rensar interna resurser. (ärvd från [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |
| [from_base64](/signature/python-net/groupdocs.signature.options/imagesignoptions/from_base64/) | Skapar en ny ImageSignOptions-instans med en fördefinierad bild från en Base64-sträng. (ärvd från [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [allow_expired](/signature/python-net/groupdocs.signature.options/digitalsignoptions/allow_expired/) | Flaggan som tillåter signering med ett certifikat vars giltighetsperiod har löpt ut. Standardvärdet är False; signering med ett utgånget certifikat kastar `GroupDocsSignatureException` och dokumentet signeras inte. |
| [allow_not_yet_valid](/signature/python-net/groupdocs.signature.options/digitalsignoptions/allow_not_yet_valid/) | Flaggan som tillåter signering med ett certifikat vars giltighetsperiod ännu inte har börjat. Standardvärdet är False; signering med ett sådant certifikat kastar `GroupDocsSignatureException` och dokumentet signeras inte. |
| [certificate_file_path](/signature/python-net/groupdocs.signature.options/digitalsignoptions/certificate_file_path/) | Sökvägen till den digitala certifikatfilen. |
| [certificate_stream](/signature/python-net/groupdocs.signature.options/digitalsignoptions/certificate_stream/) | Den digitala certifikatströmmen. Om denna egenskap är angiven används den alltid istället för CertificateFilePath. |
| [contact](/signature/python-net/groupdocs.signature.options/digitalsignoptions/contact/) | Signaturens kontakt. |
| [custom_sign_hash](/signature/python-net/groupdocs.signature.options/digitalsignoptions/custom_sign_hash/) | Den anpassade hash‑signeringsfunktionen som används för att signera dokumentet, vilket möjliggör att användare kan implementera sin egen digitala signeringslogik. |
| [height](/signature/python-net/groupdocs.signature.options/digitalsignoptions/height/) | Höjden på signaturområdet på dokumentsidan i måttenheter (pixlar, procent eller millimeter; se `MeasureType`). |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/digitalsignoptions/horizontal_alignment/) | Den horisontella justeringen av bilden på en dokumentsida. |
| [left](/signature/python-net/groupdocs.signature.options/digitalsignoptions/left/) | Den vänstra X‑positionen för signaturområdet på dokumentsidan i måttenheter (pixlar, procent eller millimeter enligt `MeasureType.location_measure_type`). |
| [location](/signature/python-net/groupdocs.signature.options/digitalsignoptions/location/) | Signaturens plats. |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/digitalsignoptions/location_measure_type/) | Måtttypen (pixlar, procent eller millimeter) för vänster‑ och topp‑egenskaperna. |
| [margin](/signature/python-net/groupdocs.signature.options/digitalsignoptions/margin/) | Det utrymme som som standard anges mellan bilden och dokumentets kanter (gäller när horisontell eller vertikal justering har angetts). |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/digitalsignoptions/margin_measure_type/) | Måtttypen för marginalen (pixlar, procent eller millimeter). |
| [password](/signature/python-net/groupdocs.signature.options/digitalsignoptions/password/) | Lösenordet för det digitala certifikatet. |
| [reason](/signature/python-net/groupdocs.signature.options/digitalsignoptions/reason/) | Anledningen till signaturen. |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/digitalsignoptions/rotation_angle/) | Rotationsvinkeln medurs. |
| [signature](/signature/python-net/groupdocs.signature.options/digitalsignoptions/signature/) | De digitala signatur‑egenskaperna för dokumentet. För PDF‑signering kan avancerade egenskaper ställas in med en [`PdfDigitalSignature`](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/)‑instans. |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/digitalsignoptions/size_measure_type/) | Måtttypen (pixlar, procent eller millimeter) för egenskaperna Width och Height. |
| [stretch](/signature/python-net/groupdocs.signature.options/digitalsignoptions/stretch/) | Sträckningsläget på dokumentsidan. |
| [top](/signature/python-net/groupdocs.signature.options/digitalsignoptions/top/) | Den övre Y‑positionen för signaturområdet på dokumentsidan i måttenheter (pixlar, procent eller millimeter; se `MeasureType` `LocationMeasureType`). |
| [transparency](/signature/python-net/groupdocs.signature.options/digitalsignoptions/transparency/) | Transparensen för den digitala signaturen, från 0,0 till 1,0. Standard är 0. |
| [use_ltv](/signature/python-net/groupdocs.signature.options/digitalsignoptions/use_ltv/) | LTV‑flaggan (Long Term Validation) för validering. |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/digitalsignoptions/vertical_alignment/) | Den vertikala justeringen av bilden på en dokumentsida. |
| [visible](/signature/python-net/groupdocs.signature.options/digitalsignoptions/visible/) | Signaturens synlighet. |
| [width](/signature/python-net/groupdocs.signature.options/digitalsignoptions/width/) | Bredden på signaturområdet på dokumentsidan i måttenheter (pixlar, procent eller millimeter). Måttenheten definieras av `MeasureType` via egenskapen SizeMeasureType. |
| [xad_es_type](/signature/python-net/groupdocs.signature.options/digitalsignoptions/xad_es_type/) | XAdES‑typen. Standardvärdet är None (XAdES är avstängt). |
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
from groupdocs.signature.options import DigitalSignOptions

def sign_with_digital_signature_advanced():
    with Signature("sample.pdf") as signature:
        # Skicka certifikatet och bild för utseende till konstruktorn
        options = DigitalSignOptions("certificate.pfx", "signature.jpg")
        options.password = "1234567890"

        # Visa signaturen på sidan, på denna position och storlek
        options.visible = True
        options.left = 100
        options.top = 400
        options.width = 200
        options.height = 100

        # Information lagrad i signaturen
        options.contact = "John Smith"
        options.reason = "Approval"
        options.location = "New York"

        result = signature.sign("signed_digital_advanced.pdf", options)
        print(f"Signed with {len(result.succeeded)} digital signature(s)")

if __name__ == "__main__":
    sign_with_digital_signature_advanced()
```

### Guides
Uppgiftsguider som använder `DigitalSignOptions`:

* [Sign Document with Digital Signature](/signature/python-net/guides/esign-document-with-digital-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)

### Se även
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
