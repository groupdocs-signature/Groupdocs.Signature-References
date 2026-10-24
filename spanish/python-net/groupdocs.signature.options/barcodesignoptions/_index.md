---
title: "Clase BarcodeSignOptions"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Representa las opciones de firma de código de barras."
type: docs
url: /es/python-net/groupdocs.signature.options/barcodesignoptions/
is_root: false
weight: 20
---


## BarcodeSignOptions class

Representa las opciones de firma de código de barras.

Aprende más

- Basic usage of creating Barcode electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Barcode+signature
- Advanced usage of settings of Barcode electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Barcode+signature+and+additional+settings

El tipo BarcodeSignOptions expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodesignoptions/__init__/) | Inicializa una nueva instancia de la clase BarcodeSignOptions con valores predeterminados. |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodesignoptions/__init__/#text) | Inicializa una nueva instancia de la clase BarcodeSignOptions con texto. |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodesignoptions/__init__/#text-encode_type) | Inicializa una nueva instancia de la clase BarcodeSignOptions con texto. |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [code_text_alignment](/signature/python-net/groupdocs.signature.options/barcodesignoptions/code_text_alignment/) | La alineación del texto en la imagen de código de barras resultante. El valor predeterminado es None. |
| [encode_type](/signature/python-net/groupdocs.signature.options/barcodesignoptions/encode_type/) | El tipo de código de barras. |
| [fore_color](/signature/python-net/groupdocs.signature.options/barcodesignoptions/fore_color/) | El color de primer plano de las barras del código de barras; usarlo puede causar problemas de verificación, así que úselo con cuidado. |
| [height](/signature/python-net/groupdocs.signature.options/barcodesignoptions/height/) | La altura del área de firma en la página del documento en unidades de medida (píxeles, porcentajes o milímetros). Consulte `MeasureType` para el tipo de medida de tamaño. |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/barcodesignoptions/horizontal_alignment/) | La alineación horizontal de la imagen en una página de documento. |
| [inner_margins](/signature/python-net/groupdocs.signature.options/barcodesignoptions/inner_margins/) | El espacio entre los elementos del código de barras y los bordes de la imagen resultante. |
| [left](/signature/python-net/groupdocs.signature.options/barcodesignoptions/left/) | La posición X izquierda del área de firma en la página del documento, expresada en unidades de medida (píxeles, porcentajes o milímetros). Consulte `MeasureType`. |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/barcodesignoptions/location_measure_type/) | El tipo de medida (píxeles, porcentajes o milímetros) para las propiedades izquierda y superior. |
| [margin](/signature/python-net/groupdocs.signature.options/barcodesignoptions/margin/) | El espacio que se especifica por defecto entre la imagen y los bordes del documento (se aplica cuando la alineación horizontal o vertical está establecida). |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/barcodesignoptions/margin_measure_type/) | El tipo de medida del margen (píxeles, porcentajes o milímetros). |
| [return_content](/signature/python-net/groupdocs.signature.options/barcodesignoptions/return_content/) | La bandera que indica si se debe recuperar el contenido de la imagen del código de barras de una firma colocada en una página del documento. |
| [return_content_type](/signature/python-net/groupdocs.signature.options/barcodesignoptions/return_content_type/) | El tipo de archivo del contenido de imagen devuelto de la firma Barcode cuando la propiedad `return_content` está habilitada. |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/barcodesignoptions/rotation_angle/) | El ángulo de rotación en sentido horario. |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/barcodesignoptions/size_measure_type/) | El tipo de medida (píxeles, porcentajes o milímetros) para las propiedades Width y Height. |
| [stretch](/signature/python-net/groupdocs.signature.options/barcodesignoptions/stretch/) | El modo de estiramiento en la página del documento. |
| [top](/signature/python-net/groupdocs.signature.options/barcodesignoptions/top/) | La posición Y superior del área de firma en la página del documento en unidades de medida (píxeles, porcentajes o milímetros). Consulte `MeasureType` LocationMeasureType. |
| [transparency](/signature/python-net/groupdocs.signature.options/barcodesignoptions/transparency/) | La transparencia de la firma de código de barras, que varía de 0.0 (totalmente opaca) a 1.0 (totalmente transparente); el valor predeterminado es 0. |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/barcodesignoptions/vertical_alignment/) | La alineación vertical de la imagen del código de barras en una página del documento. |
| [width](/signature/python-net/groupdocs.signature.options/barcodesignoptions/width/) | El ancho del área de firma en la página del documento en valores de medida (píxeles, porcentajes o milímetros) según lo definido por `MeasureType`. |
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
from groupdocs.signature.options import BarcodeSignOptions
from groupdocs.signature.domain import (
    Background, BarcodeTypes, Border, CodeTextAlignment,
    HorizontalAlignment, Padding, VerticalAlignment)
from groupdocs.pydrawing import Color

def sign_with_barcode():
    with Signature("sample.pdf") as signature:
        options = BarcodeSignOptions("JohnSmith", BarcodeTypes.CODE128)
        options.width = 220
        options.height = 80
        options.horizontal_alignment = HorizontalAlignment.RIGHT
        options.vertical_alignment = VerticalAlignment.BOTTOM
        options.margin = Padding(right=40, bottom=60)
        options.fore_color = Color.dark_blue
        options.code_text_alignment = CodeTextAlignment.BELOW
        options.inner_margins = Padding(5)

        background = Background()
        background.color = Color.light_yellow
        options.background = background

        border = Border()
        options.border = border

        signature.sign("signed.pdf", options)
```

### Guides
Guías de tareas que usan `BarcodeSignOptions`:

* [eSign Document with Barcode Signature](/signature/python-net/guides/esign-document-with-barcode-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)
* [Generate signatures preview](/signature/python-net/guides/generate-signatures-preview/)

### Ver también
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
