---
title: "Clase TextSignOptions"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Representa las opciones de firma de Texto."
type: docs
url: /es/python-net/groupdocs.signature.options/textsignoptions/
is_root: false
weight: 590
---


## TextSignOptions class

Representa las opciones de firma de Texto.

Aprende más

- Basic usage of creating Text electronic signature by GroupDocs.Signature: [How to eSign document with Text signature](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Text+signature)
- Advanced usage of settings of Text electronic signature with GroupDocs.Signature: [Advanced usage to eSign document with Text signature and additional settings](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Text+signature+-+advanced)

El tipo TextSignOptions expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/textsignoptions/__init__/) | Inicializa una nueva instancia de la clase TextSignOptions con valores predeterminados. |
| [__init__](/signature/python-net/groupdocs.signature.options/textsignoptions/__init__/#text) | Inicializa una nueva instancia de la clase TextSignOptions con texto. |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [background](/signature/python-net/groupdocs.signature.options/textsignoptions/background/) | La configuración de fondo de la firma. |
| [border](/signature/python-net/groupdocs.signature.options/textsignoptions/border/) | La configuración del borde. |
| [font](/signature/python-net/groupdocs.signature.options/textsignoptions/font/) | La fuente de la firma. |
| [fore_color](/signature/python-net/groupdocs.signature.options/textsignoptions/fore_color/) | El color de primer plano de la firma. |
| [form_text_field_title](/signature/python-net/groupdocs.signature.options/textsignoptions/form_text_field_title/) | El título del campo de formulario de texto donde colocar la firma de texto. Solo se puede usar cuando `signature_implementation` está configurado a `TextSignatureImplementation.FORM_FIELD`. |
| [form_text_field_type](/signature/python-net/groupdocs.signature.options/textsignoptions/form_text_field_type/) | El tipo de campo de formulario en el que colocar la firma de texto. Esta propiedad es aplicable solo cuando `signature_implementation` está configurado a `TextSignatureImplementation.FORM_FIELD` (es decir, TextToFormField). El valor predeterminado es `FormTextFieldType.ALL_TEXT_TYPES`. |
| [height](/signature/python-net/groupdocs.signature.options/textsignoptions/height/) | La altura de la firma en la página del documento en valores de medida (píxeles, porcentajes o milímetros). La unidad se determina mediante la propiedad `SizeMeasureType`. |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/textsignoptions/horizontal_alignment/) | La alineación horizontal de la firma en la página del documento. |
| [left](/signature/python-net/groupdocs.signature.options/textsignoptions/left/) | La posición X izquierda de la firma en la página del documento en valores de medida (píxeles, porcentajes o milímetros según lo definido por la propiedad `MeasureType` LocationMeasureType). Funciona si no se especifica la alineación horizontal. |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/textsignoptions/location_measure_type/) | El tipo de medida (píxeles, porcentajes o milímetros) para las propiedades `left` y `top`. |
| [margin](/signature/python-net/groupdocs.signature.options/textsignoptions/margin/) | El espacio entre la firma y los bordes del documento. Se aplica solo cuando se especifica la alineación horizontal o vertical. |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/textsignoptions/margin_measure_type/) | El tipo de medida (píxeles, porcentajes o milímetros) para el margen. |
| [native](/signature/python-net/groupdocs.signature.options/textsignoptions/native/) | El atributo nativo. |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/textsignoptions/rotation_angle/) | El ángulo de rotación de la firma en la página del documento (en sentido horario). |
| [shape_position](/signature/python-net/groupdocs.signature.options/textsignoptions/shape_position/) | La posición de la forma define dónde debe presentarse la forma en el diseño del documento. Disponible solo para documentos Word. |
| [shape_type](/signature/python-net/groupdocs.signature.options/textsignoptions/shape_type/) | El tipo de forma para colocar texto. |
| [signature_id](/signature/python-net/groupdocs.signature.options/textsignoptions/signature_id/) | El ID único de la firma, utilizable en opciones de verificación y compatible solo con documentos PDF. |
| [signature_implementation](/signature/python-net/groupdocs.signature.options/textsignoptions/signature_implementation/) | El tipo de implementación de firma de texto. |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/textsignoptions/size_measure_type/) | El tipo de medida (píxeles, porcentajes o milímetros) para las propiedades Width y Height. |
| [stretch](/signature/python-net/groupdocs.signature.options/textsignoptions/stretch/) | El modo de estiramiento en la página del documento. |
| [text](/signature/python-net/groupdocs.signature.options/textsignoptions/text/) | El texto de la firma. |
| [text_horizontal_alignment](/signature/python-net/groupdocs.signature.options/textsignoptions/text_horizontal_alignment/) | La alineación horizontal del texto dentro de una firma, compatible solo con implementaciones de firma de Imagen y Anotación (ver la propiedad `TextSignatureImplementation` SignatureImplementation). |
| [text_vertical_alignment](/signature/python-net/groupdocs.signature.options/textsignoptions/text_vertical_alignment/) | La alineación vertical del texto dentro de una firma. |
| [top](/signature/python-net/groupdocs.signature.options/textsignoptions/top/) | La posición Y superior de la firma en la página del documento, expresada en unidades de medida (píxeles, porcentaje o milímetros). |
| [transparency](/signature/python-net/groupdocs.signature.options/textsignoptions/transparency/) | La transparencia de la firma, un número flotante entre 0.0 (opaco) y 1.0 (transparente). El valor predeterminado es 0.0 (opaco). |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/textsignoptions/vertical_alignment/) | La alineación vertical de la firma en la página del documento. |
| [width](/signature/python-net/groupdocs.signature.options/textsignoptions/width/) | El ancho de la firma en la página del documento en valores de medida (píxeles, porcentajes o milímetros; ver la propiedad `MeasureType` `SizeMeasureType`). |
| [all_pages](/signature/python-net/groupdocs.signature.options/signoptions/all_pages/) | La firma se colocará en todas las páginas del documento. (heredado de [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [appearance](/signature/python-net/groupdocs.signature.options/signoptions/appearance/) | La apariencia adicional de la firma. (heredado de [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [document_type](/signature/python-net/groupdocs.signature.options/signoptions/document_type/) | El tipo de documento de las opciones de firma (`DocumentType`). (heredado de [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/signoptions/extensions/) | Las extensiones de la firma. (heredado de [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [hash_algorithm](/signature/python-net/groupdocs.signature.options/signoptions/hash_algorithm/) | El algoritmo hash a usar para operaciones criptográficas. Soportado exclusivamente para firmas digitales en archivos PDF. (heredado de [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/signoptions/page_number/) | El número de página del documento para firmar. (heredado de [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/signoptions/pages_setup/) | Las opciones para especificar las páginas a firmar. (heredado de [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [signature_type](/signature/python-net/groupdocs.signature.options/signoptions/signature_type/) | El tipo de firma (`SignatureType`). (heredado de [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [zorder](/signature/python-net/groupdocs.signature.options/signoptions/zorder/) | La posición Z-order de la firma de texto, que determina el orden de visualización de firmas superpuestas. (heredado de [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |

### Ejemplo

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

def sign_pdf_with_text_signature():
    with Signature("sample.pdf") as signature:
        options = TextSignOptions("John Smith")
        options.left = 100
        options.top = 100
        result = signature.sign("signed_sample.pdf", options)
        print(f"Signatures added: {len(result.succeeded)}")
```

### Guides
Guías de tareas que utilizan `TextSignOptions`:

* [Quick Start Guide](/signature/python-net/guides/quick-start-guide/)
* [eSign Document with Text Signature](/signature/python-net/guides/esign-document-with-text-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)
* [Generate signatures preview](/signature/python-net/guides/generate-signatures-preview/)

### Ver también
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
