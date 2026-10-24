---
title: "Clase WordProcessingSaveOptions"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Representa las opciones de guardado para documentos de procesamiento de texto."
type: docs
url: /es/python-net/groupdocs.signature.options/wordprocessingsaveoptions/
is_root: false
weight: 650
---


## WordProcessingSaveOptions class

Representa las opciones de guardado para documentos de procesamiento de texto.

El tipo WordProcessingSaveOptions expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/wordprocessingsaveoptions/__init__/) | Inicializa una nueva instancia de la clase WordProcessingSaveOptions con valores predeterminados. |
| [__init__](/signature/python-net/groupdocs.signature.options/wordprocessingsaveoptions/__init__/#file_format) | Inicializa una nueva instancia de WordProcessingSaveOptions con el formato de archivo de salida especificado. |
| [__init__](/signature/python-net/groupdocs.signature.options/wordprocessingsaveoptions/__init__/#overwrite_existing_file) | Inicializa una nueva instancia de WordProcessingSaveOptions con el tipo de salida especificado y la bandera de sobrescritura. |
| [__init__](/signature/python-net/groupdocs.signature.options/wordprocessingsaveoptions/__init__/#file_format-overwrite_existing_file) | Inicializa una nueva instancia de WordProcessingSaveOptions con el formato de archivo de salida especificado y la bandera de sobrescritura. |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [file_format](/signature/python-net/groupdocs.signature.options/wordprocessingsaveoptions/file_format/) | El formato de archivo del documento firmado. |
| [ooxml_compliance](/signature/python-net/groupdocs.signature.options/wordprocessingsaveoptions/ooxml_compliance/) | El nivel opcional de cumplimiento OOXML para el documento firmado. |
| [add_missing_extenstion](/signature/python-net/groupdocs.signature.options/saveoptions/add_missing_extenstion/) | La bandera que determina si se agrega automáticamente una extensión cuando falta en la ruta del archivo de salida. El valor predeterminado es False. (heredado de [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [overwrite_existing_files](/signature/python-net/groupdocs.signature.options/saveoptions/overwrite_existing_files/) | La bandera que indica si se debe sobrescribir un archivo existente con el nuevo archivo de salida. (heredado de [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [password](/signature/python-net/groupdocs.signature.options/saveoptions/password/) | La contraseña utilizada para proteger el documento firmado guardado. No compatible con documentos de Imagen. (heredado de [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [use_original_password](/signature/python-net/groupdocs.signature.options/saveoptions/use_original_password/) | La bandera que indica si se debe usar la contraseña de [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/) al guardar el documento firmado como protegido. El valor predeterminado es True. No compatible con documentos de Imagen. (heredado de [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |

### Ver también
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
