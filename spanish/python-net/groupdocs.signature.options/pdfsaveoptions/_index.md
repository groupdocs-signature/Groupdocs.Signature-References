---
title: "Clase PdfSaveOptions"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Representa opciones de guardado para documentos PDF."
type: docs
url: /es/python-net/groupdocs.signature.options/pdfsaveoptions/
is_root: false
weight: 340
---


## PdfSaveOptions class

Representa opciones de guardado para documentos PDF.

El tipo PdfSaveOptions expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/__init__/) | Inicializa una nueva instancia de PdfSaveOptions con valores predeterminados. |
| [__init__](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/__init__/#file_format) | Inicializa una nueva instancia de PdfSaveOptions con el formato de archivo de salida especificado. |
| [__init__](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/__init__/#overwrite_existing_file) | Inicializa una nueva instancia de PdfSaveOptions con una bandera de sobrescritura. |
| [__init__](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/__init__/#file_format-overwrite_existing_file) | Inicializa una nueva instancia de PdfSaveOptions con el formato de archivo de salida especificado y la bandera de sobrescritura. |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [file_format](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/file_format/) | El formato de archivo del documento firmado. |
| [permissions](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/permissions/) | Los permisos del documento PDF, como impresión, modificación y extracción de datos. |
| [permissions_password](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/permissions_password/) | La contraseña de permisos (la contraseña principal) requerida para cambiar la configuración de permisos. |
| [add_missing_extenstion](/signature/python-net/groupdocs.signature.options/saveoptions/add_missing_extenstion/) | La bandera que determina si se agrega automáticamente una extensión cuando falta en la ruta del archivo de salida. El valor predeterminado es False. (heredado de [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [overwrite_existing_files](/signature/python-net/groupdocs.signature.options/saveoptions/overwrite_existing_files/) | La bandera que indica si se debe sobrescribir un archivo existente con el nuevo archivo de salida. (heredado de [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [password](/signature/python-net/groupdocs.signature.options/saveoptions/password/) | La contraseña utilizada para proteger el documento firmado guardado. No compatible con documentos de Imagen. (heredado de [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [use_original_password](/signature/python-net/groupdocs.signature.options/saveoptions/use_original_password/) | La bandera que indica si se debe usar la contraseña de [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/) al guardar el documento firmado como protegido. El valor predeterminado es True. No compatible con documentos de Imagen. (heredado de [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |

### Ejemplo

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import LoadOptions, PdfSaveOptions, QrCodeSignOptions
from groupdocs.signature.domain import QrCodeTypes

load_options = LoadOptions()
load_options.password = "1234567890"

save_options = PdfSaveOptions()
save_options.password = "new-password"
save_options.permissions_password = "new-owner-password"
save_options.use_original_password = False

qr_options = QrCodeSignOptions("Approved by John Smith", QrCodeTypes.QR)

with Signature("protected.pdf", load_options) as signature:
    result = signature.sign("signed_new_password.pdf", qr_options, save_options)
    print(f"Signatures added: {len(result.succeeded)}")
```

### Ver también
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
