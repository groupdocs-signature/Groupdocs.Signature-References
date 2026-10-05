---
title: FormFieldSearchOptions class
second_title: GroupDocs.Signature for Python via .NET API References
description: "Represents search options for Form-field signatures."
type: docs
url: /python-net/groupdocs.signature.options/formfieldsearchoptions/
is_root: false
weight: 170
---


## FormFieldSearchOptions class

Represents search options for Form-field signatures.

Learn more:
- Basic usage of search for FormField electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+Form+Field+e-signatures
- Advanced usage of settings of search for FormField electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Advanced+search+for+Form+Field+signatures

The FormFieldSearchOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/formfieldsearchoptions/__init__/) | Initializes a new instance of the FormFieldSearchOptions class with default values. |

### Properties
| Property | Description |
| :- | :- |
| [name](/signature/python-net/groupdocs.signature.options/formfieldsearchoptions/name/) | The regular expression pattern used to match a form field signature name during search. |
| [type](/signature/python-net/groupdocs.signature.options/formfieldsearchoptions/type/) | The type of form field signature to search for. Default value is None. |
| [value](/signature/python-net/groupdocs.signature.options/formfieldsearchoptions/value/) | The value of the form field signature to search for. Default is None. |
| [all_pages](/signature/python-net/groupdocs.signature.options/searchoptions/all_pages/) | The flag indicating whether to search on each document page. By default this value is True. (inherited from [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/searchoptions/page_number/) | The document page number for searching (optional). (inherited from [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/searchoptions/pages_setup/) | The options to specify pages for signature searching. (inherited from [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/searchoptions/shape_position/) | The flag indicating whether to return the shape position in the document layout. Available only for Word documents. (inherited from [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [skip_external](/signature/python-net/groupdocs.signature.options/searchoptions/skip_external/) | The flag to return only signatures marked as `IsSignature`. By default the value is `False`, which indicates that all signatures matching the specified criteria are returned. (inherited from [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |

### Example

```python
from groupdocs.signature import Signature
from groupdocs.signature.domain import FormFieldType
from groupdocs.signature.options import FormFieldSearchOptions


def search_form_fields_by_name():
    with Signature("signed.pdf") as signature:
        options = FormFieldSearchOptions()
        # Return only text fields named "ApprovedBy"
        options.type = FormFieldType.TEXT
        options.name = "ApprovedBy"

        result = signature.search([options])

        print(f"Found {len(result.signatures)} matching form field signature(s)")
        for field in result.signatures:
            print(f"Field '{field.name}' on page {field.page_number}, value: {field.value}")


if __name__ == "__main__":
    search_form_fields_by_name()
```

### See Also
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
