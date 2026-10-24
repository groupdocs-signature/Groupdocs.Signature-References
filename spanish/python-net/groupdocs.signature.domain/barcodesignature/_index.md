---
title: "Clase BarcodeSignature"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Representa una firma de código de barras."
type: docs
url: /es/python-net/groupdocs.signature.domain/barcodesignature/
is_root: false
weight: 20
---


## BarcodeSignature class

Representa una firma de código de barras.

El tipo BarcodeSignature expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/barcodesignature/__init__/#signature_id) | Inicializa un objeto BarcodeSignature con un identificador de firma obtenido después de un proceso de búsqueda. El identificador se utiliza para recuperar propiedades adicionales de esta firma desde la capa de información de firmas del documento. |

### Métodos
| Método | Descripción |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/barcodesignature/clone/) | Clona la instancia de Barcode Signature. |
| [equals](/signature/python-net/groupdocs.signature.domain/barcodesignature/equals/#obj) | Compara esta firma de código de barras con otra firma para determinar igualdad. |
| [equals_object](/signature/python-net/groupdocs.signature.domain/barcodesignature/equals_object/) |  |
| [get_hash_code](/signature/python-net/groupdocs.signature.domain/barcodesignature/get_hash_code/) | Devuelve el código hash de la firma de código de barras. |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [content](/signature/python-net/groupdocs.signature.domain/barcodesignature/content/) | El contenido de la imagen de datos binarios del código de barras en el formato especificado por [`BarcodeSignature.format`](/signature/python-net/groupdocs.signature.domain/barcodesignature/format/). |
| [encode_type](/signature/python-net/groupdocs.signature.domain/barcodesignature/encode_type/) | El tipo de codificación del código de barras. |
| [format](/signature/python-net/groupdocs.signature.domain/barcodesignature/format/) | El formato de la imagen de la firma de código de barras. |
| [text](/signature/python-net/groupdocs.signature.domain/barcodesignature/text/) | El texto del código de barras. |
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

### Ver también
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
