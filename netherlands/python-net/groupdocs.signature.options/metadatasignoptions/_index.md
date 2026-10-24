---
title: "MetadataSignOptions‑klasse"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Vertegenwoordigt metadata-handtekeningopties."
type: docs
url: /nl/python-net/groupdocs.signature.options/metadatasignoptions/
is_root: false
weight: 320
---


## MetadataSignOptions class

Vertegenwoordigt metadata-handtekeningopties.

Meer informatie

- Basic usage of creating Metadata electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Metadata+signature
- Advanced usage of settings of Metadata electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Metadata+signature+-+advanced

Het MetadataSignOptions‑type toont de volgende leden:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/metadatasignoptions/__init__/) | Initialiseert een nieuw exemplaar van de MetadataSignOptions‑klasse met standaardwaarden. |
| [__init__](/signature/python-net/groupdocs.signature.options/metadatasignoptions/__init__/#signatures) | Initialiseert een nieuw exemplaar van [`MetadataSignOptions`](/signature/python-net/groupdocs.signature.options/metadatasignoptions/) met metadata. |

### Methoden
| Methode | Beschrijving |
| :- | :- |
| [add](/signature/python-net/groupdocs.signature.options/metadatasignoptions/add/#metadata_signature) | Voeg een bestaande MetadataSignature‑instantie toe aan de collectie. |
| [add_image_signature](/signature/python-net/groupdocs.signature.options/metadatasignoptions/add_image_signature/#id-value) | Maakt een nieuwe ImageMetadataSignature aan met de opgegeven argumenten en voegt deze toe aan de collectie. |
| [add_image_signature_uint16](/signature/python-net/groupdocs.signature.options/metadatasignoptions/add_image_signature_uint16/) |  |
| [add_metadata_signature](/signature/python-net/groupdocs.signature.options/metadatasignoptions/add_metadata_signature/) |  |
| [add_pdf_signature](/signature/python-net/groupdocs.signature.options/metadatasignoptions/add_pdf_signature/#name-value-tag) | Maakt een nieuwe PdfMetadataSignature aan met de opgegeven argumenten en voegt deze toe aan de collectie. |
| [add_pdf_signature_file](/signature/python-net/groupdocs.signature.options/metadatasignoptions/add_pdf_signature_file/) |  |
| [add_pdf_signature_string](/signature/python-net/groupdocs.signature.options/metadatasignoptions/add_pdf_signature_string/) |  |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [data_encryption](/signature/python-net/groupdocs.signature.options/metadatasignoptions/data_encryption/) | De implementatie van [`IDataEncryption`](/signature/python-net/groupdocs.signature.domain.extensions/idataencryption/) die wordt gebruikt om alle metadata‑handtekeningen in deze opties‑collectie te versleutelen. |
| [signatures](/signature/python-net/groupdocs.signature.options/metadatasignoptions/signatures/) | De metadata‑handtekeningen die aan de handtekening zijn gekoppeld. |
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
from datetime import datetime
from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSignOptions
from groupdocs.signature.domain import WordProcessingMetadataSignature

with Signature("sample.docx") as signature:
    options = MetadataSignOptions()
    signatures = [
        WordProcessingMetadataSignature("Author", "Mr.Scherlock Holmes"),
        WordProcessingMetadataSignature("DateCreated", datetime.now()),
        WordProcessingMetadataSignature("DocumentId", 123456),
        WordProcessingMetadataSignature("SignatureId", 123.456),
    ]
    options.signatures.add_range(signatures)
    result = signature.sign("signed.docx", options)
    print(f"Signed with {len(result.succeeded)} metadata signature(s).")
```

### Zie ook
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
