---
title: "Clase FormFieldSearchOptions"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Representa las opciones de búsqueda para firmas de campos de formulario."
type: docs
url: /es/python-net/groupdocs.signature.options/formfieldsearchoptions/
is_root: false
weight: 170
---


## FormFieldSearchOptions class

Representa las opciones de búsqueda para firmas de campos de formulario.

Más información:
- Basic usage of search for FormField electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+Form+Field+e-signatures
- Advanced usage of settings of search for FormField electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Advanced+search+for+Form+Field+signatures

El tipo FormFieldSearchOptions expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/formfieldsearchoptions/__init__/) | Inicializa una nueva instancia de la clase FormFieldSearchOptions con valores predeterminados. |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [name](/signature/python-net/groupdocs.signature.options/formfieldsearchoptions/name/) | El patrón de expresión regular utilizado para coincidir con el nombre de la firma de campo de formulario durante la búsqueda. |
| [type](/signature/python-net/groupdocs.signature.options/formfieldsearchoptions/type/) | El tipo de firma de campo de formulario a buscar. El valor predeterminado es None. |
| [value](/signature/python-net/groupdocs.signature.options/formfieldsearchoptions/value/) | El valor de la firma de campo de formulario a buscar. El valor predeterminado es None. |
| [all_pages](/signature/python-net/groupdocs.signature.options/searchoptions/all_pages/) | La bandera que indica si buscar en cada página del documento. Por defecto este valor es True. (heredado de [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/searchoptions/page_number/) | El número de página del documento para buscar (opcional). (heredado de [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/searchoptions/pages_setup/) | Las opciones para especificar páginas para la búsqueda de firmas. (heredado de [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/searchoptions/shape_position/) | La bandera que indica si devolver la posición de la forma en el diseño del documento. Disponible solo para documentos Word. (heredado de [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [skip_external](/signature/python-net/groupdocs.signature.options/searchoptions/skip_external/) | La bandera para devolver solo firmas marcadas como `IsSignature`. Por defecto el valor es `False`, lo que indica que se devuelven todas las firmas que coinciden con el criterio especificado. (heredado de [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |

### Ejemplo

```python
from groupdocs.signature import Signature
from groupdocs.signature.domain import FormFieldType
from groupdocs.signature.options import FormFieldSearchOptions


def search_form_fields_by_name():
    with Signature("signed.pdf") as signature:
        options = FormFieldSearchOptions()
        # Devuelve solo los campos de texto nombrados "ApprovedBy"
        options.type = FormFieldType.TEXT
        options.name = "ApprovedBy"

        result = signature.search([options])

        print(f"Found {len(result.signatures)} matching form field signature(s)")
        for field in result.signatures:
            print(f"Field '{field.name}' on page {field.page_number}, value: {field.value}")


if __name__ == "__main__":
    search_form_fields_by_name()
```

### Ver también
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
