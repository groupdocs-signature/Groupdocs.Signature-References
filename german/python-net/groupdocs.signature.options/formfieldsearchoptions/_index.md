---
title: "FormFieldSearchOptions Klasse"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Stellt Suchoptionen für Formularfeld-Signaturen dar."
type: docs
url: /de/python-net/groupdocs.signature.options/formfieldsearchoptions/
is_root: false
weight: 170
---


## FormFieldSearchOptions class

Stellt Suchoptionen für Formularfeld-Signaturen dar.

Mehr erfahren:
- Basic usage of search for FormField electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+Form+Field+e-signatures
- Advanced usage of settings of search for FormField electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Advanced+search+for+Form+Field+signatures

Der Typ FormFieldSearchOptions stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/formfieldsearchoptions/__init__/) | Initialisiert eine neue Instanz der FormFieldSearchOptions Klasse mit Standardwerten. |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [name](/signature/python-net/groupdocs.signature.options/formfieldsearchoptions/name/) | Das reguläre Ausdrucksmuster, das verwendet wird, um einen Formularfeldsignaturnamen während der Suche zu finden. |
| [type](/signature/python-net/groupdocs.signature.options/formfieldsearchoptions/type/) | Der Typ der gesuchten Formularfeldsignatur. Standardwert ist None. |
| [value](/signature/python-net/groupdocs.signature.options/formfieldsearchoptions/value/) | Der Wert der gesuchten Formularfeldsignatur. Standard ist None. |
| [all_pages](/signature/python-net/groupdocs.signature.options/searchoptions/all_pages/) | Das Flag, das angibt, ob auf jeder Dokumentseite gesucht werden soll. Standardmäßig ist dieser Wert True. (geerbt von [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/searchoptions/page_number/) | Die Dokumentseitennummer für die Suche (optional). (geerbt von [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/searchoptions/pages_setup/) | Die Optionen, um Seiten für die Signatursuche anzugeben. (geerbt von [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/searchoptions/shape_position/) | Das Flag, das angibt, ob die Position der Form im Dokumentlayout zurückgegeben werden soll. Nur für Word‑Dokumente verfügbar. (geerbt von [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [skip_external](/signature/python-net/groupdocs.signature.options/searchoptions/skip_external/) | Das Flag, um nur Signaturen zurückzugeben, die als `IsSignature` markiert sind. Standardmäßig ist der Wert `False`, was bedeutet, dass alle Signaturen, die den angegebenen Kriterien entsprechen, zurückgegeben werden. (geerbt von [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |

### Beispiel

```python
from groupdocs.signature import Signature
from groupdocs.signature.domain import FormFieldType
from groupdocs.signature.options import FormFieldSearchOptions


def search_form_fields_by_name():
    with Signature("signed.pdf") as signature:
        options = FormFieldSearchOptions()
        # Nur Textfelder mit dem Namen "ApprovedBy" zurückgeben
        options.type = FormFieldType.TEXT
        options.name = "ApprovedBy"

        result = signature.search([options])

        print(f"Found {len(result.signatures)} matching form field signature(s)")
        for field in result.signatures:
            print(f"Field '{field.name}' on page {field.page_number}, value: {field.value}")


if __name__ == "__main__":
    search_form_fields_by_name()
```

### Siehe auch
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
