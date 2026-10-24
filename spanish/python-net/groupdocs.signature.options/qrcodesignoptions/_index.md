---
title: "Clase QrCodeSignOptions"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Representa las opciones de firma de código QR."
type: docs
url: /es/python-net/groupdocs.signature.options/qrcodesignoptions/
is_root: false
weight: 480
---


## QrCodeSignOptions class

Representa las opciones de firma de código QR.

- Basic usage of creating QR-Code electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/eSign+document+with+QR-code+signature
- Advanced usage of settings of QR-Code electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Sign+document+with+QR-code+signature+-+advanced

El tipo QrCodeSignOptions expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/__init__/) | Inicializa una nueva instancia de la clase QRCodeSignOptions con valores predeterminados. |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/__init__/#text) | Inicializa una instancia de QrCodeSignOptions con el texto especificado. |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/__init__/#text-encode_type) | Inicializa una nueva instancia de la clase QrCodeSignOptions con texto. |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [code_text_alignment](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/code_text_alignment/) | La alineación del texto en la imagen QR-code resultante, el valor predeterminado es None. |
| [data](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/data/) | El objeto personalizado para serializar al contenido QR-Code. |
| [data_encryption](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/data_encryption/) | La implementación de cifrado de datos usada para codificar y decodificar el texto o los datos de la firma de código QR. |
| [encode_type](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/encode_type/) | El tipo de QR-Code. |
| [fore_color](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/fore_color/) | El color de primer plano de las barras del código QR; usar esta propiedad podría causar problemas de verificación, así que úsela con cuidado. |
| [height](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/height/) | La altura del área de firma en la página del documento en unidades de medida (píxeles, porcentajes o milímetros; ver `MeasureType` SizeMeasureType). |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/horizontal_alignment/) | La alineación horizontal del código QR en una página del documento. |
| [inner_margins](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/inner_margins/) | El espacio entre los elementos del código QR y los bordes de la imagen resultante. |
| [left](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/left/) | La posición X izquierda del área de firma en una página del documento en unidades de medida (píxeles, porcentajes o milímetros). |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/location_measure_type/) | El tipo de medida (píxeles, porcentajes o milímetros) para las propiedades izquierda y superior. |
| [logo_file_path](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/logo_file_path/) | El nombre de archivo de la imagen del logotipo del QR-code. |
| [logo_stream](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/logo_stream/) | El flujo de imagen del logotipo del QR-code. |
| [margin](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/margin/) | El espacio que se especifica por defecto entre los bordes de la Imagen y el Documento (funciona si se especifica la alineación horizontal o vertical). |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/margin_measure_type/) | El tipo de medida del margen (píxeles, porcentajes o milímetros). |
| [return_content](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/return_content/) | La bandera para recuperar el contenido de imagen QR-Code de una firma colocada en una página del documento. |
| [return_content_type](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/return_content_type/) | El tipo de archivo del contenido de imagen devuelto de la firma QR‑Code cuando la propiedad `return_content` está habilitada. |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/rotation_angle/) | El ángulo de rotación en grados, en sentido horario. |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/size_measure_type/) | El tipo de medida (píxeles, porcentajes o milímetros) para las propiedades Width y Height. |
| [stretch](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/stretch/) | El modo de estiramiento en la página del documento. |
| [top](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/top/) | La posición Y superior del área de firma en una página del documento en unidades de medida (píxeles, porcentajes o milímetros). La unidad está definida por la propiedad `LocationMeasureType` de tipo `MeasureType`. |
| [transparency](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/transparency/) | La transparencia de la firma del código QR. El valor varía de 0.0 a 1.0, con un valor predeterminado de 0. |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/vertical_alignment/) | La alineación vertical de la imagen en una página de documento. |
| [width](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/width/) | El ancho del área de firma en la página del documento en valores de medida (píxeles, porcentaje o milímetros según lo definido por `MeasureType`). |
| [all_pages](/signature/python-net/groupdocs.signature.options/signoptions/all_pages/) | La firma se colocará en todas las páginas del documento. (heredado de [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [appearance](/signature/python-net/groupdocs.signature.options/signoptions/appearance/) | La apariencia adicional de la firma. (heredado de [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [background](/signature/python-net/groupdocs.signature.options/textsignoptions/background/) | La configuración del fondo de la firma. (heredado de [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [border](/signature/python-net/groupdocs.signature.options/textsignoptions/border/) | La configuración del borde. (heredado de [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [document_type](/signature/python-net/groupdocs.signature.options/signoptions/document_type/) | El tipo de documento de las opciones de firma (`DocumentType`). (heredado de [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/signoptions/extensions/) | Las extensiones de la firma. (heredado de [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [font](/signature/python-net/groupdocs.signature.options/textsignoptions/font/) | La fuente de la firma. (heredado de [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [form_text_field_title](/signature/python-net/groupdocs.signature.options/textsignoptions/form_text_field_title/) | El título del campo de formulario de texto donde colocar la firma de texto. Solo se puede usar cuando `signature_implementation` está configurado a `TextSignatureImplementation.FORM_FIELD`. (heredado de [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [form_text_field_type](/signature/python-net/groupdocs.signature.options/textsignoptions/form_text_field_type/) | El tipo de campo de formulario donde colocar la firma de texto. Esta propiedad se aplica solo cuando `signature_implementation` está configurado a `TextSignatureImplementation.FORM_FIELD` (es decir, TextToFormField). El valor predeterminado es `FormTextFieldType.ALL_TEXT_TYPES`. (heredado de [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [hash_algorithm](/signature/python-net/groupdocs.signature.options/signoptions/hash_algorithm/) | El algoritmo hash a usar para operaciones criptográficas. Soportado exclusivamente para firmas digitales en archivos PDF. (heredado de [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [native](/signature/python-net/groupdocs.signature.options/textsignoptions/native/) | El atributo nativo. (heredado de [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/signoptions/page_number/) | El número de página del documento para firmar. (heredado de [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/signoptions/pages_setup/) | Las opciones para especificar las páginas a firmar. (heredado de [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/textsignoptions/shape_position/) | La posición de la forma define dónde debe presentarse la forma en el diseño del documento. Disponible solo para documentos Word. (heredado de [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [shape_type](/signature/python-net/groupdocs.signature.options/textsignoptions/shape_type/) | El tipo de forma para colocar texto. (heredado de [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [signature_id](/signature/python-net/groupdocs.signature.options/textsignoptions/signature_id/) | El ID único de la firma, utilizable en opciones de verificación y compatible solo con documentos PDF. (heredado de [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [signature_implementation](/signature/python-net/groupdocs.signature.options/textsignoptions/signature_implementation/) | El tipo de implementación de firma de texto. (heredado de [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [signature_type](/signature/python-net/groupdocs.signature.options/signoptions/signature_type/) | El tipo de firma (`SignatureType`). (heredado de [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [text](/signature/python-net/groupdocs.signature.options/textsignoptions/text/) | El texto de la firma. (heredado de [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [text_horizontal_alignment](/signature/python-net/groupdocs.signature.options/textsignoptions/text_horizontal_alignment/) | La alineación horizontal del texto dentro de una firma, compatible solo con implementaciones de firma de Imagen y Anotación (ver la propiedad `TextSignatureImplementation` SignatureImplementation). (heredado de [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [text_vertical_alignment](/signature/python-net/groupdocs.signature.options/textsignoptions/text_vertical_alignment/) | La alineación vertical del texto dentro de una firma. (heredado de [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [zorder](/signature/python-net/groupdocs.signature.options/signoptions/zorder/) | La posición Z-order de la firma de texto, que determina el orden de visualización de firmas superpuestas. (heredado de [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |

### Ejemplo

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import QrCodeSignOptions
from groupdocs.signature.domain import (
    Background, Border, DashStyle, HorizontalAlignment, Padding,
    QrCodeTypes, VerticalAlignment)
from groupdocs.pydrawing import Color

def sign_with_qr_code_signature_advanced():
    with Signature("sample.pdf") as signature:
        # Pase el texto y el tipo de código QR al constructor
        options = QrCodeSignOptions("https://www.example.com/verify-document", QrCodeTypes.QR)

        # Coloque el código QR en la esquina inferior derecha de la página
        options.width = 120
        options.height = 120
        options.horizontal_alignment = HorizontalAlignment.RIGHT
        options.vertical_alignment = VerticalAlignment.BOTTOM
        options.margin = Padding(right=40, bottom=60)

        # Color del módulo, fondo y un borde punteado con algo de espacio interior
        options.fore_color = Color.dark_blue
        background = Background()
        background.color = Color.light_yellow
        options.background = background
        border = Border()
        border.color = Color.dark_blue
        border.dash_style = DashStyle.DOT
        border.weight = 2
        border.visible = True

        signature.sign("signed.pdf", options)
```

### Guides
Guías de tareas que usan `QrCodeSignOptions`:

* [eSign Document with QR Code Signature](/signature/python-net/guides/esign-document-with-qr-code-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)
* [Generate signatures preview](/signature/python-net/guides/generate-signatures-preview/)

### Ver también
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
