---
title: "Clase BarcodeSearchOptions"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Representa las opciones de búsqueda para firmas de código de barras."
type: docs
url: /es/python-net/groupdocs.signature.options/barcodesearchoptions/
is_root: false
weight: 10
---


## BarcodeSearchOptions class

Representa las opciones de búsqueda para firmas de código de barras.

Más información:
- Basic usage of search for Barcode electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+Barcode+e-signatures
- Advanced usage of settings of search for Barcode electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Advanced+search+for+Barcode+signatures

El tipo BarcodeSearchOptions expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/__init__/) | Inicializa una nueva instancia de la clase BarcodeSearchOptions con valores predeterminados. |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/__init__/#encode_type) | Inicializa una nueva instancia de la clase BarcodeSearchOptions con el valor del tipo de codificación. |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/__init__/#encode_type-text) | Inicializa una nueva instancia de la clase BarcodeSearchOptions con los valores del tipo de codificación y texto. |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [encode_type](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/encode_type/) | El tipo de codificación utilizado para filtrar la búsqueda de códigos de barras; si no se establece, la búsqueda incluye todos los tipos de códigos de barras compatibles. |
| [match_type](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/match_type/) | El tipo de coincidencia de texto de código de barras utilizado para la búsqueda. Se usa solo cuando la propiedad `text` está establecida. |
| [return_content](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/return_content/) | La bandera que indica si se debe recuperar el contenido de imagen del código de barras de una firma en una página del documento. |
| [return_content_type](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/return_content_type/) | El tipo de archivo del contenido de imagen devuelto para una firma de código de barras cuando la propiedad `return_content` está habilitada. |
| [text](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/text/) | El texto de la firma de código de barras que se buscará y coincidirá. |
| [all_pages](/signature/python-net/groupdocs.signature.options/searchoptions/all_pages/) | La bandera que indica si buscar en cada página del documento. Por defecto este valor es True. (heredado de [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/searchoptions/page_number/) | El número de página del documento para buscar (opcional). (heredado de [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/searchoptions/pages_setup/) | Las opciones para especificar páginas para la búsqueda de firmas. (heredado de [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/searchoptions/shape_position/) | La bandera que indica si devolver la posición de la forma en el diseño del documento. Disponible solo para documentos Word. (heredado de [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [skip_external](/signature/python-net/groupdocs.signature.options/searchoptions/skip_external/) | La bandera para devolver solo firmas marcadas como `IsSignature`. Por defecto el valor es `False`, lo que indica que se devuelven todas las firmas que coinciden con el criterio especificado. (heredado de [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |

### Ejemplo

```python
from groupdocs.signature import Signature
from groupdocs.signature.domain import BarcodeTypes, TextMatchType
from groupdocs.signature.options import BarcodeSearchOptions

with Signature("signed.pdf") as signature:
    options = BarcodeSearchOptions()
    options.all_pages = False
    options.page_number = 1
    options.encode_type = BarcodeTypes.CODE128
    options.text = "1234"
    options.match_type = TextMatchType.STARTS_WITH

    result = signature.search([options])
    print(f"Found {len(result.signatures)} matching barcode signature(s)")
```

### Guides
Guías de tareas que usan `BarcodeSearchOptions`:

* [Search for Barcode e-Signatures](/signature/python-net/guides/search-for-barcode-e-signatures/)

### Ver también
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
