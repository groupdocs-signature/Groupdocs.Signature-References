---
title: "TextVerifyOptions klasse"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Bevat opties om de teksthandtekening van een document te verifiëren."
type: docs
url: /nl/python-net/groupdocs.signature.options/textverifyoptions/
is_root: false
weight: 600
---


## TextVerifyOptions class

Bevat opties om de teksthandtekening van een document te verifiëren.

Meer informatie:
- Basic usage of verification for Barcode electronic signature by GroupDocs.Signature: [How to eVerification Barcode signatures in a document](https://docs.groupdocs.com/display/signaturenet/Verify+Text+signatures+in+the+document)
- Advanced usage of settings of verification for Barcode electronic signature with GroupDocs.Signature: [Advanced usage of eVerification Barcode signatures in a document and additional settings](https://docs.groupdocs.com/display/signaturenet/Verify+Text+signatures)

Het TextVerifyOptions-type bevat de volgende leden:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/textverifyoptions/__init__/) | Initialiseert een nieuw exemplaar van TextVerifyOptions met standaardwaarden. |
| [__init__](/signature/python-net/groupdocs.signature.options/textverifyoptions/__init__/#text) | Initialiseert een nieuw exemplaar van TextVerifyOptions met verificatietekst. |
| [__init__](/signature/python-net/groupdocs.signature.options/textverifyoptions/__init__/#text-implementation) | Initialiseert een nieuw TextVerifyOptions-exemplaar met de te verifiëren tekst en het type handtekeningimplementatie. |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [form_text_field_title](/signature/python-net/groupdocs.signature.options/textverifyoptions/form_text_field_title/) | De titel van het formulierveld dat moet worden geverifieerd. Indien ingesteld, wordt de tekst alleen gevonden in tekstformuliervelden. |
| [form_text_field_type](/signature/python-net/groupdocs.signature.options/textverifyoptions/form_text_field_type/) | Het type formulierveld om te verifiëren; indien ingesteld, wordt tekst alleen gevonden in tekstformuliervelden. |
| [match_type](/signature/python-net/groupdocs.signature.options/textverifyoptions/match_type/) | De verificatie van het tekstovereenkomsttype. |
| [signature_id](/signature/python-net/groupdocs.signature.options/textverifyoptions/signature_id/) | De Text Signature ID om te verifiëren. Moet groter zijn dan nul; alleen ondersteund voor PDF-documenten. |
| [signature_implementation](/signature/python-net/groupdocs.signature.options/textverifyoptions/signature_implementation/) | Het type handtekening dat moet worden geverifieerd. |
| [text](/signature/python-net/groupdocs.signature.options/textverifyoptions/text/) | De handtekeningtekst om te verifiëren. |
| [all_pages](/signature/python-net/groupdocs.signature.options/verifyoptions/all_pages/) | De vlag die aangeeft of elke documentpagina moet worden geverifieerd. Standaard is de waarde True. (geërfd van [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/verifyoptions/extensions/) | De extra extensies voor verificatie van alternatieve handtekeningopties. (geërfd van [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [is_valid](/signature/python-net/groupdocs.signature.options/verifyoptions/is_valid/) | De geldige eigenschapsvlag. (geërfd van [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/verifyoptions/page_number/) | Het paginanummer van het document dat moet worden geverifieerd; indien niet ingesteld, worden alle pagina's van het document geverifieerd voor de eerste keer (minimumwaarde is 1). (geërfd van [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/verifyoptions/pages_setup/) | De pagina-opties om de te verifiëren pagina's op te geven. (geërfd van [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/verifyoptions/shape_position/) | De vormpositie in de documentlay-out die wordt gebruikt voor het verifiëren van handtekeningen in kopteksten/voetteksten. (geërfd van [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |

### Voorbeeld

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextVerifyOptions

def verify_text_signature():
    with Signature("signed.pdf") as signature:
        options = TextVerifyOptions("John Smith")
        result = signature.verify(options)
        print(f"Document is signed by John Smith: {result.is_valid}")

if __name__ == "__main__":
    verify_text_signature()
```

### Guides
Taakgidsen die `TextVerifyOptions` gebruiken:

* [Quick Start Guide](/signature/python-net/guides/quick-start-guide/)

### Zie ook
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
