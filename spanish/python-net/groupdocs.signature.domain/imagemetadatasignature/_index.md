---
title: "Clase ImageMetadataSignature"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Representa una firma de metadatos de imagen."
type: docs
url: /es/python-net/groupdocs.signature.domain/imagemetadatasignature/
is_root: false
weight: 320
---


## ImageMetadataSignature class

Representa una firma de metadatos de imagen.

Las firmas de metadatos para documentos de imagen son firmas electrónicas basadas en estándares de metadatos de imagen como EXIF. Cada firma se identifica mediante un identificador numérico (0‑65535) y almacena un valor de varios tipos (texto, fecha/hora, entero, punto flotante).

El tipo ImageMetadataSignature expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/__init__/#id-value) | Inicializa una firma de metadatos de imagen con el identificador y valor especificados. |

### Métodos
| Método | Descripción |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/clone/) | Clonar instancia de Metadata Signature. |
| [clone](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/clone/#value) | Clona una instancia de ImageMetadataSignature con el valor dado. |
| [clone_object](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/clone_object/) |  |
| [equals](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/equals/#obj) | Determina si el objeto de firma especificado es igual a esta instancia. |
| [equals_object](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/equals_object/) |  |
| [get_hash_code](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/get_hash_code/) | Devuelve el código hash de la firma. |
| [to_boolean](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_boolean/) | Convierte el valor de la firma de metadatos a un booleano. |
| [to_date_time](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_date_time/) | Convierte el valor de la firma de metadatos a un `datetime.datetime`. |
| [to_date_time](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_date_time/#provider) | Convierte el valor de la firma de metadatos a un `datetime`. |
| [to_date_time_iformat_provider](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_date_time_iformat_provider/) |  |
| [to_decimal](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_decimal/) | Convierte a Decimal. |
| [to_decimal](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_decimal/#provider) | Convierte el valor de la firma de metadatos a un decimal. |
| [to_decimal_iformat_provider](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_decimal_iformat_provider/) |  |
| [to_double](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_double/) | Convierte a un float. |
| [to_double](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_double/#provider) | Convierte el valor de la firma de metadatos a un número de punto flotante. |
| [to_double_iformat_provider](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_double_iformat_provider/) |  |
| [to_integer](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_integer/) | Convierte el valor de la firma de metadatos a un entero. |
| [to_long](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_long/) | Convierte a long. |
| [to_single](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_single/) | Convierte a float. |
| [to_single](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_single/#provider) | Convierte el valor de la firma de metadatos a un número de punto flotante. |
| [to_single_iformat_provider](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_single_iformat_provider/) |  |
| [to_string](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_string/) | Convierte el valor de la firma de metadatos a una cadena. |
| [to_string](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_string/#format) | Convierte el valor de la firma de metadatos a una cadena usando el formato especificado. |
| [to_string](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_string/#format-provider) | Convierte a una cadena con el formato especificado. |
| [to_string_file](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_string_file/) |  |
| [to_string_string](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_string_string/) |  |
| [get_data](/signature/python-net/groupdocs.signature.domain/metadatasignature/get_data/) | (heredado de [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [get_data_idata_encryption](/signature/python-net/groupdocs.signature.domain/metadatasignature/get_data_idata_encryption/) | (heredado de [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [description](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/description/) | La descripción de la firma estándar Image Metadata. |
| [id](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/id/) | El identificador de la firma Image Metadata. Consulte la clase `GroupDocs.Signature.Domain.ImageMetadataSignatures` que contiene la firma estándar con un valor Id predefinido. |
| [size](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/size/) | El tamaño del valor de los metadatos. |
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
from groupdocs.signature.domain import ImageMetadataSignature


def sign_png():
    with Signature("sample.png") as signature:
        options = MetadataSignOptions()

        metadata_id = 41996
        options.add(ImageMetadataSignature(metadata_id, "Mr.Scherlock Holmes"))   # text
        options.add(ImageMetadataSignature(metadata_id + 1, datetime.now()))    # date and time
        options.add(ImageMetadataSignature(metadata_id + 2, 123456))            # whole number
        options.add(ImageMetadataSignature(metadata_id + 3, 123.456))           # floating‑point number

        result = signature.sign("signed.png", options)
        print(f"Signed with {len(result.succeeded)} metadata signature(s):")
        for item in result.succeeded:
            print(f"  {item.id}")
```

### Ver también
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
