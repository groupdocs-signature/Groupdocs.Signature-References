---
title: "LoadOptions-klass"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Klassen LoadOptions tillåter att ange ytterligare alternativ (t.ex. lösenord) när ett dokument öppnas för signering."
type: docs
url: /sv/python-net/groupdocs.signature.options/loadoptions/
is_root: false
weight: 300
---


## LoadOptions class

Klassen LoadOptions tillåter att ange ytterligare alternativ (t.ex. lösenord) när ett dokument öppnas för signering.

Ange attributet `password` till dokumentets lösenord om filen är krypterad.

LoadOptions-typen visar följande medlemmar:

### Konstruktörer
| Konstruktor | Beskrivning |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/loadoptions/__init__/) | Initierar en ny instans av LoadOptions-klassen. |
| [__init__](/signature/python-net/groupdocs.signature.options/loadoptions/__init__/#file_type) | Initierar en ny instans av [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/) klassen med en specificerad filtyp. |

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [file_type](/signature/python-net/groupdocs.signature.options/loadoptions/file_type/) | Filtypen som är associerad med laddningsalternativen, standard är [`FileType.unknown`](/signature/python-net/groupdocs.signature.domain/filetype/unknown/). |
| [load_external_resources](/signature/python-net/groupdocs.signature.options/loadoptions/load_external_resources/) | Flaggan som bestämmer om dokumentet laddar externa resurser. Denna egenskap är föråldrad; använd istället [`LoadOptions.SkipExternalResources`](/signature/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/), som har motsatt betydelse. |
| [password](/signature/python-net/groupdocs.signature.options/loadoptions/password/) | Lösenordet som används för att öppna ett skyddat dokument och för att spara ett signerat dokument som skyddat. |
| [permissions](/signature/python-net/groupdocs.signature.options/loadoptions/permissions/) | PDF-dokumentets behörigheter såsom utskrift, ändring och dataextraktion. Endast för PDF-dokument. |
| [skip_external_resources](/signature/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/) | Flaggan som hindrar dokumentet från att ladda externa resurser. Standardvärdet är True; externa resurser laddas inte förutom de som matchar [`LoadOptions.WhitelistedResources`](/signature/python-net/groupdocs.signature.options/loadoptions/whitelisted_resources/). |
| [whitelisted_resources](/signature/python-net/groupdocs.signature.options/loadoptions/whitelisted_resources/) | Listan med adressfragment för externa resurser som laddas även när [`LoadOptions.SkipExternalResources`](/signature/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/) är true. Standardvärdet är en tom lista. |

### Exempel

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import LoadOptions

load_options = LoadOptions()
load_options.password = "1234567890"
with Signature("protected.pdf", load_options) as signature:
    info = signature.get_document_info()
    print(f"{info.file_type.file_format}, {info.page_count} page(s), {info.size} bytes")
```

### Se även
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
