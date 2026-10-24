---
title: "Clase QrCodeSearchOptions"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Representa opciones de búsqueda para firmas de código QR."
type: docs
url: /es/python-net/groupdocs.signature.options/qrcodesearchoptions/
is_root: false
weight: 470
---


## QrCodeSearchOptions class

Representa opciones de búsqueda para firmas de código QR.

- Basic usage of search for QR-Code electronic signature by GroupDocs.Signature: How to eSearch QR-Code signatures in a document (https://docs.groupdocs.com/display/signaturenet/Search+for+QR-Code+e-signatures)
- Advanced usage of settings of search for QR-Code electronic signature with GroupDocs.Signature: Advanced usage of eSearch QR-Code signatures in a document and additional settings (https://docs.groupdocs.com/display/signaturenet/Advanced+search+for+QR-code+signatures)

El tipo QrCodeSearchOptions expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/__init__/) | Inicializa una nueva instancia de la clase QRCodeSearchOptions con valores predeterminados. |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/__init__/#encode_type) | Inicializa una nueva instancia de la clase QRCodeSearchOptions con el valor del tipo de codificación. |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/__init__/#encode_type-text) | Inicializa una nueva instancia de la clase QRCodeSearchOptions con los valores de tipo de codificación y texto. |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [data_encryption](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/data_encryption/) | La implementación de [`IDataEncryption`](/signature/python-net/groupdocs.signature.domain.extensions/idataencryption/) se utiliza para codificar y decodificar el texto o las propiedades de datos de la firma QR-Code. |
| [encode_type](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/encode_type/) | El tipo de codificación para buscar códigos QR. |
| [match_type](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/match_type/) | El tipo de coincidencia de texto QR-Code utilizado durante la búsqueda. |
| [return_content](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/return_content/) | La bandera que determina si el contenido de imagen QR‑Code se devuelve para cada firma en una página del documento. Cuando se establece en True, los datos de imagen sin procesar se guardan en la propiedad `content` de la firma usando el formato especificado por `return_content_type`. Deshabilitado por defecto. |
| [return_content_type](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/return_content_type/) | El tipo de archivo del contenido de imagen devuelto de la firma QR-Code cuando la propiedad `return_content` está habilitada. |
| [text](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/text/) | El texto de la firma QR-Code a buscar y coincidir. |
| [all_pages](/signature/python-net/groupdocs.signature.options/searchoptions/all_pages/) | La bandera que indica si buscar en cada página del documento. Por defecto este valor es True. (heredado de [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/searchoptions/page_number/) | El número de página del documento para buscar (opcional). (heredado de [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/searchoptions/pages_setup/) | Las opciones para especificar páginas para la búsqueda de firmas. (heredado de [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/searchoptions/shape_position/) | La bandera que indica si devolver la posición de la forma en el diseño del documento. Disponible solo para documentos Word. (heredado de [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [skip_external](/signature/python-net/groupdocs.signature.options/searchoptions/skip_external/) | La bandera para devolver solo firmas marcadas como `IsSignature`. Por defecto el valor es `False`, lo que indica que se devuelven todas las firmas que coinciden con el criterio especificado. (heredado de [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |

### Ejemplo

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import QrCodeSearchOptions

with Signature("signed.pdf") as signature:
    result = signature.search([QrCodeSearchOptions()])
    print(f"Found {len(result.signatures)} QR code signature(s)")
    for qr in result.signatures:
        print(f"QR code signature found at page {qr.page_number} with type {qr.encode_type.type_name} and text '{qr.text}'")
```

### Ver también
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
