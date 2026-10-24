---
title: "FormFieldSearchOptions-klass"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Representerar sökalternativ för formulärfältsignaturer."
type: docs
url: /sv/python-net/groupdocs.signature.options/formfieldsearchoptions/
is_root: false
weight: 170
---


## FormFieldSearchOptions class

Representerar sökalternativ för formulärfältsignaturer.

Läs mer:
- Basic usage of search for FormField electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+Form+Field+e-signatures
- Advanced usage of settings of search for FormField electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Advanced+search+for+Form+Field+signatures

FormFieldSearchOptions-typen exponerar följande medlemmar:

### Konstruktörer
| Konstruktor | Beskrivning |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/formfieldsearchoptions/__init__/) | Initierar en ny instans av FormFieldSearchOptions-klass med standardvärden. |

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [name](/signature/python-net/groupdocs.signature.options/formfieldsearchoptions/name/) | Reguljärt uttrycksmönster som används för att matcha ett formulärfältssignaturnamn under sökning. |
| [type](/signature/python-net/groupdocs.signature.options/formfieldsearchoptions/type/) | Typen av formulärfältssignatur att söka efter. Standardvärdet är None. |
| [value](/signature/python-net/groupdocs.signature.options/formfieldsearchoptions/value/) | Värdet för formulärfältssignaturen att söka efter. Standard är None. |
| [all_pages](/signature/python-net/groupdocs.signature.options/searchoptions/all_pages/) | Flaggan som anger om varje dokumentsida ska genomsökas. Standardvärdet är True. (ärvd från [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/searchoptions/page_number/) | Dokumentsidans nummer för sökning (valfritt). (ärvd från [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/searchoptions/pages_setup/) | Alternativen för att ange sidor för signatursökning. (ärvd från [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/searchoptions/shape_position/) | Flaggan som anger om formens position i dokumentlayouten ska returneras. Endast tillgänglig för Word‑dokument. (ärvd från [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [skip_external](/signature/python-net/groupdocs.signature.options/searchoptions/skip_external/) | Flaggan för att endast returnera signaturer markerade som `IsSignature`. Standardvärdet är `False`, vilket innebär att alla signaturer som matchar de angivna kriterierna returneras. (ärvd från [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |

### Exempel

```python
from groupdocs.signature import Signature
from groupdocs.signature.domain import FormFieldType
from groupdocs.signature.options import FormFieldSearchOptions


def search_form_fields_by_name():
    with Signature("signed.pdf") as signature:
        options = FormFieldSearchOptions()
        # Returnera endast textfält med namnet "ApprovedBy"
        options.type = FormFieldType.TEXT
        options.name = "ApprovedBy"

        result = signature.search([options])

        print(f"Found {len(result.signatures)} matching form field signature(s)")
        for field in result.signatures:
            print(f"Field '{field.name}' on page {field.page_number}, value: {field.value}")


if __name__ == "__main__":
    search_form_fields_by_name()
```

### Se även
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
