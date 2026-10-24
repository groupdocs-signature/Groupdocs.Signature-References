---
title: "Clase CertificateVerifyOptions"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Mantiene opciones para verificar documentos de certificado."
type: docs
url: /es/python-net/groupdocs.signature.options/certificateverifyoptions/
is_root: false
weight: 70
---


## CertificateVerifyOptions class

Mantiene opciones para verificar documentos de certificado.

Aprende más

- Basic usage of certificate documents by GroupDocs.Signature: Preview Digital Certificates properties (https://docs.groupdocs.com/signature/net/preview-certificate-properties/)

El tipo CertificateVerifyOptions expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/__init__/) | Inicializa una nueva instancia de TextVerifyOptions con valores predeterminados. |
| [__init__](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/__init__/#subject) | Inicializa una nueva instancia de CertificateVerifyOptions con el sujeto a verificar. |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [expired](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/expired/) | La propiedad indica si el certificado está expirado según el resultado de la validación. |
| [issuer](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/issuer/) | El emisor del certificado a verificar. |
| [match_type](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/match_type/) | El tipo de coincidencia de texto usado para la verificación. |
| [perform_chain_validation](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/perform_chain_validation/) | El proceso de verificación debe proporcionar validación de cadena X.509 usando la política de validación básica. |
| [serial_number](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/serial_number/) | El número de serie del certificado a verificar. |
| [subject](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/subject/) | El sujeto del certificado a verificar. |
| [thumbprint](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/thumbprint/) | La huella digital del certificado a verificar. |
| [all_pages](/signature/python-net/groupdocs.signature.options/verifyoptions/all_pages/) | La bandera que indica si cada página del documento debe ser verificada. Por defecto el valor es True. (heredado de [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/verifyoptions/extensions/) | Las extensiones adicionales para la verificación de opciones de firma alternativas. (heredado de [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [is_valid](/signature/python-net/groupdocs.signature.options/verifyoptions/is_valid/) | La bandera de propiedad válida. (heredado de [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/verifyoptions/page_number/) | El número de página del documento a verificar; si no se establece, se verifican todas las páginas del documento para la primera aparición (el valor mínimo es 1). (heredado de [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/verifyoptions/pages_setup/) | Las opciones de página para especificar las páginas a verificar. (heredado de [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/verifyoptions/shape_position/) | La posición de la forma en el diseño del documento utilizada para verificar firmas en encabezados/pies de página. (heredado de [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |

### Ver también
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
