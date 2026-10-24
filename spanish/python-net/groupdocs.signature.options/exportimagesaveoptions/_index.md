---
title: "Clase ExportImageSaveOptions"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Representa las opciones de guardado para exportar documentos a imagen."
type: docs
url: /es/python-net/groupdocs.signature.options/exportimagesaveoptions/
is_root: false
weight: 160
---


## ExportImageSaveOptions class

Representa las opciones de guardado para exportar documentos a imagen.

El tipo ExportImageSaveOptions expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/__init__/) | Inicializa una nueva instancia de la clase ExportAsImageSaveOptions con valores predeterminados. |
| [__init__](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/__init__/#file_format) | Inicializa una nueva instancia de ExportAsImageSaveOptions con el formato de archivo especificado. |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [border](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/border/) | La configuración del borde de la imagen. Por defecto, este valor no está establecido. |
| [export_all_pages](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/export_all_pages/) | La bandera para exportar cada página. |
| [page_columns](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/page_columns/) | El número de columnas para las imágenes exportadas. Use esta propiedad si necesita colocar imágenes en una fila. |
| [page_number](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/page_number/) | El número de página del documento para la exportación (el valor mínimo es 1). |
| [pages_setup](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/pages_setup/) | Las opciones para especificar las páginas a firmar. |
| [tiff_multipage](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/tiff_multipage/) | Las páginas del documento se colocan en diferentes marcos en una imagen TIFF. |
| [add_missing_extenstion](/signature/python-net/groupdocs.signature.options/saveoptions/add_missing_extenstion/) | La bandera que determina si se agrega automáticamente una extensión cuando falta en la ruta del archivo de salida. El valor predeterminado es False. (heredado de [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [file_format](/signature/python-net/groupdocs.signature.options/imagesaveoptions/file_format/) | El formato de archivo del documento firmado. (heredado de [`ImageSaveOptions`](/signature/python-net/groupdocs.signature.options/imagesaveoptions/)) |
| [overwrite_existing_files](/signature/python-net/groupdocs.signature.options/saveoptions/overwrite_existing_files/) | La bandera que indica si se debe sobrescribir un archivo existente con el nuevo archivo de salida. (heredado de [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [password](/signature/python-net/groupdocs.signature.options/saveoptions/password/) | La contraseña utilizada para proteger el documento firmado guardado. No compatible con documentos de Imagen. (heredado de [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [use_original_password](/signature/python-net/groupdocs.signature.options/saveoptions/use_original_password/) | La bandera que indica si se debe usar la contraseña de [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/) al guardar el documento firmado como protegido. El valor predeterminado es True. No compatible con documentos de Imagen. (heredado de [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |

### Ver también
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
