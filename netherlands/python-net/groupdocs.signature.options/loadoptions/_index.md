---
title: "LoadOptions klasse"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "De LoadOptions-klasse maakt het mogelijk extra opties (zoals wachtwoord) op te geven bij het openen van een document om te ondertekenen."
type: docs
url: /nl/python-net/groupdocs.signature.options/loadoptions/
is_root: false
weight: 300
---


## LoadOptions class

De LoadOptions-klasse maakt het mogelijk extra opties (zoals wachtwoord) op te geven bij het openen van een document om te ondertekenen.

Stel de `password`‑attribuut in op het documentwachtwoord als het bestand versleuteld is.

Het type LoadOptions bevat de volgende leden:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/loadoptions/__init__/) | Initialiseert een nieuw exemplaar van de LoadOptions klasse. |
| [__init__](/signature/python-net/groupdocs.signature.options/loadoptions/__init__/#file_type) | Initialiseert een nieuw exemplaar van de [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/) klasse met een gespecificeerd bestandstype. |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [file_type](/signature/python-net/groupdocs.signature.options/loadoptions/file_type/) | Het bestandstype dat aan de laadopties is gekoppeld, standaard ingesteld op [`FileType.unknown`](/signature/python-net/groupdocs.signature.domain/filetype/unknown/). |
| [load_external_resources](/signature/python-net/groupdocs.signature.options/loadoptions/load_external_resources/) | De vlag die bepaalt of het document externe bronnen laadt. Deze eigenschap is verouderd; gebruik in plaats daarvan [`LoadOptions.SkipExternalResources`](/signature/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/), die de tegenovergestelde betekenis heeft. |
| [password](/signature/python-net/groupdocs.signature.options/loadoptions/password/) | Het wachtwoord dat wordt gebruikt om een beschermd document te openen en om een ondertekend document als beschermd op te slaan. |
| [permissions](/signature/python-net/groupdocs.signature.options/loadoptions/permissions/) | De PDF‑documentrechten zoals afdrukken, wijzigen en gegevensextractie. Alleen voor PDF‑documenten. |
| [skip_external_resources](/signature/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/) | De vlag die voorkomt dat het document externe bronnen laadt. De standaardwaarde is True; externe bronnen worden niet geladen behalve die die overeenkomen met [`LoadOptions.WhitelistedResources`](/signature/python-net/groupdocs.signature.options/loadoptions/whitelisted_resources/). |
| [whitelisted_resources](/signature/python-net/groupdocs.signature.options/loadoptions/whitelisted_resources/) | De lijst met adresfragmenten van externe bronnen die worden geladen, zelfs wanneer [`LoadOptions.SkipExternalResources`](/signature/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/) true is. De standaardwaarde is een lege lijst. |

### Voorbeeld

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import LoadOptions

load_options = LoadOptions()
load_options.password = "1234567890"
with Signature("protected.pdf", load_options) as signature:
    info = signature.get_document_info()
    print(f"{info.file_type.file_format}, {info.page_count} page(s), {info.size} bytes")
```

### Zie ook
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
