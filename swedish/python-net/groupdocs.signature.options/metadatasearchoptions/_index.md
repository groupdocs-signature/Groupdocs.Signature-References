---
title: "MetadataSearchOptions-klass"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Representerar sökalternativ för metadata‑signaturer."
type: docs
url: /sv/python-net/groupdocs.signature.options/metadatasearchoptions/
is_root: false
weight: 310
---


## MetadataSearchOptions class

Representerar sökalternativ för metadata‑signaturer.

Tillhandahåller alternativ för att konfigurera sökning efter metadata‑signaturer i ett dokument.

- Basic usage of search for Metadata electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+Metadata+e-signatures
- Advanced usage of settings of search for Metadata electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+built-in+Metadata+signatures

MetadataSearchOptions‑typen visar följande medlemmar:

### Konstruktörer
| Konstruktor | Beskrivning |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/metadatasearchoptions/__init__/) | Initierar en ny instans av MetadataSearchOptions‑klassen med standardvärden. |

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [data_encryption](/signature/python-net/groupdocs.signature.options/metadatasearchoptions/data_encryption/) | Implementeringen av [`IDataEncryption`](/signature/python-net/groupdocs.signature.domain.extensions/idataencryption/) som används för att dekryptera alla metadata‑signaturer i denna alternativsamling. |
| [include_builtin_properties](/signature/python-net/groupdocs.signature.options/metadatasearchoptions/include_builtin_properties/) | Flaggan som anger om inbyggda dokumentegenskaper såsom dokumentstatistik och information inkluderas i sökresultatet. |
| [name](/signature/python-net/groupdocs.signature.options/metadatasearchoptions/name/) | Metadata‑signaturens namn att söka efter och matcha. |
| [name_match_type](/signature/python-net/groupdocs.signature.options/metadatasearchoptions/name_match_type/) | Matchningstypen för metadata‑namn som används vid sökning. Den tillämpas endast när egenskapen `name` är angiven. |
| [all_pages](/signature/python-net/groupdocs.signature.options/searchoptions/all_pages/) | Flaggan som anger om varje dokumentsida ska genomsökas. Standardvärdet är True. (ärvd från [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/searchoptions/page_number/) | Dokumentsidans nummer för sökning (valfritt). (ärvd från [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/searchoptions/pages_setup/) | Alternativen för att ange sidor för signatursökning. (ärvd från [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/searchoptions/shape_position/) | Flaggan som anger om formens position i dokumentlayouten ska returneras. Endast tillgänglig för Word‑dokument. (ärvd från [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [skip_external](/signature/python-net/groupdocs.signature.options/searchoptions/skip_external/) | Flaggan för att endast returnera signaturer markerade som `IsSignature`. Standardvärdet är `False`, vilket innebär att alla signaturer som matchar de angivna kriterierna returneras. (ärvd från [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |

### Exempel

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

### Se även
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
