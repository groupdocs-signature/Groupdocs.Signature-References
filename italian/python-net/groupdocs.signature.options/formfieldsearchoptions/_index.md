---
title: "classe FormFieldSearchOptions"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Rappresenta le opzioni di ricerca per le firme Form-field."
type: docs
url: /it/python-net/groupdocs.signature.options/formfieldsearchoptions/
is_root: false
weight: 170
---


## FormFieldSearchOptions class

Rappresenta le opzioni di ricerca per le firme Form-field.

Per saperne di più:
- Basic usage of search for FormField electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+Form+Field+e-signatures
- Advanced usage of settings of search for FormField electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Advanced+search+for+Form+Field+signatures

Il tipo FormFieldSearchOptions espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/formfieldsearchoptions/__init__/) | Inizializza una nuova istanza della classe FormFieldSearchOptions con valori predefiniti. |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [name](/signature/python-net/groupdocs.signature.options/formfieldsearchoptions/name/) | Il modello di espressione regolare utilizzato per corrispondere a un nome di firma del campo modulo durante la ricerca. |
| [type](/signature/python-net/groupdocs.signature.options/formfieldsearchoptions/type/) | Il tipo di firma del campo modulo da cercare. Il valore predefinito è None. |
| [value](/signature/python-net/groupdocs.signature.options/formfieldsearchoptions/value/) | Il valore della firma del campo modulo da cercare. Il valore predefinito è None. |
| [all_pages](/signature/python-net/groupdocs.signature.options/searchoptions/all_pages/) | Il flag che indica se eseguire la ricerca su ogni pagina del documento. Per impostazione predefinita questo valore è True. (eredita da [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/searchoptions/page_number/) | Il numero di pagina del documento per la ricerca (opzionale). (eredita da [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/searchoptions/pages_setup/) | Le opzioni per specificare le pagine per la ricerca della firma. (eredita da [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/searchoptions/shape_position/) | Il flag che indica se restituire la posizione della forma nel layout del documento. Disponibile solo per i documenti Word. (eredita da [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [skip_external](/signature/python-net/groupdocs.signature.options/searchoptions/skip_external/) | Il flag per restituire solo le firme contrassegnate come `IsSignature`. Per impostazione predefinita il valore è `False`, il che indica che vengono restituite tutte le firme che corrispondono ai criteri specificati. (eredita da [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |

### Esempio

```python
from groupdocs.signature import Signature
from groupdocs.signature.domain import FormFieldType
from groupdocs.signature.options import FormFieldSearchOptions


def search_form_fields_by_name():
    with Signature("signed.pdf") as signature:
        options = FormFieldSearchOptions()
        # Restituisci solo i campi di testo denominati "ApprovedBy"
        options.type = FormFieldType.TEXT
        options.name = "ApprovedBy"

        result = signature.search([options])

        print(f"Found {len(result.signatures)} matching form field signature(s)")
        for field in result.signatures:
            print(f"Field '{field.name}' on page {field.page_number}, value: {field.value}")


if __name__ == "__main__":
    search_form_fields_by_name()
```

### Vedi anche
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
