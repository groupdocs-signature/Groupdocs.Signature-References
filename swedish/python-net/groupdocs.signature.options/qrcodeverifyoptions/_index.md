---
title: "QrCodeVerifyOptions-klass"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Behåller alternativ för att verifiera dokumentets QR‑Kod‑signatur."
type: docs
url: /sv/python-net/groupdocs.signature.options/qrcodeverifyoptions/
is_root: false
weight: 490
---


## QrCodeVerifyOptions class

Behåller alternativ för att verifiera dokumentets QR‑Kod‑signatur.

- Basic usage of verification for QR-code electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Verify+QR-code+signatures+in+the+document
- Advanced usage of settings of verification for QR-code electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Verify+QR-code+signatures

QrCodeVerifyOptions-typen exponerar följande medlemmar:

### Konstruktörer
| Konstruktor | Beskrivning |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodeverifyoptions/__init__/) | Initierar verifieringsalternativ för QR‑Kod‑signaturer. |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodeverifyoptions/__init__/#text) | Initierar verifieringsalternativ för QR‑Kod‑signaturer med den angivna QR‑kodtexten. |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodeverifyoptions/__init__/#text-encode_type) | Initierar verifieringsalternativ för QR‑Kod‑signaturer med text och QR‑Kod‑kodningstyp att verifiera. |

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [data_encryption](/signature/python-net/groupdocs.signature.options/qrcodeverifyoptions/data_encryption/) | Implementeringen av [`IDataEncryption`](/signature/python-net/groupdocs.signature.domain.extensions/idataencryption/) som används för att koda och avkoda QR-Code‑signaturens textegenskaper. |
| [encode_type](/signature/python-net/groupdocs.signature.options/qrcodeverifyoptions/encode_type/) | QR-code‑typverifiering. Denna egenskap är valfri. |
| [all_pages](/signature/python-net/groupdocs.signature.options/verifyoptions/all_pages/) | Flaggan som indikerar om varje dokumentsida ska verifieras. Som standard är värdet True. (ärvd från [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/verifyoptions/extensions/) | De extra tilläggen för verifiering av alternativa signaturalternativ. (ärvd från [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [form_text_field_title](/signature/python-net/groupdocs.signature.options/textverifyoptions/form_text_field_title/) | Titeln på formulärfältet som ska verifieras. Om den är angiven kommer texten endast att hittas i textformulärfält. (ärvd från [`TextVerifyOptions`](/signature/python-net/groupdocs.signature.options/textverifyoptions/)) |
| [form_text_field_type](/signature/python-net/groupdocs.signature.options/textverifyoptions/form_text_field_type/) | Typen av formulärfält att verifiera; om den är angiven kommer texten endast att hittas i textformulärfält. (ärvd från [`TextVerifyOptions`](/signature/python-net/groupdocs.signature.options/textverifyoptions/)) |
| [is_valid](/signature/python-net/groupdocs.signature.options/verifyoptions/is_valid/) | Den giltiga egenskapsflaggan. (ärvd från [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [match_type](/signature/python-net/groupdocs.signature.options/textverifyoptions/match_type/) | Verifiering av textmatchningstyp. (ärvd från [`TextVerifyOptions`](/signature/python-net/groupdocs.signature.options/textverifyoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/verifyoptions/page_number/) | Dokumentsidans nummer som ska verifieras; om det inte är angivet verifieras alla sidor i dokumentet för den första förekomsten (minsta värde är 1). (ärvd från [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/verifyoptions/pages_setup/) | Sidalternativen för att specificera vilka sidor som ska verifieras. (ärvd från [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/verifyoptions/shape_position/) | Formens position i dokumentlayouten som används för att verifiera signaturer i sidhuvuden/sidfötter. (ärvd från [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [signature_id](/signature/python-net/groupdocs.signature.options/textverifyoptions/signature_id/) | Textsignatur-ID:t att verifiera. Måste vara större än noll; stöds endast för PDF-dokument. (ärvd från [`TextVerifyOptions`](/signature/python-net/groupdocs.signature.options/textverifyoptions/)) |
| [signature_implementation](/signature/python-net/groupdocs.signature.options/textverifyoptions/signature_implementation/) | Typen av signatur som ska verifieras. (ärvd från [`TextVerifyOptions`](/signature/python-net/groupdocs.signature.options/textverifyoptions/)) |
| [text](/signature/python-net/groupdocs.signature.options/textverifyoptions/text/) | Signaturtexten att verifiera. (ärvd från [`TextVerifyOptions`](/signature/python-net/groupdocs.signature.options/textverifyoptions/)) |

### Exempel

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import QrCodeVerifyOptions
from groupdocs.signature.domain import TextMatchType

def verify_qr_codes():
    with Signature("signed.pdf") as signature:
        options = QrCodeVerifyOptions()
        options.all_pages = True
        options.text = "John"
        options.match_type = TextMatchType.CONTAINS

        result = signature.verify(options)

        if result.is_valid:
            print(f"Document verified: {len(result.succeeded)} matching QR code signature(s).")
        else:
            print("Document verification failed.")
```

### Se även
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
