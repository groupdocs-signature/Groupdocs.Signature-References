---
title: "Clase PngSaveOptions"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Las opciones de guardado PNG para documentos de imagen."
type: docs
url: /es/python-net/groupdocs.signature.options/pngsaveoptions/
is_root: false
weight: 400
---


## PngSaveOptions class

Las opciones de guardado PNG para documentos de imagen.

El tipo PngSaveOptions expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/pngsaveoptions/__init__/) | Inicializa PngSaveOptions con valores predeterminados. |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [bit_depth](/signature/python-net/groupdocs.signature.options/pngsaveoptions/bit_depth/) | La profundidad de bits. |
| [color_type](/signature/python-net/groupdocs.signature.options/pngsaveoptions/color_type/) | El tipo de `PngColorType`. |
| [compression_level](/signature/python-net/groupdocs.signature.options/pngsaveoptions/compression_level/) | El nivel de compresión de la imagen png en el rango 0-9, donde 9 es la compresión máxima y 0 es modo de almacenamiento. |
| [filter_type](/signature/python-net/groupdocs.signature.options/pngsaveoptions/filter_type/) | El tipo de filtro `PngFilterType` utilizado durante el proceso de guardado del archivo PNG. |
| [progressive](/signature/python-net/groupdocs.signature.options/pngsaveoptions/progressive/) | La bandera progresiva que indica si el PNG se guarda de forma progresiva. |
| [add_missing_extenstion](/signature/python-net/groupdocs.signature.options/saveoptions/add_missing_extenstion/) | La bandera que determina si se agrega automáticamente una extensión cuando falta en la ruta del archivo de salida. El valor predeterminado es False. (heredado de [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [file_format](/signature/python-net/groupdocs.signature.options/imagesaveoptions/file_format/) | El formato de archivo del documento firmado. (heredado de [`ImageSaveOptions`](/signature/python-net/groupdocs.signature.options/imagesaveoptions/)) |
| [overwrite_existing_files](/signature/python-net/groupdocs.signature.options/saveoptions/overwrite_existing_files/) | La bandera que indica si se debe sobrescribir un archivo existente con el nuevo archivo de salida. (heredado de [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [password](/signature/python-net/groupdocs.signature.options/saveoptions/password/) | La contraseña utilizada para proteger el documento firmado guardado. No compatible con documentos de Imagen. (heredado de [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [use_original_password](/signature/python-net/groupdocs.signature.options/saveoptions/use_original_password/) | La bandera que indica si se debe usar la contraseña de [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/) al guardar el documento firmado como protegido. El valor predeterminado es True. No compatible con documentos de Imagen. (heredado de [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |

### Ver también
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
