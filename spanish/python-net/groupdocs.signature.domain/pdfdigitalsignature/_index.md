---
title: "Clase PdfDigitalSignature"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Representa las propiedades de la firma digital PDF."
type: docs
url: /es/python-net/groupdocs.signature.domain/pdfdigitalsignature/
is_root: false
weight: 420
---


## PdfDigitalSignature class

Representa las propiedades de la firma digital PDF.

El tipo PdfDigitalSignature expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/__init__/) | Inicializa una firma digital PDF sin un certificado. |
| [__init__](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/__init__/#store) | Inicializa una firma digital PDF usando el almacén X509 especificado. Se usará el primer certificado del almacén. |
| [__init__](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/__init__/#store-index) | Inicializa una firma digital PDF usando el almacén X509 especificado y el índice del certificado. |
| [__init__](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/__init__/#certificate) | Inicializa una firma digital PDF con el certificado X509 especificado. |

### Métodos
| Método | Descripción |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/clone/) | Clona la instancia de firma digital PDF. |
| [equals](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/equals/#obj) | Compara las propiedades de la firma para determinar la igualdad. |
| [equals_object](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/equals_object/) |  |
| [get_hash_code](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/get_hash_code/) | Sobrescribe el método GetHashCode. |
| [load_digital_signatures](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures/) | Carga firmas digitales de todos los almacenes de certificados X509 del sistema. (heredado de [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)) |
| [load_digital_signatures_file](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures_file/) | (heredado de [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)) |
| [load_digital_signatures_store_name](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures_store_name/) | (heredado de [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)) |
| [load_digital_signatures_string](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures_string/) | (heredado de [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)) |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [contact_info](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/contact_info/) | La información de contacto proporcionada por el firmante para permitir que el destinatario verifique la firma, p. ej., un número de teléfono. |
| [location](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/location/) | El nombre del host CPU o la ubicación física de la firma. |
| [reason](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/reason/) | La razón de la firma, como (I agreeРІР‚В¦). |
| [show_properties](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/show_properties/) | La bandera que obliga a que las propiedades de la firma se muestren u oculten; cuando es true, el campo de firma usa un formato de apariencia predefinido (p.ej., `Digitally signed by {PdfDigitalSignature.contact_info} Date: {Date} Reason: {PdfDigitalSignature.reason} Location: {PdfDigitalSignature.location}`) y por defecto es True. |
| [time_stamp](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/time_stamp/) | La marca de tiempo para una firma digital PDF. El valor predeterminado es None. |
| [type](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/type/) | El tipo de firma digital PDF. |
| [certificate](/signature/python-net/groupdocs.signature.domain/digitalsignature/certificate/) | El certificado X509 asociado con la firma digital. (heredado de [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)) |
| [certificate_custom_store_name](/signature/python-net/groupdocs.signature.domain/digitalsignature/certificate_custom_store_name/) | El nombre de almacén personalizado del certificado. (heredado de [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)) |
| [certificate_store_location](/signature/python-net/groupdocs.signature.domain/digitalsignature/certificate_store_location/) | La ubicación del almacén del certificado. (heredado de [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)) |
| [certificate_store_name](/signature/python-net/groupdocs.signature.domain/digitalsignature/certificate_store_name/) | El nombre del almacén del certificado. (heredado de [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)) |
| [comments](/signature/python-net/groupdocs.signature.domain/digitalsignature/comments/) | El comentario del propósito de la firma. (heredado de [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)) |
| [created_on](/signature/python-net/groupdocs.signature.domain/basesignature/created_on/) | La fecha de creación de la firma. (heredado de [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [deleted](/signature/python-net/groupdocs.signature.domain/basesignature/deleted/) | El indicador que muestra si esta firma fue eliminada del documento. (heredado de [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [height](/signature/python-net/groupdocs.signature.domain/basesignature/height/) | La altura de la firma. (heredado de [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [is_signature](/signature/python-net/groupdocs.signature.domain/basesignature/is_signature/) | El indicador que muestra si este componente representa una firma (`True`) o contenido del documento (`False`). (heredado de [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [is_valid](/signature/python-net/groupdocs.signature.domain/digitalsignature/is_valid/) | La firma digital es válida y el documento no ha sido manipulado. (heredado de [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)) |
| [left](/signature/python-net/groupdocs.signature.domain/basesignature/left/) | La posición izquierda de la firma. (heredado de [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [modified_on](/signature/python-net/groupdocs.signature.domain/basesignature/modified_on/) | La fecha de modificación de la firma. (heredado de [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [page_number](/signature/python-net/groupdocs.signature.domain/basesignature/page_number/) | El número de página donde se encontró la firma. (heredado de [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [sign_time](/signature/python-net/groupdocs.signature.domain/digitalsignature/sign_time/) | El momento en que se firmó el documento. (heredado de [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)) |
| [signature_id](/signature/python-net/groupdocs.signature.domain/basesignature/signature_id/) | El identificador único de la firma, utilizado para modificar la firma en el documento mediante operaciones de actualización o eliminación. (heredado de [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [signature_type](/signature/python-net/groupdocs.signature.domain/basesignature/signature_type/) | El tipo de firma. (heredado de [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [thumbprint](/signature/python-net/groupdocs.signature.domain/digitalsignature/thumbprint/) | La huella digital de un certificado. (heredado de [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)) |
| [top](/signature/python-net/groupdocs.signature.domain/basesignature/top/) | La posición superior de la firma. (heredado de [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [width](/signature/python-net/groupdocs.signature.domain/basesignature/width/) | El ancho de la firma. (heredado de [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [xad_es_type](/signature/python-net/groupdocs.signature.domain/digitalsignature/xad_es_type/) | El tipo XAdES ([`DigitalSignature.x_ad_es_type`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)). (heredado de [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)) |

### Ver también
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
