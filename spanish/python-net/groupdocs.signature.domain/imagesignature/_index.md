---
title: "Clase ImageSignature"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "La clase contiene propiedades de firma de imagen."
type: docs
url: /es/python-net/groupdocs.signature.domain/imagesignature/
is_root: false
weight: 340
---


## ImageSignature class

La clase contiene propiedades de firma de imagen.

El tipo ImageSignature expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/imagesignature/__init__/#signature_id) | Inicializa un objeto ImageSignature con un identificador de firma único obtenido del método Sign o Search de la clase [`GroupDocs.Signature`](/signature/python-net/groupdocs.signature/signature/). |

### Métodos
| Método | Descripción |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/imagesignature/clone/) | Clonar la instancia ImageSignature. |
| [equals](/signature/python-net/groupdocs.signature.domain/imagesignature/equals/#obj) | Determina si la firma especificada es igual a esta instancia. |
| [equals_object](/signature/python-net/groupdocs.signature.domain/imagesignature/equals_object/) |  |
| [get_hash_code](/signature/python-net/groupdocs.signature.domain/imagesignature/get_hash_code/) | Devuelve el código hash de la firma. |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [content](/signature/python-net/groupdocs.signature.domain/imagesignature/content/) | Los datos binarios de imagen de la firma, en el formato especificado por [`ImageSignature.Format`](/signature/python-net/groupdocs.signature.domain/imagesignature/format/). |
| [format](/signature/python-net/groupdocs.signature.domain/imagesignature/format/) | El formato de la imagen de la firma. |
| [size](/signature/python-net/groupdocs.signature.domain/imagesignature/size/) | El tamaño en bytes de la imagen de la firma. |
| [created_on](/signature/python-net/groupdocs.signature.domain/basesignature/created_on/) | La fecha de creación de la firma. (heredado de [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [deleted](/signature/python-net/groupdocs.signature.domain/basesignature/deleted/) | El indicador que muestra si esta firma fue eliminada del documento. (heredado de [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [height](/signature/python-net/groupdocs.signature.domain/basesignature/height/) | La altura de la firma. (heredado de [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [is_signature](/signature/python-net/groupdocs.signature.domain/basesignature/is_signature/) | El indicador que muestra si este componente representa una firma (`True`) o contenido del documento (`False`). (heredado de [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [left](/signature/python-net/groupdocs.signature.domain/basesignature/left/) | La posición izquierda de la firma. (heredado de [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [modified_on](/signature/python-net/groupdocs.signature.domain/basesignature/modified_on/) | La fecha de modificación de la firma. (heredado de [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [page_number](/signature/python-net/groupdocs.signature.domain/basesignature/page_number/) | El número de página donde se encontró la firma. (heredado de [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [signature_id](/signature/python-net/groupdocs.signature.domain/basesignature/signature_id/) | El identificador único de la firma, utilizado para modificar la firma en el documento mediante operaciones de actualización o eliminación. (heredado de [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [signature_type](/signature/python-net/groupdocs.signature.domain/basesignature/signature_type/) | El tipo de firma. (heredado de [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [top](/signature/python-net/groupdocs.signature.domain/basesignature/top/) | La posición superior de la firma. (heredado de [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [width](/signature/python-net/groupdocs.signature.domain/basesignature/width/) | El ancho de la firma. (heredado de [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |

### Ejemplo

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import ImageSearchOptions

with Signature("signed.pdf") as signature:
    result = signature.search([ImageSearchOptions()])
    for image in result.signatures:
        print(
            f"Page {image.page_number}: {image.size} bytes at ({image.left}, {image.top}), "
            f"size {image.width}x{image.height}"
        )
```

### Ver también
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
