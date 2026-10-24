---
title: "Clase SignatureSettings"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Representa la configuración para personalizar el comportamiento de Signature."
type: docs
url: /es/python-net/groupdocs.signature/signaturesettings/
is_root: false
weight: 140
---


## SignatureSettings class

Representa la configuración para personalizar el comportamiento de [`Signature`](/signature/python-net/groupdocs.signature/signature/).

El tipo SignatureSettings expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature/signaturesettings/__init__/) | Inicializa una instancia predeterminada de SignatureSettings con valores por defecto. |
| [__init__](/signature/python-net/groupdocs.signature/signaturesettings/__init__/#logger) | Inicializa una instancia predeterminada de SignatureSettings con la implementación de Logger. |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [default_culture](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/) | La cultura predeterminada utilizada durante el procesamiento de documentos. El valor predeterminado es "en-US". |
| [include_standard_metadata_signatures](/signature/python-net/groupdocs.signature/signaturesettings/include_standard_metadata_signatures/) | La bandera que indica si las firmas de metadatos de documento estándar, como Autor, Propietario, fecha de creación y fecha de modificación, están incluidas en la lista de metadatos. |
| [log_level](/signature/python-net/groupdocs.signature/signaturesettings/log_level/) | Las banderas de nivel de registro que determinan qué tipos de mensajes se envían a [`SignatureSettings.Logger`](/signature/python-net/groupdocs.signature/signaturesettings/logger/). |
| [logger](/signature/python-net/groupdocs.signature/signaturesettings/logger/) | La implementación del registrador utilizada para el registro (Errores, Advertencias, Trazas). [`ILogger`](/signature/python-net/groupdocs.signature.logging/ilogger/). |
| [save_document_on_empty_delete](/signature/python-net/groupdocs.signature/signaturesettings/save_document_on_empty_delete/) | La bandera que determina si el documento fuente se vuelve a guardar cuando el método Delete no tiene firmas afectadas que eliminar. |
| [save_document_on_empty_update](/signature/python-net/groupdocs.signature/signaturesettings/save_document_on_empty_update/) | La bandera que determina si el documento fuente se vuelve a guardar cuando el método `Update` no tiene firmas para actualizar. |
| [show_deleted_signatures_info](/signature/python-net/groupdocs.signature/signaturesettings/show_deleted_signatures_info/) | La bandera que determina si las firmas eliminadas se incluyen en el resultado de información del documento. Cada [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) tiene una bandera `Deleted` que indica si fue eliminada. |

### Ver también
* module [`groupdocs.signature`](/signature/python-net/groupdocs.signature/)
