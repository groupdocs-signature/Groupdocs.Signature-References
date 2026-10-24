---
title: "Clase JpegSaveOptions"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Representa opciones de guardado JPEG para documentos de imagen."
type: docs
url: /es/python-net/groupdocs.signature.options/jpegsaveoptions/
is_root: false
weight: 290
---


## JpegSaveOptions class

Representa opciones de guardado JPEG para documentos de imagen.

El tipo JpegSaveOptions expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/jpegsaveoptions/__init__/) | Inicializa JpegSaveOptions con valores predeterminados. |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [bits_per_channel](/signature/python-net/groupdocs.signature.options/jpegsaveoptions/bits_per_channel/) | El número de bits por canal para una imagen JPEG sin pérdida. Los valores compatibles son de 2 a 8 bits por canal. |
| [color_type](/signature/python-net/groupdocs.signature.options/jpegsaveoptions/color_type/) | El tipo de color para la imagen JPEG. |
| [comment](/signature/python-net/groupdocs.signature.options/jpegsaveoptions/comment/) | El comentario del archivo JPEG. |
| [compression_type](/signature/python-net/groupdocs.signature.options/jpegsaveoptions/compression_type/) | El tipo de compresión. |
| [quality](/signature/python-net/groupdocs.signature.options/jpegsaveoptions/quality/) | La calidad de la imagen. |
| [sample_rounding_mode](/signature/python-net/groupdocs.signature.options/jpegsaveoptions/sample_rounding_mode/) | El modo de redondeo de muestra utilizado para ajustar un valor de 8 bits a un valor de n bits de `JpegOptions.BitsPerChannel`. |
| [add_missing_extenstion](/signature/python-net/groupdocs.signature.options/saveoptions/add_missing_extenstion/) | La bandera que determina si se agrega automáticamente una extensión cuando falta en la ruta del archivo de salida. El valor predeterminado es False. (heredado de [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [file_format](/signature/python-net/groupdocs.signature.options/imagesaveoptions/file_format/) | El formato de archivo del documento firmado. (heredado de [`ImageSaveOptions`](/signature/python-net/groupdocs.signature.options/imagesaveoptions/)) |
| [overwrite_existing_files](/signature/python-net/groupdocs.signature.options/saveoptions/overwrite_existing_files/) | La bandera que indica si se debe sobrescribir un archivo existente con el nuevo archivo de salida. (heredado de [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [password](/signature/python-net/groupdocs.signature.options/saveoptions/password/) | La contraseña utilizada para proteger el documento firmado guardado. No compatible con documentos de Imagen. (heredado de [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [use_original_password](/signature/python-net/groupdocs.signature.options/saveoptions/use_original_password/) | La bandera que indica si se debe usar la contraseña de [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/) al guardar el documento firmado como protegido. El valor predeterminado es True. No compatible con documentos de Imagen. (heredado de [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |

### Ver también
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
