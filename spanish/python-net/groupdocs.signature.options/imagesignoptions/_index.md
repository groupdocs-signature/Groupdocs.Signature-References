---
title: "ImageSignOptions clase"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Representa las opciones de firma de Imagen."
type: docs
url: /es/python-net/groupdocs.signature.options/imagesignoptions/
is_root: false
weight: 250
---


## ImageSignOptions class

Representa las opciones de firma de Imagen.

Más información:
- Basic usage of creating Image electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Image+signature
- Advanced usage of settings of Image electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Image+signature+-+advanced

El tipo ImageSignOptions expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/imagesignoptions/__init__/) | Inicializa una nueva instancia de la clase ImageSignOptions con valores predeterminados. |
| [__init__](/signature/python-net/groupdocs.signature.options/imagesignoptions/__init__/#image_file_path) | Inicializa ImageSignOptions con un archivo de imagen. |
| [__init__](/signature/python-net/groupdocs.signature.options/imagesignoptions/__init__/#image_stream) | Inicializa una nueva instancia de ImageSignOptions con un flujo de imagen. |

### Métodos
| Método | Descripción |
| :- | :- |
| [dispose](/signature/python-net/groupdocs.signature.options/imagesignoptions/dispose/) | Limpia los recursos internos. |
| [from_base64](/signature/python-net/groupdocs.signature.options/imagesignoptions/from_base64/#base_64_content) | Crea una nueva instancia de ImageSignOptions con una imagen predefinida a partir de una cadena Base64. |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [border](/signature/python-net/groupdocs.signature.options/imagesignoptions/border/) | La configuración del borde para la firma de imagen. |
| [height](/signature/python-net/groupdocs.signature.options/imagesignoptions/height/) | La altura de la firma en la página del documento en valores de medida (píxeles, porcentajes o milímetros; ver `MeasureType` SizeMeasureType). |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/imagesignoptions/horizontal_alignment/) | La alineación horizontal de la firma en la página del documento. |
| [image_file_path](/signature/python-net/groupdocs.signature.options/imagesignoptions/image_file_path/) | La ruta del archivo de la imagen de la firma, utilizada solo si `image_stream` no está especificado. |
| [image_stream](/signature/python-net/groupdocs.signature.options/imagesignoptions/image_stream/) | El flujo de la imagen de la firma. Si se especifica, siempre se usa en lugar de ImageFilePath. |
| [left](/signature/python-net/groupdocs.signature.options/imagesignoptions/left/) | La posición X izquierda de la firma en la página del documento en valores de medida (píxeles, porcentajes o milímetros). Funciona si no se especifica la alineación horizontal. Ver `MeasureType` para el tipo de medida de ubicación. |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/imagesignoptions/location_measure_type/) | El tipo de medida (píxeles, porcentajes o milímetros) para las propiedades izquierda y superior. |
| [margin](/signature/python-net/groupdocs.signature.options/imagesignoptions/margin/) | El espacio entre la firma y los bordes del documento. Funciona solo si se especifican la alineación horizontal o vertical. |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/imagesignoptions/margin_measure_type/) | El tipo de medida (píxeles, porcentajes o milímetros) para el margen. |
| [rectangle](/signature/python-net/groupdocs.signature.options/imagesignoptions/rectangle/) | El rectángulo del área donde colocar la imagen en el documento. |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/imagesignoptions/rotation_angle/) | El ángulo de rotación de la firma en la página del documento (en sentido horario). |
| [shape_position](/signature/python-net/groupdocs.signature.options/imagesignoptions/shape_position/) | La posición de la forma define dónde debe presentarse la forma en el diseño del documento. Disponible solo para documentos Word. |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/imagesignoptions/size_measure_type/) | El tipo de medida (píxeles, porcentajes o milímetros) para las propiedades Width y Height. |
| [stretch](/signature/python-net/groupdocs.signature.options/imagesignoptions/stretch/) | El modo de estiramiento en la página del documento. |
| [top](/signature/python-net/groupdocs.signature.options/imagesignoptions/top/) | La posición Y superior de la firma en la página del documento en valores de medida (píxeles, porcentajes o milímetros) según lo definido por `MeasureType` LocationMeasureType. Funciona si no se especifica la alineación vertical. |
| [transparency](/signature/python-net/groupdocs.signature.options/imagesignoptions/transparency/) | La transparencia de la firma, que varía de 0.0 (opaco) a 1.0 (claro), por defecto es 0 (opaco). |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/imagesignoptions/vertical_alignment/) | La alineación vertical de la firma en la página del documento. |
| [width](/signature/python-net/groupdocs.signature.options/imagesignoptions/width/) | El ancho de la firma en la página del documento en valores de medida (píxeles, porcentajes o milímetros `MeasureType` tipo de medida de tamaño). |
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
from groupdocs.signature.options import ImageSignOptions

def sign_with_image_signature():
    with Signature("sample.pdf") as signature:
        # Crear opciones de firma de imagen con el archivo de imagen
        options = ImageSignOptions("signature.jpg")
        # Establecer la posición y el tamaño de la firma
        options.left = 100
        options.top = 400
        options.width = 120
        options.height = 100

        result = signature.sign("signed_image.pdf", options)
        print(f"Signed with {len(result.succeeded)} image signature(s)")
```

### Guides
Guías de tareas que usan `ImageSignOptions`:

* [eSign Document with Image Signature](/signature/python-net/guides/esign-document-with-image-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)

### Ver también
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
