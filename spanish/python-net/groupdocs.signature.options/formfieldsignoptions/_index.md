---
title: "Clase FormFieldSignOptions"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Representa las opciones de firma FormField para documentos PDF."
type: docs
url: /es/python-net/groupdocs.signature.options/formfieldsignoptions/
is_root: false
weight: 180
---


## FormFieldSignOptions class

Representa las opciones de firma FormField para documentos PDF.

Proporciona opciones para crear o actualizar firmas de campos de formulario en archivos PDF.

- Basic usage of creating FormField electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Form+Field+signature
- Advanced usage of settings of FormField electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Form+Field+signature+-+advanced

El tipo FormFieldSignOptions expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/__init__/) | Inicializa una nueva instancia de la clase PdfFormFieldSignOptions con valores predeterminados. |
| [__init__](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/__init__/#signature) | Inicializa una nueva instancia de la clase PdfFormFieldSignOptions con una firma FormField. |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [height](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/height/) | La altura del área de firma en la página del documento en unidades de medida (píxeles, porcentajes o milímetros; ver `MeasureType` SizeMeasureType). |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/horizontal_alignment/) | La alineación horizontal de la imagen en una página de documento. |
| [left](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/left/) | La posición X izquierda del área de firma en la página del documento en unidades de medida (píxeles, porcentajes o milímetros). |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/location_measure_type/) | El tipo de medida (píxeles, porcentajes o milímetros) para las propiedades Left y Top. |
| [margin](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/margin/) | El espacio predeterminado entre la imagen y los bordes del documento (se aplica cuando se establece la alineación horizontal o vertical). |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/margin_measure_type/) | El tipo de medida del margen (píxeles, porcentajes o milímetros). |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/rotation_angle/) | El ángulo de rotación, medido en sentido horario. |
| [signature](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/signature/) | El FormField de la firma. |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/size_measure_type/) | El tipo de medida (píxeles, porcentajes o milímetros) para las propiedades Width y Height. |
| [stretch](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/stretch/) | El modo de estiramiento en la página del documento. |
| [top](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/top/) | La posición Y superior del área de firma en la página del documento en unidades de medida (píxeles, porcentajes o milímetros). Consulte `MeasureType` para el tipo de medida de ubicación. |
| [transparency](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/transparency/) | La transparencia de la firma del campo de formulario. El valor varía de 0.0 a 1.0, con un valor predeterminado de 0. |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/vertical_alignment/) | La alineación vertical de la imagen en una página de documento. |
| [width](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/width/) | El ancho del área de firma en la página del documento en valores de medida (píxeles, porcentajes o milímetros; ver `MeasureType` SizeMeasureType). |
| [all_pages](/signature/python-net/groupdocs.signature.options/signoptions/all_pages/) | La firma se colocará en todas las páginas del documento. (heredado de [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [appearance](/signature/python-net/groupdocs.signature.options/signoptions/appearance/) | La apariencia adicional de la firma. (heredado de [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [background](/signature/python-net/groupdocs.signature.options/textsignoptions/background/) | La configuración del fondo de la firma. (heredado de [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [border](/signature/python-net/groupdocs.signature.options/textsignoptions/border/) | La configuración del borde. (heredado de [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [document_type](/signature/python-net/groupdocs.signature.options/signoptions/document_type/) | El tipo de documento de las opciones de firma (`DocumentType`). (heredado de [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/signoptions/extensions/) | Las extensiones de la firma. (heredado de [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [font](/signature/python-net/groupdocs.signature.options/textsignoptions/font/) | La fuente de la firma. (heredado de [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [fore_color](/signature/python-net/groupdocs.signature.options/textsignoptions/fore_color/) | El color de primer plano de la firma. (heredado de [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
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
from groupdocs.signature.options import FormFieldSignOptions
from groupdocs.signature.domain import TextFormFieldSignature

def sign_with_form_field_signature():
    with Signature("sample.pdf") as signature:
        text_field = TextFormFieldSignature("FieldText", "Value1")
        options = FormFieldSignOptions(text_field)
        options.left = 100
        options.top = 400
        options.width = 200
        options.height = 20

        result = signature.sign("signed_form_field.pdf", options)
        for field in result.succeeded:
            print(f"Added form field '{field.name}' with value '{field.value}'")
```

### Ver también
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
