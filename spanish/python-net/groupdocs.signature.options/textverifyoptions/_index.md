---
title: "Clase TextVerifyOptions"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Mantiene opciones para verificar la firma de Texto del documento."
type: docs
url: /es/python-net/groupdocs.signature.options/textverifyoptions/
is_root: false
weight: 600
---


## TextVerifyOptions class

Mantiene opciones para verificar la firma de Texto del documento.

Más información:
- Basic usage of verification for Barcode electronic signature by GroupDocs.Signature: [How to eVerification Barcode signatures in a document](https://docs.groupdocs.com/display/signaturenet/Verify+Text+signatures+in+the+document)
- Advanced usage of settings of verification for Barcode electronic signature with GroupDocs.Signature: [Advanced usage of eVerification Barcode signatures in a document and additional settings](https://docs.groupdocs.com/display/signaturenet/Verify+Text+signatures)

El tipo TextVerifyOptions expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/textverifyoptions/__init__/) | Inicializa una nueva instancia de TextVerifyOptions con valores predeterminados. |
| [__init__](/signature/python-net/groupdocs.signature.options/textverifyoptions/__init__/#text) | Inicializa una nueva instancia de TextVerifyOptions con texto de verificación. |
| [__init__](/signature/python-net/groupdocs.signature.options/textverifyoptions/__init__/#text-implementation) | Inicializa una nueva instancia de TextVerifyOptions con el texto a verificar y el tipo de implementación de la firma. |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [form_text_field_title](/signature/python-net/groupdocs.signature.options/textverifyoptions/form_text_field_title/) | El título del campo de formulario a verificar. Si se establece, el texto se encontrará solo en campos de formulario de texto. |
| [form_text_field_type](/signature/python-net/groupdocs.signature.options/textverifyoptions/form_text_field_type/) | El tipo de campo de formulario a verificar; si se establece, el texto se encontrará solo en campos de formulario de texto. |
| [match_type](/signature/python-net/groupdocs.signature.options/textverifyoptions/match_type/) | La verificación del tipo de coincidencia de texto. |
| [signature_id](/signature/python-net/groupdocs.signature.options/textverifyoptions/signature_id/) | El ID de firma de texto a verificar. Debe ser mayor que cero; compatible solo con documentos PDF. |
| [signature_implementation](/signature/python-net/groupdocs.signature.options/textverifyoptions/signature_implementation/) | El tipo de firma a verificar. |
| [text](/signature/python-net/groupdocs.signature.options/textverifyoptions/text/) | El texto de la firma a verificar. |
| [all_pages](/signature/python-net/groupdocs.signature.options/verifyoptions/all_pages/) | La bandera que indica si cada página del documento debe ser verificada. Por defecto el valor es True. (heredado de [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/verifyoptions/extensions/) | Las extensiones adicionales para la verificación de opciones de firma alternativas. (heredado de [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [is_valid](/signature/python-net/groupdocs.signature.options/verifyoptions/is_valid/) | La bandera de propiedad válida. (heredado de [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/verifyoptions/page_number/) | El número de página del documento a verificar; si no se establece, se verifican todas las páginas del documento para la primera aparición (el valor mínimo es 1). (heredado de [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/verifyoptions/pages_setup/) | Las opciones de página para especificar las páginas a verificar. (heredado de [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/verifyoptions/shape_position/) | La posición de la forma en el diseño del documento utilizada para verificar firmas en encabezados/pies de página. (heredado de [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |

### Ejemplo

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextVerifyOptions

def verify_text_signature():
    with Signature("signed.pdf") as signature:
        options = TextVerifyOptions("John Smith")
        result = signature.verify(options)
        print(f"Document is signed by John Smith: {result.is_valid}")

if __name__ == "__main__":
    verify_text_signature()
```

### Guides
Guías de tareas que usan `TextVerifyOptions`:

* [Quick Start Guide](/signature/python-net/guides/quick-start-guide/)

### Ver también
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
