---
title: "Clase WordProcessingMetadataSignature"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Representa una firma de metadatos de procesamiento de texto."
type: docs
url: /es/python-net/groupdocs.signature.domain/wordprocessingmetadatasignature/
is_root: false
weight: 840
---


## WordProcessingMetadataSignature class

Representa una firma de metadatos de procesamiento de texto.

Se usa con [`MetadataSignOptions`](/signature/python-net/groupdocs.signature.options/metadatasignoptions/) para agregar firmas de metadatos a documentos de procesamiento de texto.

El tipo WordProcessingMetadataSignature expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/wordprocessingmetadatasignature/__init__/#name) | Inicializa un WordProcessingMetadataSignature con el nombre especificado y un valor vacío. |
| [__init__](/signature/python-net/groupdocs.signature.domain/wordprocessingmetadatasignature/__init__/#name-value) | Inicializa una firma de metadatos de WordProcessing con valores predefinidos. |

### Métodos
| Método | Descripción |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/wordprocessingmetadatasignature/clone/) | Clonar instancia de Metadata Signature. |
| [clone](/signature/python-net/groupdocs.signature.domain/wordprocessingmetadatasignature/clone/#value) | Crea una clonación de la instancia WordProcessingMetadataSignature con el valor especificado. |
| [clone_object](/signature/python-net/groupdocs.signature.domain/wordprocessingmetadatasignature/clone_object/) |  |
| [to_string](/signature/python-net/groupdocs.signature.domain/wordprocessingmetadatasignature/to_string/) | Convierte la firma de metadatos a una cadena. |
| [to_string](/signature/python-net/groupdocs.signature.domain/wordprocessingmetadatasignature/to_string/#format-provider) | Convierte la firma de metadatos a una cadena con el formato especificado. |
| [to_string_file](/signature/python-net/groupdocs.signature.domain/wordprocessingmetadatasignature/to_string_file/) |  |
| [to_string_string](/signature/python-net/groupdocs.signature.domain/wordprocessingmetadatasignature/to_string_string/) |  |
| [equals](/signature/python-net/groupdocs.signature.domain/metadatasignature/equals/) | Determina si la firma especificada es igual a esta instancia. (heredado de [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [equals_object](/signature/python-net/groupdocs.signature.domain/metadatasignature/equals_object/) | (heredado de [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [get_data](/signature/python-net/groupdocs.signature.domain/metadatasignature/get_data/) | (heredado de [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [get_data_idata_encryption](/signature/python-net/groupdocs.signature.domain/metadatasignature/get_data_idata_encryption/) | (heredado de [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [get_hash_code](/signature/python-net/groupdocs.signature.domain/metadatasignature/get_hash_code/) | Devuelve el código hash para la firma de metadatos. (heredado de [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
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

### Propiedades
| Propiedad | Descripción |
| :- | :- |
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
from groupdocs.signature.domain import WordProcessingMetadataSignature

with Signature("sample.docx") as signature:
    options = MetadataSignOptions()
    signatures = [
        WordProcessingMetadataSignature("Author", "Mr. Sherlock Holmes"),
        WordProcessingMetadataSignature("DateCreated", datetime.now()),
        WordProcessingMetadataSignature("DocumentId", 123456),
        WordProcessingMetadataSignature("SignatureId", 123.456),
    ]
    options.signatures.add_range(signatures)
    result = signature.sign("signed.docx", options)
    print(f"Signed with {len(result.succeeded)} metadata signature(s):")
    for item in result.succeeded:
        print(f"  {item.name}")
```

### Ver también
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
