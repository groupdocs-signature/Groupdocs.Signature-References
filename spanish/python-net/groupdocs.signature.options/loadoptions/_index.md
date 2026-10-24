---
title: "Clase LoadOptions"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "La clase LoadOptions permite especificar opciones adicionales (como la contraseña) al abrir un documento para firmar."
type: docs
url: /es/python-net/groupdocs.signature.options/loadoptions/
is_root: false
weight: 300
---


## LoadOptions class

La clase LoadOptions permite especificar opciones adicionales (como la contraseña) al abrir un documento para firmar.

Establezca el atributo `password` a la contraseña del documento si el archivo está encriptado.

El tipo LoadOptions expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/loadoptions/__init__/) | Inicializa una nueva instancia de la clase LoadOptions. |
| [__init__](/signature/python-net/groupdocs.signature.options/loadoptions/__init__/#file_type) | Inicializa una nueva instancia de la clase [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/) con un tipo de archivo especificado. |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [file_type](/signature/python-net/groupdocs.signature.options/loadoptions/file_type/) | El tipo de archivo asociado con las opciones de carga, por defecto [`FileType.unknown`](/signature/python-net/groupdocs.signature.domain/filetype/unknown/). |
| [load_external_resources](/signature/python-net/groupdocs.signature.options/loadoptions/load_external_resources/) | La bandera que determina si el documento carga recursos externos. Esta propiedad está obsoleta; use [`LoadOptions.SkipExternalResources`](/signature/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/) en su lugar, que tiene el significado opuesto. |
| [password](/signature/python-net/groupdocs.signature.options/loadoptions/password/) | La contraseña utilizada para abrir un documento protegido y para guardar un documento firmado como protegido. |
| [permissions](/signature/python-net/groupdocs.signature.options/loadoptions/permissions/) | Los permisos del documento PDF, como impresión, modificación y extracción de datos. Solo para documentos PDF. |
| [skip_external_resources](/signature/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/) | La bandera que impide que el documento cargue recursos externos. El valor predeterminado es True; los recursos externos no se cargan excepto aquellos que coinciden con [`LoadOptions.WhitelistedResources`](/signature/python-net/groupdocs.signature.options/loadoptions/whitelisted_resources/). |
| [whitelisted_resources](/signature/python-net/groupdocs.signature.options/loadoptions/whitelisted_resources/) | La lista de fragmentos de direcciones de recursos externos que se cargan incluso cuando [`LoadOptions.SkipExternalResources`](/signature/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/) es true. El valor predeterminado es una lista vacía. |

### Ejemplo

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import LoadOptions

load_options = LoadOptions()
load_options.password = "1234567890"
with Signature("protected.pdf", load_options) as signature:
    info = signature.get_document_info()
    print(f"{info.file_type.file_format}, {info.page_count} page(s), {info.size} bytes")
```

### Ver también
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
