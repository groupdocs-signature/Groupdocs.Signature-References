---
title: "Clase DigitalSignOptions"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Representa las opciones de firma digital."
type: docs
url: /es/python-net/groupdocs.signature.options/digitalsignoptions/
is_root: false
weight: 140
---


## DigitalSignOptions class

Representa las opciones de firma digital.

Aprende más

- Basic usage of creating Digital electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Digital+signature
- Advanced usage of settings of Digital electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Digital+signature+-+advanced

El tipo DigitalSignOptions expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/) | Inicializa una nueva instancia de la clase DigitalSignOptions con valores predeterminados. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/#certificate_file_path) | Inicializa una nueva instancia de DigitalSignOptions con un archivo de certificado. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/#certificate_stream) | Inicializa una nueva instancia de DigitalSignOptions con un flujo de certificado. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/#certificate_file_path-image_file_path) | Inicializa una nueva instancia de la clase DigitalSignOptions con un archivo de certificado y un archivo de imagen de apariencia. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/#certificate_file_path-appearence_image_stream) | Inicializa una nueva instancia de DigitalSignOptions con un archivo de certificado y un flujo de imagen de apariencia. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/#certificate_stream-image_file_path) | Inicializa una nueva instancia de DigitalSignOptions con un flujo de certificado y un archivo de imagen de apariencia. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/#certificate_stream-appearence_image_stream) | Inicializa una nueva instancia de DigitalSignOptions con un flujo de certificado y un flujo de imagen de apariencia. |

