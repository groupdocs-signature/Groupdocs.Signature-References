---
title: "MetadataSearchOptions klasse"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Vertegenwoordigt zoekopties voor metadata-handtekeningen."
type: docs
url: /nl/python-net/groupdocs.signature.options/metadatasearchoptions/
is_root: false
weight: 310
---


## MetadataSearchOptions class

Vertegenwoordigt zoekopties voor metadata-handtekeningen.

Biedt opties om het zoeken naar metadata‑handtekeningen in een document te configureren.

- Basic usage of search for Metadata electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+Metadata+e-signatures
- Advanced usage of settings of search for Metadata electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+built-in+Metadata+signatures

Het type MetadataSearchOptions exposeert de volgende leden:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/metadatasearchoptions/__init__/) | Initialiseert een nieuw exemplaar van de MetadataSearchOptions klasse met standaardwaarden. |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [data_encryption](/signature/python-net/groupdocs.signature.options/metadatasearchoptions/data_encryption/) | De implementatie van [`IDataEncryption`](/signature/python-net/groupdocs.signature.domain.extensions/idataencryption/) die wordt gebruikt om alle metadata‑handtekeningen binnen deze optieverzameling te ontsleutelen. |
| [include_builtin_properties](/signature/python-net/groupdocs.signature.options/metadatasearchoptions/include_builtin_properties/) | De vlag die aangeeft of ingebouwde documenteigenschappen, zoals documentstatistieken en -informatie, zijn opgenomen in het zoekresultaat. |
| [name](/signature/python-net/groupdocs.signature.options/metadatasearchoptions/name/) | De naam van de metadata‑handtekening om naar te zoeken en te matchen. |
| [name_match_type](/signature/python-net/groupdocs.signature.options/metadatasearchoptions/name_match_type/) | Het type metadata‑naammatching dat wordt gebruikt voor zoeken. Het wordt alleen toegepast wanneer de `name`‑eigenschap is ingesteld. |
| [all_pages](/signature/python-net/groupdocs.signature.options/searchoptions/all_pages/) | De vlag die aangeeft of er op elke documentpagina moet worden gezocht. Standaard is deze waarde True. (geërfd van [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/searchoptions/page_number/) | Het paginanummer van het document voor zoeken (optioneel). (geërfd van [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/searchoptions/pages_setup/) | De opties om pagina's op te geven voor handtekeningzoeken. (geërfd van [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/searchoptions/shape_position/) | De vlag die aangeeft of de vormpositie in de documentlay-out moet worden geretourneerd. Alleen beschikbaar voor Word‑documenten. (geërfd van [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [skip_external](/signature/python-net/groupdocs.signature.options/searchoptions/skip_external/) | De vlag om alleen handtekeningen die gemarkeerd zijn als `IsSignature` te retourneren. Standaard is de waarde `False`, wat aangeeft dat alle handtekeningen die aan de opgegeven criteria voldoen, worden geretourneerd. (geërfd van [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |

### Voorbeeld

```python
from groupdocs.signature import Signature
from groupdocs.signature.domain import TextMatchType
from groupdocs.signature.options import MetadataSearchOptions

with Signature("signed.pdf") as signature:
    options = MetadataSearchOptions()
    options.name = "Author"
    options.name_match_type = TextMatchType.EXACT

    result = signature.search([options])
    print(f"Found {len(result.signatures)} matching metadata signature(s)")
    for metadata in result.signatures:
        print(f"{metadata.name} = {metadata.value}")
```

### Zie ook
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
