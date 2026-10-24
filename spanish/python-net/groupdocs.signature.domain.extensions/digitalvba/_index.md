---
title: "Clase DigitalVBA"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Representa la firma digital para proyectos VBA de hojas de cálculo."
type: docs
url: /es/python-net/groupdocs.signature.domain.extensions/digitalvba/
is_root: false
weight: 60
---


## DigitalVBA class

Representa la firma digital para proyectos VBA de hojas de cálculo.

Proporciona la capacidad de firmar un proyecto VBA en formatos de documentos de hoja de cálculo como `Xlsm` o `Xltm`. Si se añaden múltiples extensiones [`DigitalVBA`](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/) a [`DigitalSignOptions.extensions`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/), solo la primera se usa durante la firma.

El tipo DigitalVBA expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/__init__/#certificate_file_path-password) | Inicializa una nueva instancia de la clase DigitalVBA con un archivo de certificado. |
| [__init__](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/__init__/#certificate_stream-password) | Inicializa una nueva instancia de la clase DigitalVBA con un flujo de certificado. |

### Métodos
| Método | Descripción |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain.extensions/signatureextension/clone/) | Obtiene una copia de este objeto. (heredado de [`SignatureExtension`](/signature/python-net/groupdocs.signature.domain.extensions/signatureextension/)) |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [certificate_file_path](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/certificate_file_path/) | La ruta del archivo del certificado digital, usada solo si `CertificateStream` no está especificado. |
| [certificate_stream](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/certificate_stream/) | El flujo del certificado digital. Si esta propiedad está especificada, siempre se usa en lugar de CertificateFilePath. |
| [comments](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/comments/) | Los comentarios de la firma. |
| [password](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/password/) | La contraseña del certificado digital. |
| [sign_only_vba_project](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/sign_only_vba_project/) | La configuración que determina si solo se firma el proyecto VBA. Cuando es True, el propio documento de hoja de cálculo no se firma; solo se firma el proyecto VBA. |

### Ejemplo

```python
import zipfile
from groupdocs.signature import Signature
from groupdocs.signature.domain.extensions import DigitalVBA
from groupdocs.signature.options import DigitalSignOptions


def sign_spreadsheet_macros_only():
    # Firmar macros dentro de la hoja de cálculo
    with Signature("sample.xlsm") as signature:
        sign_options = DigitalSignOptions()

        # Agregar extensión para firmar digitalmente el proyecto VBA
        digital_vba = DigitalVBA("certificate.pfx", "1234567890")
        digital_vba.sign_only_vba_project = True
        digital_vba.comments = "Signed VBA macros"
        sign_options.extensions.append(digital_vba)

        result = signature.sign("signed_macros.xlsm", sign_options)
        print(f"Signatures added: {len(result.succeeded)}")

    # Verificar que la parte de firma del proyecto VBA fue añadida
    with zipfile.ZipFile("signed_macros.xlsm") as package:
        print("VBA project signed:", "xl/vbaProjectSignature.bin" in package.namelist())
```

### Ver también
* module [`groupdocs.signature.domain.extensions`](/signature/python-net/groupdocs.signature.domain.extensions/)