### Métodos
| Método | Descripción |
| :- | :- |
| [dispose](/signature/python-net/groupdocs.signature.options/imagesignoptions/dispose/) | Limpia los recursos internos. (heredado de [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |
| [from_base64](/signature/python-net/groupdocs.signature.options/imagesignoptions/from_base64/) | Crea una nueva instancia de ImageSignOptions con una imagen predefinida a partir de una cadena Base64. (heredado de [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [allow_expired](/signature/python-net/groupdocs.signature.options/digitalsignoptions/allow_expired/) | La bandera que permite firmar con un certificado cuyo período de validez ha finalizado. El valor predeterminado es False; firmar con un certificado expirado genera `GroupDocsSignatureException` y el documento no se firma. |
| [allow_not_yet_valid](/signature/python-net/groupdocs.signature.options/digitalsignoptions/allow_not_yet_valid/) | La bandera que permite firmar con un certificado cuyo período de validez aún no ha comenzado. El valor predeterminado es False; firmar con dicho certificado genera `GroupDocsSignatureException` y el documento no se firma. |
| [certificate_file_path](/signature/python-net/groupdocs.signature.options/digitalsignoptions/certificate_file_path/) | La ruta del archivo del certificado digital. |
| [certificate_stream](/signature/python-net/groupdocs.signature.options/digitalsignoptions/certificate_stream/) | El flujo del certificado digital. Si esta propiedad está especificada, siempre se usa en lugar de CertificateFilePath. |
| [contact](/signature/python-net/groupdocs.signature.options/digitalsignoptions/contact/) | El contacto de la firma. |
| [custom_sign_hash](/signature/python-net/groupdocs.signature.options/digitalsignoptions/custom_sign_hash/) | La función personalizada de hash para firmar utilizada para firmar el documento, que permite a los usuarios implementar su propia lógica de firma digital. |
| [height](/signature/python-net/groupdocs.signature.options/digitalsignoptions/height/) | La altura del área de firma en la página del documento en unidades de medida (píxeles, porcentajes o milímetros; ver `MeasureType`). |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/digitalsignoptions/horizontal_alignment/) | La alineación horizontal de la imagen en una página de documento. |
| [left](/signature/python-net/groupdocs.signature.options/digitalsignoptions/left/) | La posición X izquierda del área de firma en la página del documento en unidades de medida (píxeles, porcentajes o milímetros según lo definido por `MeasureType.location_measure_type`). |
| [location](/signature/python-net/groupdocs.signature.options/digitalsignoptions/location/) | La ubicación de la firma. |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/digitalsignoptions/location_measure_type/) | El tipo de medida (píxeles, porcentajes o milímetros) para las propiedades left y top. |
| [margin](/signature/python-net/groupdocs.signature.options/digitalsignoptions/margin/) | El espacio que se especifica por defecto entre la imagen y los bordes del documento (se aplica cuando se especifica la alineación horizontal o vertical). |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/digitalsignoptions/margin_measure_type/) | El tipo de medida del margen (píxeles, porcentajes o milímetros). |
| [password](/signature/python-net/groupdocs.signature.options/digitalsignoptions/password/) | La contraseña del certificado digital. |
| [reason](/signature/python-net/groupdocs.signature.options/digitalsignoptions/reason/) | La razón de la firma. |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/digitalsignoptions/rotation_angle/) | El ángulo de rotación en sentido horario. |
| [signature](/signature/python-net/groupdocs.signature.options/digitalsignoptions/signature/) | Las propiedades de la firma digital para el documento. Para la firma PDF, se pueden establecer propiedades avanzadas usando una instancia de [`PdfDigitalSignature`](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/). |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/digitalsignoptions/size_measure_type/) | El tipo de medida (píxeles, porcentajes o milímetros) para las propiedades Width y Height. |
| [stretch](/signature/python-net/groupdocs.signature.options/digitalsignoptions/stretch/) | El modo de estiramiento en la página del documento. |
| [top](/signature/python-net/groupdocs.signature.options/digitalsignoptions/top/) | La posición Y superior del área de firma en la página del documento en unidades de medida (píxeles, porcentajes o milímetros; ver `MeasureType` `LocationMeasureType`). |
| [transparency](/signature/python-net/groupdocs.signature.options/digitalsignoptions/transparency/) | La transparencia de la firma digital, que varía de 0.0 a 1.0. El valor predeterminado es 0. |
| [use_ltv](/signature/python-net/groupdocs.signature.options/digitalsignoptions/use_ltv/) | La bandera de validación LTV (Validación a Largo Plazo). |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/digitalsignoptions/vertical_alignment/) | La alineación vertical de la imagen en una página de documento. |
| [visible](/signature/python-net/groupdocs.signature.options/digitalsignoptions/visible/) | La visibilidad de la firma. |
| [width](/signature/python-net/groupdocs.signature.options/digitalsignoptions/width/) | El ancho del área de firma en la página del documento en valores de medida (píxeles, porcentajes o milímetros). La unidad de medida se define mediante `MeasureType` a través de la propiedad SizeMeasureType. |
| [xad_es_type](/signature/python-net/groupdocs.signature.options/digitalsignoptions/xad_es_type/) | El tipo XAdES. El valor predeterminado es None (XAdES está desactivado). |
| [all_pages](/signature/python-net/groupdocs.signature.options/signoptions/all_pages/) | La firma se colocará en todas las páginas del documento. (heredado de [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [appearance](/signature/python-net/groupdocs.signature.options/signoptions/appearance/) | La apariencia adicional de la firma. (heredado de [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [border](/signature/python-net/groupdocs.signature.options/imagesignoptions/border/) | La configuración de borde para la firma de imagen. (heredada de [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |
| [document_type](/signature/python-net/groupdocs.signature.options/signoptions/document_type/) | El tipo de documento de las opciones de firma (`DocumentType`). (heredado de [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/signoptions/extensions/) | Las extensiones de la firma. (heredado de [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [hash_algorithm](/signature/python-net/groupdocs.signature.options/signoptions/hash_algorithm/) | El algoritmo hash a usar para operaciones criptográficas. Soportado exclusivamente para firmas digitales en archivos PDF. (heredado de [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [image_file_path](/signature/python-net/groupdocs.signature.options/imagesignoptions/image_file_path/) | La ruta del archivo de la imagen de la firma, utilizada solo si `image_stream` no está especificado. (heredada de [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |
| [image_stream](/signature/python-net/groupdocs.signature.options/imagesignoptions/image_stream/) | El flujo de la imagen de la firma. Si se especifica, siempre se usa en lugar de ImageFilePath. (heredada de [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/signoptions/page_number/) | El número de página del documento para firmar. (heredado de [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/signoptions/pages_setup/) | Las opciones para especificar las páginas a firmar. (heredado de [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [rectangle](/signature/python-net/groupdocs.signature.options/imagesignoptions/rectangle/) | El rectángulo del área donde colocar la imagen en el documento. (heredada de [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/imagesignoptions/shape_position/) | La posición de la forma define dónde debe presentarse la forma en el diseño del documento. Disponible solo para documentos Word. (heredada de [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |
| [signature_type](/signature/python-net/groupdocs.signature.options/signoptions/signature_type/) | El tipo de firma (`SignatureType`). (heredado de [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [zorder](/signature/python-net/groupdocs.signature.options/signoptions/zorder/) | La posición Z-order de la firma de texto, que determina el orden de visualización de firmas superpuestas. (heredado de [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |

### Ejemplo

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalSignOptions

def sign_with_digital_signature_advanced():
    with Signature("sample.pdf") as signature:
        # Pase el certificado y la imagen de apariencia al constructor
        options = DigitalSignOptions("certificate.pfx", "signature.jpg")
        options.password = "1234567890"

        # Muestre la firma en la página, en esta posición y tamaño
        options.visible = True
        options.left = 100
        options.top = 400
        options.width = 200
        options.height = 100

        # Información almacenada en la firma
        options.contact = "John Smith"
        options.reason = "Approval"
        options.location = "New York"

        result = signature.sign("signed_digital_advanced.pdf", options)
        print(f"Signed with {len(result.succeeded)} digital signature(s)")

if __name__ == "__main__":
    sign_with_digital_signature_advanced()
```

### Guides
Guías de tareas que usan `DigitalSignOptions`:

* [Sign Document with Digital Signature](/signature/python-net/guides/esign-document-with-digital-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)

### Ver también
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
