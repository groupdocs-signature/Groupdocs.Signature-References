---
title: "Clase TextSignature"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "La clase TextSignature contiene propiedades de firma de texto."
type: docs
url: /es/python-net/groupdocs.signature.domain/textsignature/
is_root: false
weight: 770
---


## TextSignature class

La clase TextSignature contiene propiedades de firma de texto.

El tipo TextSignature expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/textsignature/__init__/#signature_id) | Inicializa un objeto TextSignature con el identificador único de firma obtenido de una operación de firma o búsqueda. |

### Métodos
| Método | Descripción |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/textsignature/clone/) | Clona la instancia de Text Signature. |
| [equals](/signature/python-net/groupdocs.signature.domain/textsignature/equals/#obj) | Compara la firma especificada con esta instancia para igualdad. |
| [equals_object](/signature/python-net/groupdocs.signature.domain/textsignature/equals_object/) |  |
| [get_hash_code](/signature/python-net/groupdocs.signature.domain/textsignature/get_hash_code/) | Devuelve el código hash de la firma. |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [native](/signature/python-net/groupdocs.signature.domain/textsignature/native/) | El atributo nativo que indica si la firma es específica del documento. |
| [signature_implementation](/signature/python-net/groupdocs.signature.domain/textsignature/signature_implementation/) | La implementación de la firma de texto. |
| [text](/signature/python-net/groupdocs.signature.domain/textsignature/text/) | El texto de la firma. |
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
from groupdocs.signature.options import TextSearchOptions

with Signature("signed.pdf") as signature:
    result = signature.search([TextSearchOptions()])
    for text_sig in result.signatures:
        print(f"Text: {text_sig.text}, Position: ({text_sig.left}, {text_sig.top}), Size: {text_sig.width}x{text_sig.height}")
```

### Ver también
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
