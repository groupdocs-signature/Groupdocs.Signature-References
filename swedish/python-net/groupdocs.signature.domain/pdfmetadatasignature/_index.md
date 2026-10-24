---
title: "PdfMetadataSignature-klass"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Representerar en PDF-metadata‑signatur."
type: docs
url: /sv/python-net/groupdocs.signature.domain/pdfmetadatasignature/
is_root: false
weight: 440
---


## PdfMetadataSignature class

Representerar en PDF-metadata‑signatur.

PdfMetadataSignature-typen visar följande medlemmar:

### Konstruktörer
| Konstruktor | Beskrivning |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignature/__init__/#name) | Initierar en PDF-metadata-signatur med ett fördefinierat namn och ett tomt värde. |
| [__init__](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignature/__init__/#name-value) | Initierar en PDF-metadata-signatur med fördefinierade värden. |
| [__init__](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignature/__init__/#name-value-tag) | Initierar en PDF-metadata-signatur med fördefinierade värden. |

### Metoder
| Metod | Beskrivning |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignature/clone/) | Klona Metadata Signature-instans. |
| [clone](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignature/clone/#value) | Klonar en PDF-metadata-signaturinstans med det angivna värdet. |
| [clone_object](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignature/clone_object/) |  |
| [equals](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignature/equals/#obj) | Jämför den här signaturen med en annan för likhet baserat på dess egenskaper. |
| [equals_object](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignature/equals_object/) |  |
| [get_hash_code](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignature/get_hash_code/) | Returnerar hashkoden för signaturen. |
| [get_data](/signature/python-net/groupdocs.signature.domain/metadatasignature/get_data/) | (ärvd från [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [get_data_idata_encryption](/signature/python-net/groupdocs.signature.domain/metadatasignature/get_data_idata_encryption/) | (ärvd från [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [to_boolean](/signature/python-net/groupdocs.signature.domain/metadatasignature/to_boolean/) | Konverterar till boolean. (ärvd från [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [to_date_time](/signature/python-net/groupdocs.signature.domain/metadatasignature/to_date_time/) | Konverterar metadata-signaturvärdet till en datetime. (ärvd från [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [to_date_time_iformat_provider](/signature/python-net/groupdocs.signature.domain/metadatasignature/to_date_time_iformat_provider/) | (ärvd från [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [to_decimal](/signature/python-net/groupdocs.signature.domain/metadatasignature/to_decimal/) | Konverterar metadata-signaturvärdet till Decimal. (ärvd från [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [to_decimal_iformat_provider](/signature/python-net/groupdocs.signature.domain/metadatasignature/to_decimal_iformat_provider/) | (ärvd från [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [to_double](/signature/python-net/groupdocs.signature.domain/metadatasignature/to_double/) | Konverterar metadata‑signaturvärdet till ett flyttal. (ärvd från [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [to_double_iformat_provider](/signature/python-net/groupdocs.signature.domain/metadatasignature/to_double_iformat_provider/) | (ärvd från [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [to_integer](/signature/python-net/groupdocs.signature.domain/metadatasignature/to_integer/) | Konverterar metadata‑signaturvärdet till ett heltal. (ärvd från [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [to_single](/signature/python-net/groupdocs.signature.domain/metadatasignature/to_single/) | Konverterar metadata‑signaturvärdet till ett flyttal. (ärvd från [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [to_single_iformat_provider](/signature/python-net/groupdocs.signature.domain/metadatasignature/to_single_iformat_provider/) | (ärvd från [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [to_string](/signature/python-net/groupdocs.signature.domain/metadatasignature/to_string/) | Konverterar metadata‑signaturen till en sträng. (ärvd från [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [to_string_file](/signature/python-net/groupdocs.signature.domain/metadatasignature/to_string_file/) | (ärvd från [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [to_string_string](/signature/python-net/groupdocs.signature.domain/metadatasignature/to_string_string/) | (ärvd från [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [tag_prefix](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignature/tag_prefix/) | Prefix‑taggen för ett PDF‑metadata‑signaturnamn. Som standard är denna egenskap satt till "xmp". |
| [created_on](/signature/python-net/groupdocs.signature.domain/basesignature/created_on/) | Signaturens skapelsedatum. (ärvd från [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [data_encryption](/signature/python-net/groupdocs.signature.domain/metadatasignature/data_encryption/) | Implementeringen av [`IDataEncryption`](/signature/python-net/groupdocs.signature.domain.extensions/idataencryption/) som används för att koda och avkoda signaturvärdesegenskaper. (ärvd från [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [deleted](/signature/python-net/groupdocs.signature.domain/basesignature/deleted/) | Flaggan som indikerar om denna signatur har raderats från dokumentet. (ärvd från [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [height](/signature/python-net/groupdocs.signature.domain/basesignature/height/) | Signaturens höjd. (ärvd från [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [is_signature](/signature/python-net/groupdocs.signature.domain/basesignature/is_signature/) | Flaggan som indikerar om denna komponent representerar en signatur (`True`) eller dokumentinnehåll (`False`). (ärvd från [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [left](/signature/python-net/groupdocs.signature.domain/basesignature/left/) | Signaturens vänstra position. (ärvd från [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [modified_on](/signature/python-net/groupdocs.signature.domain/basesignature/modified_on/) | Signaturens ändringsdatum. (ärvd från [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [name](/signature/python-net/groupdocs.signature.domain/metadatasignature/name/) | Det unika metadata‑namnet. (ärvd från [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [page_number](/signature/python-net/groupdocs.signature.domain/basesignature/page_number/) | Sidnumret där signaturen hittades. (ärvd från [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [signature_id](/signature/python-net/groupdocs.signature.domain/basesignature/signature_id/) | Den unika identifieraren för signaturen, som används för att ändra signaturen i dokumentet via uppdaterings‑ eller raderingsoperationer. (ärvd från [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [signature_type](/signature/python-net/groupdocs.signature.domain/basesignature/signature_type/) | Signaturens typ. (ärvd från [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [top](/signature/python-net/groupdocs.signature.domain/basesignature/top/) | Signaturens övre position. (ärvd från [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [type](/signature/python-net/groupdocs.signature.domain/metadatasignature/type/) | Metadata‑värdetypen. (ärvd från [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [value](/signature/python-net/groupdocs.signature.domain/metadatasignature/value/) | Metadata‑objektet. (ärvd från [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [width](/signature/python-net/groupdocs.signature.domain/basesignature/width/) | Signaturens bredd. (ärvd från [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |

### Exempel

```python
from datetime import datetime
from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSignOptions
from groupdocs.signature.domain import PdfMetadataSignature

with Signature("sample.pdf") as signature:
    options = MetadataSignOptions()
    options.add(PdfMetadataSignature("Author", "Mr.Scherlock Holmes"))
    options.add(PdfMetadataSignature("CreatedOn", datetime.now()))
    options.add(PdfMetadataSignature("DocumentId", 123456))
    options.add(PdfMetadataSignature("SignatureId", 123.456))
    result = signature.sign("signed.pdf", options)
    print(f"Signed with {len(result.succeeded)} metadata signature(s):")
    for item in result.succeeded:
        print(f"  {item.name}")
```

### Se även
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
