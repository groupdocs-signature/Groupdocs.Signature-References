---
title: "QrCodeVerifyOptions klasse"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Bevat opties om de QR-codehandtekening van een document te verifiëren."
type: docs
url: /nl/python-net/groupdocs.signature.options/qrcodeverifyoptions/
is_root: false
weight: 490
---


## QrCodeVerifyOptions class

Bevat opties om de QR-codehandtekening van een document te verifiëren.

- Basic usage of verification for QR-code electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Verify+QR-code+signatures+in+the+document
- Advanced usage of settings of verification for QR-code electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Verify+QR-code+signatures

Het QrCodeVerifyOptions-type geeft de volgende leden weer:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodeverifyoptions/__init__/) | Initialiseert verificatieopties voor QR-Code-handtekeningen. |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodeverifyoptions/__init__/#text) | Initialiseert verificatieopties voor QR-Code-handtekeningen met de opgegeven QR-code-tekst. |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodeverifyoptions/__init__/#text-encode_type) | Initialiseert verificatieopties voor QR-Code-handtekeningen met tekst en QR-Code-encoderingstype om te verifiëren. |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [data_encryption](/signature/python-net/groupdocs.signature.options/qrcodeverifyoptions/data_encryption/) | De implementatie van [`IDataEncryption`](/signature/python-net/groupdocs.signature.domain.extensions/idataencryption/) die wordt gebruikt om QR-Code-handtekeningtekst‑eigenschappen te coderen en decoderen. |
| [encode_type](/signature/python-net/groupdocs.signature.options/qrcodeverifyoptions/encode_type/) | De QR-code type‑verificatie. Deze eigenschap is optioneel. |
| [all_pages](/signature/python-net/groupdocs.signature.options/verifyoptions/all_pages/) | De vlag die aangeeft of elke documentpagina moet worden geverifieerd. Standaard is de waarde True. (geërfd van [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/verifyoptions/extensions/) | De extra extensies voor verificatie van alternatieve handtekeningopties. (geërfd van [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [form_text_field_title](/signature/python-net/groupdocs.signature.options/textverifyoptions/form_text_field_title/) | De titel van het formulierveld dat moet worden geverifieerd. Indien ingesteld, wordt de tekst alleen gevonden in tekstformuliervelden. (geërfd van [`TextVerifyOptions`](/signature/python-net/groupdocs.signature.options/textverifyoptions/)) |
| [form_text_field_type](/signature/python-net/groupdocs.signature.options/textverifyoptions/form_text_field_type/) | Het type formulierveld dat moet worden geverifieerd; indien ingesteld, wordt tekst alleen gevonden in tekstformuliervelden. (geërfd van [`TextVerifyOptions`](/signature/python-net/groupdocs.signature.options/textverifyoptions/)) |
| [is_valid](/signature/python-net/groupdocs.signature.options/verifyoptions/is_valid/) | De geldige eigenschapsvlag. (geërfd van [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [match_type](/signature/python-net/groupdocs.signature.options/textverifyoptions/match_type/) | De verificatie van het tekstovereenkomsttype. (geërfd van [`TextVerifyOptions`](/signature/python-net/groupdocs.signature.options/textverifyoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/verifyoptions/page_number/) | Het paginanummer van het document dat moet worden geverifieerd; indien niet ingesteld, worden alle pagina's van het document geverifieerd voor de eerste keer (minimumwaarde is 1). (geërfd van [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/verifyoptions/pages_setup/) | De pagina-opties om de te verifiëren pagina's op te geven. (geërfd van [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/verifyoptions/shape_position/) | De vormpositie in de documentlay-out die wordt gebruikt voor het verifiëren van handtekeningen in kopteksten/voetteksten. (geërfd van [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [signature_id](/signature/python-net/groupdocs.signature.options/textverifyoptions/signature_id/) | De teksthandtekening-ID die moet worden geverifieerd. Moet groter zijn dan nul; alleen ondersteund voor PDF-documenten. (geërfd van [`TextVerifyOptions`](/signature/python-net/groupdocs.signature.options/textverifyoptions/)) |
| [signature_implementation](/signature/python-net/groupdocs.signature.options/textverifyoptions/signature_implementation/) | Het type handtekening dat moet worden geverifieerd. (geërfd van [`TextVerifyOptions`](/signature/python-net/groupdocs.signature.options/textverifyoptions/)) |
| [text](/signature/python-net/groupdocs.signature.options/textverifyoptions/text/) | De handtekeningtekst die moet worden geverifieerd. (geërfd van [`TextVerifyOptions`](/signature/python-net/groupdocs.signature.options/textverifyoptions/)) |

### Voorbeeld

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

### Zie ook
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
