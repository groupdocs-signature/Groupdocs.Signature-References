---
title: "Clase SaveOptions"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Especifica opciones adicionales (como la contraseña) al guardar un documento para firmar."
type: docs
url: /es/python-net/groupdocs.signature.options/saveoptions/
is_root: false
weight: 520
---


## SaveOptions class

Especifica opciones adicionales (como la contraseña) al guardar un documento para firmar.

El tipo SaveOptions expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/saveoptions/__init__/) | Inicializa una nueva instancia de la clase SaveOptions con valores predeterminados. |
| [__init__](/signature/python-net/groupdocs.signature.options/saveoptions/__init__/#overwrite_existing_file) | Inicializa una nueva instancia de la clase SaveOptions con el tipo de salida especificado y la bandera de sobrescritura. |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [add_missing_extenstion](/signature/python-net/groupdocs.signature.options/saveoptions/add_missing_extenstion/) | La bandera que determina si se debe agregar automáticamente una extensión cuando falta en la ruta del archivo de salida. El valor predeterminado es False. |
| [overwrite_existing_files](/signature/python-net/groupdocs.signature.options/saveoptions/overwrite_existing_files/) | La bandera que indica si se debe sobrescribir un archivo existente con el nuevo archivo de salida. |
| [password](/signature/python-net/groupdocs.signature.options/saveoptions/password/) | La contraseña utilizada para proteger el documento firmado guardado. No compatible con documentos de Imagen. |
| [use_original_password](/signature/python-net/groupdocs.signature.options/saveoptions/use_original_password/) | La bandera que indica si se debe usar la contraseña de [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/) al guardar el documento firmado como protegido. El valor predeterminado es True. No compatible con documentos de Imagen. |

### Ver también
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
