---
title: "Clase PdfMetadataSignature"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Representa una firma de metadatos PDF."
type: docs
url: /es/python-net/groupdocs.signature.domain/pdfmetadatasignature/
is_root: false
weight: 440
---


## PdfMetadataSignature class

Representa una firma de metadatos PDF.

El tipo PdfMetadataSignature expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignature/__init__/#name) | Inicializa una firma de metadatos PDF con un nombre predefinido y un valor vacío. |
| [__init__](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignature/__init__/#name-value) | Inicializa una firma de metadatos PDF con valores predefinidos. |
| [__init__](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignature/__init__/#name-value-tag) | Inicializa una firma de metadatos PDF con valores predefinidos. |

### Métodos
| Método | Descripción |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignature/clone/) | Clonar instancia de Metadata Signature. |
| [clone](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignature/clone/#value) | Clona una instancia de firma de metadatos PDF con el valor proporcionado. |
| [clone_object](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignature/clone_object/) |  |
| [equals](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignature/equals/#obj) | Compara esta firma con otra para determinar igualdad basándose en sus propiedades. |
| [equals_object](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignature/equals_object/) |  |
| [get_hash_code](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignature/get_hash_code/) | Devuelve el código hash de la firma. |
| [get_data](/signature/python-net/groupdocs.signature.domain/metadatasignature/get_data/) | (heredado de [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [get_data_idata_encryption](/signature/python-net/groupdocs.signature.domain/metadatasignature/get_data_idata_encryption/) | (heredado de [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [to_boolean](/signature/python-net/groupdocs.signature.domain/metadatasignature/to_boolean/) | Convierte a booleano. (heredado de [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [to_date_time](/signature/python-net/groupdocs.signature.domain/metadatasignature/to_date_time/) | Convierte el valor de la firma de metadatos a una fecha y hora. (heredado de [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [to_date_time_iformat_provider](/signature/python-net/groupdocs.signature.domain/metadatasignature/to_date_time_iformat_provider/) | (heredado de [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [to_decimal](/signature/python-net/groupdocs.signature.domain/metadatasignature/to_decimal/) | Convierte el valor de la firma de metadatos a Decimal. (heredado de [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [to_decimal_iformat_provider](/signature/python-net/groupdocs.signature.domain/metadatasignature/to_decimal_iformat_provider/) | (heredado de [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [to_double](/signature/python-net/groupdocs.signature.domain/metadatasignature/to_double/) | Convierte el valor de la firma de metadatos a un número de punto flotante. (heredado de [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [to_double_iformat_provider](/signature/python-net/groupdocs.signature.domain/metadatasignature/to_double_iformat_provider/) | (heredado de [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [to_integer](/signature/python-net/groupdocs.signature.domain/metadatasignature/to_integer/) | Convierte el valor de la firma de metadatos a un entero. (heredado de [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [to_single](/signature/python-net/groupdocs.signature.domain/metadatasignature/to_single/) | Convierte el valor de la firma de metadatos a un número de punto flotante. (heredado de [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [to_single_iformat_provider](/signature/python-net/groupdocs.signature.domain/metadatasignature/to_single_iformat_provider/) | (heredado de [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [to_string](/signature/python-net/groupdocs.signature.domain/metadatasignature/to_string/) | Convierte la firma de metadatos a una cadena. (heredado de [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [to_string_file](/signature/python-net/groupdocs.signature.domain/metadatasignature/to_string_file/) | (heredado de [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [to_string_string](/signature/python-net/groupdocs.signature.domain/metadatasignature/to_string_string/) | (heredado de [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [tag_prefix](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignature/tag_prefix/) | La etiqueta de prefijo del nombre de una firma de metadatos PDF. Por defecto, esta propiedad está establecida en "xmp". |
| [created_on](/signature/python-net/groupdocs.signature.domain/basesignature/created_on/) | La fecha de creación de la firma. (heredado de [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [data_encryption](/signature/python-net/groupdocs.signature.domain/metadatasignature/data_encryption/) | La implementación de [`IDataEncryption`](/signature/python-net/groupdocs.signature.domain.extensions/idataencryption/) utilizada para codificar y decodificar las propiedades del valor de la firma. (heredado de [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [deleted](/signature/python-net/groupdocs.signature.domain/basesignature/deleted/) | El indicador que muestra si esta firma fue eliminada del documento. (heredado de [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [height](/signature/python-net/groupdocs.signature.domain/basesignature/height/) | La altura de la firma. (heredado de [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [is_signature](/signature/python-net/groupdocs.signature.domain/basesignature/is_signature/) | El indicador que muestra si este componente representa una firma (`True`) o contenido del documento (`False`). (heredado de [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [left](/signature/python-net/groupdocs.signature.domain/basesignature/left/) | La posición izquierda de la firma. (heredado de [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [modified_on](/signature/python-net/groupdocs.signature.domain/basesignature/modified_on/) | La fecha de modificación de la firma. (heredado de [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [name](/signature/python-net/groupdocs.signature.domain/metadatasignature/name/) | El nombre único de los metadatos. (heredado de [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [page_number](/signature/python-net/groupdocs.signature.domain/basesignature/page_number/) | El número de página donde se encontró la firma. (heredado de [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [signature_id](/signature/python-net/groupdocs.signature.domain/basesignature/signature_id/) | El identificador único de la firma, utilizado para modificar la firma en el documento mediante operaciones de actualización o eliminación. (heredado de [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [signature_type](/signature/python-net/groupdocs.signature.domain/basesignature/signature_type/) | El tipo de firma. (heredado de [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [top](/signature/python-net/groupdocs.signature.domain/basesignature/top/) | La posición superior de la firma. (heredado de [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [type](/signature/python-net/groupdocs.signature.domain/metadatasignature/type/) | El tipo de valor de los metadatos. (heredado de [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [value](/signature/python-net/groupdocs.signature.domain/metadatasignature/value/) | El objeto de metadatos. (heredado de [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [width](/signature/python-net/groupdocs.signature.domain/basesignature/width/) | El ancho de la firma. (heredado de [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |

### Ejemplo

```python
from datetime import datetime
from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSignOptions
from groupdocs.signature.domain import PdfMetadataSignature

with Signature("sample.pdf") as signature:
    options = MetadataSignOptions()
    options.add(PdfMetadataSignature("Author", "Mr.Scherlock Holmes"))
    options.add(PdfMetadataSignature("CreatedOn", datetime.now()))
    options.add(PdfMetadataSignature("DocumentId", 123456))
    options.add(PdfMetadataSignature("SignatureId", 123.456))
    result = signature.sign("signed.pdf", options)
    print(f"Signed with {len(result.succeeded)} metadata signature(s):")
    for item in result.succeeded:
        print(f"  {item.name}")
```

### Ver también
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
