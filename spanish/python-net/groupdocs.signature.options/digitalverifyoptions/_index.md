---
title: "Clase DigitalVerifyOptions"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Mantiene opciones para verificar la firma digital de un documento."
type: docs
url: /es/python-net/groupdocs.signature.options/digitalverifyoptions/
is_root: false
weight: 150
---


## DigitalVerifyOptions class

Mantiene opciones para verificar la firma digital de un documento.

Aprende más

- Basic usage of verification for Digital electronic signature by GroupDocs.Signature: [How to eVerification Digital signatures in a document](https://docs.groupdocs.com/display/signaturenet/Verify+Digital+signatures+in+the+document)
- Advanced usage of settings of verification for Digital electronic signature with GroupDocs.Signature: Advanced usage of eVerification Digital signatures in a document and additional settings

El tipo DigitalVerifyOptions expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/__init__/) | Inicializa una instancia de DigitalVerifyOptions con valores predeterminados. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/__init__/#certificate_file_path) | Inicializa una instancia de DigitalVerifyOptions con la ruta de archivo del certificado digital proporcionada. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/__init__/#certificate_stream) | Inicializa una instancia de DigitalVerifyOptions con el flujo del certificado proporcionado. |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [certificate](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/certificate/) | El certificado X509Certificate2 obtenido de la ruta del archivo del certificado o del flujo. |
| [certificate_file_path](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/certificate_file_path/) | La ruta del archivo del certificado digital. |
| [certificate_stream](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/certificate_stream/) | El flujo del certificado digital. |
| [comments](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/comments/) | Los comentarios de la firma digital a validar. |
| [contact](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/contact/) | El contacto de la firma a validar. |
| [issuer_name](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/issuer_name/) | El nombre del emisor del certificado a validar. |
| [location](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/location/) | La ubicación de la firma a validar. |
| [password](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/password/) | La contraseña del certificado digital si se requiere. |
| [reason](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/reason/) | La razón de la firma digital a validar. |
| [sign_date_time_from](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/sign_date_time_from/) | El inicio del rango de fecha y hora de la firma digital a validar. Un valor None será ignorado. |
| [sign_date_time_to](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/sign_date_time_to/) | El final del rango de fecha y hora de la firma digital a validar. Un valor null será ignorado. |
| [subject_name](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/subject_name/) | El nombre distinguido del sujeto del certificado a validar; la verificación comprueba si el nombre del sujeto de la firma contiene o es igual a este valor sensible a mayúsculas. |
| [all_pages](/signature/python-net/groupdocs.signature.options/verifyoptions/all_pages/) | La bandera que indica si cada página del documento debe ser verificada. Por defecto el valor es True. (heredado de [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/verifyoptions/extensions/) | Las extensiones adicionales para la verificación de opciones de firma alternativas. (heredado de [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [is_valid](/signature/python-net/groupdocs.signature.options/verifyoptions/is_valid/) | La bandera de propiedad válida. (heredado de [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/verifyoptions/page_number/) | El número de página del documento a verificar; si no se establece, se verifican todas las páginas del documento para la primera aparición (el valor mínimo es 1). (heredado de [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/verifyoptions/pages_setup/) | Las opciones de página para especificar las páginas a verificar. (heredado de [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/verifyoptions/shape_position/) | La posición de la forma en el diseño del documento utilizada para verificar firmas en encabezados/pies de página. (heredado de [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |

### Ver también
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
