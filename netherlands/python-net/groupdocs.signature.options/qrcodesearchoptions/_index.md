---
title: "QrCodeSearchOptions klasse"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Vertegenwoordigt zoekopties voor QR-codehandtekeningen."
type: docs
url: /nl/python-net/groupdocs.signature.options/qrcodesearchoptions/
is_root: false
weight: 470
---


## QrCodeSearchOptions class

Vertegenwoordigt zoekopties voor QR-codehandtekeningen.

- Basic usage of search for QR-Code electronic signature by GroupDocs.Signature: How to eSearch QR-Code signatures in a document (https://docs.groupdocs.com/display/signaturenet/Search+for+QR-Code+e-signatures)
- Advanced usage of settings of search for QR-Code electronic signature with GroupDocs.Signature: Advanced usage of eSearch QR-Code signatures in a document and additional settings (https://docs.groupdocs.com/display/signaturenet/Advanced+search+for+QR-code+signatures)

Het QrCodeSearchOptions-type geeft de volgende leden weer:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/__init__/) | Initialiseert een nieuwe instantie van de QRCodeSearchOptions‑klasse met standaardwaarden. |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/__init__/#encode_type) | Initialiseert een nieuwe instantie van de QRCodeSearchOptions‑klasse met een encode‑typewaarde. |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/__init__/#encode_type-text) | Initialiseert een nieuw exemplaar van de QRCodeSearchOptions‑klasse met coderings‑type en tekstwaarden. |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [data_encryption](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/data_encryption/) | De implementatie van [`IDataEncryption`](/signature/python-net/groupdocs.signature.domain.extensions/idataencryption/) die wordt gebruikt om QR‑Code‑handtekeningtekst of -dataproperties te coderen en decoderen. |
| [encode_type](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/encode_type/) | Het coderings‑type om naar QR‑codes te zoeken. |
| [match_type](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/match_type/) | Het QR‑Code‑tekst‑overeenkomsttype dat tijdens het zoeken wordt gebruikt. |
| [return_content](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/return_content/) | De vlag die bepaalt of QR‑Code‑afbeeldingsinhoud wordt geretourneerd voor elke handtekening op een documentpagina. Wanneer ingesteld op True, wordt de ruwe afbeeldingsdata bewaard in de `content`‑eigenschap van de handtekening met het formaat gespecificeerd door `return_content_type`. Standaard uitgeschakeld. |
| [return_content_type](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/return_content_type/) | Het bestandstype van de geretourneerde afbeeldingsinhoud van de QR‑Code‑handtekening wanneer de `return_content`‑eigenschap is ingeschakeld. |
| [text](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/text/) | De QR‑Code‑handtekeningtekst om te zoeken en te vergelijken. |
| [all_pages](/signature/python-net/groupdocs.signature.options/searchoptions/all_pages/) | De vlag die aangeeft of er op elke documentpagina moet worden gezocht. Standaard is deze waarde True. (geërfd van [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/searchoptions/page_number/) | Het paginanummer van het document voor zoeken (optioneel). (geërfd van [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/searchoptions/pages_setup/) | De opties om pagina's op te geven voor handtekeningzoeken. (geërfd van [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/searchoptions/shape_position/) | De vlag die aangeeft of de vormpositie in de documentlay-out moet worden geretourneerd. Alleen beschikbaar voor Word‑documenten. (geërfd van [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [skip_external](/signature/python-net/groupdocs.signature.options/searchoptions/skip_external/) | De vlag om alleen handtekeningen die gemarkeerd zijn als `IsSignature` te retourneren. Standaard is de waarde `False`, wat aangeeft dat alle handtekeningen die aan de opgegeven criteria voldoen, worden geretourneerd. (geërfd van [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |

### Voorbeeld

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import QrCodeSearchOptions

with Signature("signed.pdf") as signature:
    result = signature.search([QrCodeSearchOptions()])
    print(f"Found {len(result.signatures)} QR code signature(s)")
    for qr in result.signatures:
        print(f"QR code signature found at page {qr.page_number} with type {qr.encode_type.type_name} and text '{qr.text}'")
```

### Zie ook
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
