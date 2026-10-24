---
title: "ImageMetadataSignature‑klasse"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Stelt een afbeeldingmetadatahandtekening voor."
type: docs
url: /nl/python-net/groupdocs.signature.domain/imagemetadatasignature/
is_root: false
weight: 320
---


## ImageMetadataSignature class

Stelt een afbeeldingmetadatahandtekening voor.

Metadata‑handtekeningen voor afbeeldingsdocumenten zijn elektronische handtekeningen gebaseerd op metadata‑standaarden voor afbeeldingen zoals EXIF. Elke handtekening wordt geïdentificeerd door een numerieke identifier (0‑65535) en slaat een waarde op van verschillende typen (tekst, datum/tijd, geheel getal, zwevend‑komma).

Het ImageMetadataSignature‑type biedt de volgende leden:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/__init__/#id-value) | Initialiseert een Image Metadata Signature met de opgegeven identifier en waarde. |

### Methoden
| Methode | Beschrijving |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/clone/) | Kloon Metadata Signature‑instantie. |
| [clone](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/clone/#value) | Kloon een ImageMetadataSignature‑instantie met de opgegeven waarde. |
| [clone_object](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/clone_object/) |  |
| [equals](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/equals/#obj) | Bepaalt of het opgegeven handtekeningobject gelijk is aan deze instantie. |
| [equals_object](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/equals_object/) |  |
| [get_hash_code](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/get_hash_code/) | Retourneert de hashcode voor de handtekening. |
| [to_boolean](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_boolean/) | Converteert de metadata‑handtekeningwaarde naar een boolean. |
| [to_date_time](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_date_time/) | Converteert de metadata‑handtekeningwaarde naar een `datetime.datetime`. |
| [to_date_time](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_date_time/#provider) | Converteert de metadata‑handtekeningwaarde naar een `datetime`. |
| [to_date_time_iformat_provider](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_date_time_iformat_provider/) |  |
| [to_decimal](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_decimal/) | Converteert naar Decimal. |
| [to_decimal](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_decimal/#provider) | Converteert de metadata‑handtekeningwaarde naar een decimaal. |
| [to_decimal_iformat_provider](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_decimal_iformat_provider/) |  |
| [to_double](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_double/) | Converteert naar een float. |
| [to_double](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_double/#provider) | Converteert de metadata handtekeningwaarde naar een float. |
| [to_double_iformat_provider](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_double_iformat_provider/) |  |
| [to_integer](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_integer/) | Converteert de metadata handtekeningwaarde naar een integer. |
| [to_long](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_long/) | Converteert naar long. |
| [to_single](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_single/) | Converteert naar float. |
| [to_single](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_single/#provider) | Converteert de metadata handtekeningwaarde naar een float. |
| [to_single_iformat_provider](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_single_iformat_provider/) |  |
| [to_string](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_string/) | Converteert de metadata‑handtekeningwaarde naar een string. |
| [to_string](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_string/#format) | Converteert de metadata‑handtekeningwaarde naar een string met het opgegeven formaat. |
| [to_string](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_string/#format-provider) | Converteert naar een string met het opgegeven formaat. |
| [to_string_file](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_string_file/) |  |
| [to_string_string](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_string_string/) |  |
| [get_data](/signature/python-net/groupdocs.signature.domain/metadatasignature/get_data/) | (geërfd van [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [get_data_idata_encryption](/signature/python-net/groupdocs.signature.domain/metadatasignature/get_data_idata_encryption/) | (geërfd van [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [description](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/description/) | De beschrijving van de standaard Image Metadata-handtekening. |
| [id](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/id/) | De identifier van de Image Metadata-handtekening. Zie de `GroupDocs.Signature.Domain.ImageMetadataSignatures`-klasse die de standaardhandtekening bevat met een vooraf gedefinieerde Id-waarde. |
| [size](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/size/) | De grootte van de metadatawaarde. |
| [created_on](/signature/python-net/groupdocs.signature.domain/basesignature/created_on/) | De datum van handtekeningcreatie. (geërfd van [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [data_encryption](/signature/python-net/groupdocs.signature.domain/metadatasignature/data_encryption/) | De implementatie van [`IDataEncryption`](/signature/python-net/groupdocs.signature.domain.extensions/idataencryption/) die wordt gebruikt om handtekeningwaarde‑eigenschappen te coderen en decoderen. (geërfd van [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [deleted](/signature/python-net/groupdocs.signature.domain/basesignature/deleted/) | De vlag die aangeeft of deze handtekening uit het document is verwijderd. (geërfd van [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [height](/signature/python-net/groupdocs.signature.domain/basesignature/height/) | De hoogte van de handtekening. (geërfd van [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [is_signature](/signature/python-net/groupdocs.signature.domain/basesignature/is_signature/) | De vlag die aangeeft of dit component een handtekening (`True`) of documentinhoud (`False`) vertegenwoordigt. (geërfd van [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [left](/signature/python-net/groupdocs.signature.domain/basesignature/left/) | De linkse positie van de handtekening. (geërfd van [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [modified_on](/signature/python-net/groupdocs.signature.domain/basesignature/modified_on/) | De wijzigingsdatum van de handtekening. (geërfd van [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [name](/signature/python-net/groupdocs.signature.domain/metadatasignature/name/) | De unieke metadata-naam. (geërfd van [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [page_number](/signature/python-net/groupdocs.signature.domain/basesignature/page_number/) | Het paginanummer waarop de handtekening werd gevonden. (geërfd van [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [signature_id](/signature/python-net/groupdocs.signature.domain/basesignature/signature_id/) | De unieke identificatie van de handtekening, gebruikt om de handtekening in het document te wijzigen via update- of delete-bewerkingen. (geërfd van [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [signature_type](/signature/python-net/groupdocs.signature.domain/basesignature/signature_type/) | Het type handtekening. (geërfd van [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [top](/signature/python-net/groupdocs.signature.domain/basesignature/top/) | De bovenste positie van de handtekening. (geërfd van [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [type](/signature/python-net/groupdocs.signature.domain/metadatasignature/type/) | Het metadata-waardetype. (geërfd van [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [value](/signature/python-net/groupdocs.signature.domain/metadatasignature/value/) | Het metadata-object. (geërfd van [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [width](/signature/python-net/groupdocs.signature.domain/basesignature/width/) | De breedte van de handtekening. (geërfd van [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |

### Voorbeeld

```python
from datetime import datetime

from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSignOptions
from groupdocs.signature.domain import ImageMetadataSignature


def sign_png():
    with Signature("sample.png") as signature:
        options = MetadataSignOptions()

        metadata_id = 41996
        options.add(ImageMetadataSignature(metadata_id, "Mr.Scherlock Holmes"))   # text
        options.add(ImageMetadataSignature(metadata_id + 1, datetime.now()))    # date and time
        options.add(ImageMetadataSignature(metadata_id + 2, 123456))            # whole number
        options.add(ImageMetadataSignature(metadata_id + 3, 123.456))           # floating‑point number

        result = signature.sign("signed.png", options)
        print(f"Signed with {len(result.succeeded)} metadata signature(s):")
        for item in result.succeeded:
            print(f"  {item.id}")
```

### Zie ook
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
