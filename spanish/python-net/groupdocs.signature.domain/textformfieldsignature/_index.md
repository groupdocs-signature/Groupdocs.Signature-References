---
title: "Clase TextFormFieldSignature"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Representa propiedades de firma de campo de formulario de entrada de texto para documentos PDF."
type: docs
url: /es/python-net/groupdocs.signature.domain/textformfieldsignature/
is_root: false
weight: 730
---


## TextFormFieldSignature class

Representa propiedades de firma de campo de formulario de entrada de texto para documentos PDF.

El tipo TextFormFieldSignature expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/__init__/#name) | Inicializa un PdfTextFormFieldSignature con un nombre predefinido. |
| [__init__](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/__init__/#name-text) | Inicializa un PdfTextFormFieldSignature con un nombre predefinido. |

### Métodos
| Método | Descripción |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/clone/) | Clona la instancia de FormField Signature. |
| [equals](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/equals/#obj) | Compara esta firma con otra firma para determinar igualdad basada en el tipo y los valores de las propiedades. |
| [equals_object](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/equals_object/) |  |
| [get_hash_code](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/get_hash_code/) | Sobrescribe el método GetHashCode. |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [text](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/text/) | El texto de la entrada del campo de formulario. |
| [created_on](/signature/python-net/groupdocs.signature.domain/basesignature/created_on/) | La fecha de creación de la firma. (heredado de [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [deleted](/signature/python-net/groupdocs.signature.domain/basesignature/deleted/) | El indicador que muestra si esta firma fue eliminada del documento. (heredado de [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [height](/signature/python-net/groupdocs.signature.domain/basesignature/height/) | La altura de la firma. (heredado de [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [is_signature](/signature/python-net/groupdocs.signature.domain/basesignature/is_signature/) | El indicador que muestra si este componente representa una firma (`True`) o contenido del documento (`False`). (heredado de [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [left](/signature/python-net/groupdocs.signature.domain/basesignature/left/) | La posición izquierda de la firma. (heredado de [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [modified_on](/signature/python-net/groupdocs.signature.domain/basesignature/modified_on/) | La fecha de modificación de la firma. (heredado de [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [name](/signature/python-net/groupdocs.signature.domain/formfieldsignature/name/) | El nombre único del campo de formulario. (heredado de [`FormFieldSignature`](/signature/python-net/groupdocs.signature.domain/formfieldsignature/)) |
| [page_number](/signature/python-net/groupdocs.signature.domain/basesignature/page_number/) | El número de página donde se encontró la firma. (heredado de [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [signature_id](/signature/python-net/groupdocs.signature.domain/basesignature/signature_id/) | El identificador único de la firma, utilizado para modificar la firma en el documento mediante operaciones de actualización o eliminación. (heredado de [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [signature_type](/signature/python-net/groupdocs.signature.domain/basesignature/signature_type/) | El tipo de firma. (heredado de [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [top](/signature/python-net/groupdocs.signature.domain/basesignature/top/) | La posición superior de la firma. (heredado de [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [type](/signature/python-net/groupdocs.signature.domain/formfieldsignature/type/) | El tipo de campo de formulario. (heredado de [`FormFieldSignature`](/signature/python-net/groupdocs.signature.domain/formfieldsignature/)) |
| [value](/signature/python-net/groupdocs.signature.domain/formfieldsignature/value/) | El objeto de datos del campo de formulario. (heredado de [`FormFieldSignature`](/signature/python-net/groupdocs.signature.domain/formfieldsignature/)) |
| [width](/signature/python-net/groupdocs.signature.domain/basesignature/width/) | El ancho de la firma. (heredado de [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |

### Ejemplo

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import FormFieldSignOptions
from groupdocs.signature.domain import TextFormFieldSignature


def sign_with_form_field_signature():
    with Signature("sample.pdf") as signature:
        # Crea un campo de formulario de texto llamado "FieldText" con el valor "Value1"
        text_field = TextFormFieldSignature("FieldText", "Value1")

        # Crea opciones de campo de formulario para él
        options = FormFieldSignOptions(text_field)

        # Establece la posición y el tamaño del campo de formulario
        options.left = 100
        options.top = 400
        options.width = 200
        options.height = 20

        # Firma el documento y guarda el resultado
        result = signature.sign("signed_form_field.pdf", options)
        for field in result.succeeded:
            print(f"Added form field '{field.name}' with value '{field.value}'")
```

### Ver también
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
