---
title: "Clase ImageSearchOptions"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Representa opciones de búsqueda para firmas de Imagen."
type: docs
url: /es/python-net/groupdocs.signature.options/imagesearchoptions/
is_root: false
weight: 240
---


## ImageSearchOptions class

Representa opciones de búsqueda para firmas de Imagen.

Más información:
- Basic usage of search for Image electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+Image+e-signatures
- Advanced usage of settings of search for Image electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Advanced+search+for+Image+signatures

El tipo ImageSearchOptions expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/imagesearchoptions/__init__/) | Inicializa una nueva instancia de la clase ImageSearchOptions con valores predeterminados. |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [max_content_size](/signature/python-net/groupdocs.signature.options/imagesearchoptions/max_content_size/) | El tamaño máximo de imágenes para el criterio de búsqueda, en bytes. |
| [min_content_size](/signature/python-net/groupdocs.signature.options/imagesearchoptions/min_content_size/) | El tamaño mínimo de datos de imagen, en bytes, que se considerará durante una búsqueda. Un valor distinto de cero especifica el tamaño mínimo; el valor predeterminado es cero, lo que no afecta el resultado de la búsqueda. |
| [return_content](/signature/python-net/groupdocs.signature.options/imagesearchoptions/return_content/) | La bandera que determina si se devuelve el contenido de imagen de una firma. |
| [return_content_type](/signature/python-net/groupdocs.signature.options/imagesearchoptions/return_content_type/) | El tipo de archivo del contenido de imagen devuelto cuando la propiedad `return_content` está habilitada. |
| [all_pages](/signature/python-net/groupdocs.signature.options/searchoptions/all_pages/) | La bandera que indica si buscar en cada página del documento. Por defecto este valor es True. (heredado de [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/searchoptions/page_number/) | El número de página del documento para buscar (opcional). (heredado de [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/searchoptions/pages_setup/) | Las opciones para especificar páginas para la búsqueda de firmas. (heredado de [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/searchoptions/shape_position/) | La bandera que indica si devolver la posición de la forma en el diseño del documento. Disponible solo para documentos Word. (heredado de [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [skip_external](/signature/python-net/groupdocs.signature.options/searchoptions/skip_external/) | La bandera para devolver solo firmas marcadas como `IsSignature`. Por defecto el valor es `False`, lo que indica que se devuelven todas las firmas que coinciden con el criterio especificado. (heredado de [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |

### Ejemplo

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import ImageSearchOptions

def extract_image_signatures():
    with Signature("signed.pdf") as signature:
        options = ImageSearchOptions()
        options.all_pages = False          # search the first page only
        options.page_number = 1
        options.min_content_size = 1024   # skip images smaller than 1 KB
        options.return_content = True
        options.return_content_type = FileType.PNG

        result = signature.search([options])
        for i, image in enumerate(result.signatures, start=1):
            file_name = f"image_signature_{i}.png"
            with open(file_name, "wb") as out:
                out.write(image.content)
```

### Ver también
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
