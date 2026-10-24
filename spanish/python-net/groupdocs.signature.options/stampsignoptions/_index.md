---
title: "Clase StampSignOptions"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Representa las opciones de firma de sello."
type: docs
url: /es/python-net/groupdocs.signature.options/stampsignoptions/
is_root: false
weight: 570
---


## StampSignOptions class

Representa las opciones de firma de sello.

Más información:
- Basic usage of creating Stamp electronic signature by GroupDocs.Signature: How to eSign document with Stamp signature (https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Stamp+signature)
- Advanced usage of settings of Stamp electronic signature with GroupDocs.Signature: Advanced usage to eSign document with Stamp signature and additional settings (https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Stamp+signature+-+advanced)

El tipo StampSignOptions expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/stampsignoptions/__init__/) | Inicializa una nueva instancia de la clase StampSignOptions con valores predeterminados. |
| [__init__](/signature/python-net/groupdocs.signature.options/stampsignoptions/__init__/#left-top-width-height) | Inicializa una nueva instancia de la clase StampSignOptions con opciones de alineación. |

### Métodos
| Método | Descripción |
| :- | :- |
| [dispose](/signature/python-net/groupdocs.signature.options/imagesignoptions/dispose/) | Limpia los recursos internos. (heredado de [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |
| [from_base64](/signature/python-net/groupdocs.signature.options/imagesignoptions/from_base64/) | Crea una nueva instancia de ImageSignOptions con una imagen predefinida a partir de una cadena Base64. (heredado de [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [background](/signature/python-net/groupdocs.signature.options/stampsignoptions/background/) | El fondo del sello. |
| [background_color_crop_type](/signature/python-net/groupdocs.signature.options/stampsignoptions/background_color_crop_type/) | El tipo de recorte del color de fondo de la firma. |
| [background_image_crop_type](/signature/python-net/groupdocs.signature.options/stampsignoptions/background_image_crop_type/) | El tipo de recorte de la imagen de fondo de la firma. |
| [height](/signature/python-net/groupdocs.signature.options/stampsignoptions/height/) | La altura del área de la firma en la página del documento en unidades de medida (píxeles, porcentajes o milímetros). |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/stampsignoptions/horizontal_alignment/) | La alineación horizontal de la imagen en una página de documento. |
| [inner_lines](/signature/python-net/groupdocs.signature.options/stampsignoptions/inner_lines/) | La lista de líneas internas renderizadas como un conjunto de rectángulos. |
| [left](/signature/python-net/groupdocs.signature.options/stampsignoptions/left/) | La posición X izquierda del área de la firma en la página del documento en unidades de medida (píxeles, porcentajes o milímetros). Ver `MeasureType` `LocationMeasureType`. |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/stampsignoptions/location_measure_type/) | El tipo de medida (píxeles, porcentajes o milímetros) para las propiedades left y top. |
| [margin](/signature/python-net/groupdocs.signature.options/stampsignoptions/margin/) | El espacio que se especifica por defecto entre la imagen y los bordes del documento (funciona si se especifica alineación horizontal o vertical). |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/stampsignoptions/margin_measure_type/) | El tipo de medida del margen (píxeles, porcentajes o milímetros). |
| [outer_lines](/signature/python-net/groupdocs.signature.options/stampsignoptions/outer_lines/) | La lista de líneas externas renderizadas como círculos concéntricos. |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/stampsignoptions/rotation_angle/) | El ángulo de rotación en sentido horario. |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/stampsignoptions/size_measure_type/) | El tipo de medida (píxeles, porcentajes o milímetros) para las propiedades Width y Height. |
| [stamp_type](/signature/python-net/groupdocs.signature.options/stampsignoptions/stamp_type/) | El tipo de sello. Por defecto es `Round`. |
| [stretch](/signature/python-net/groupdocs.signature.options/stampsignoptions/stretch/) | El modo de estiramiento en la página del documento. |
| [top](/signature/python-net/groupdocs.signature.options/stampsignoptions/top/) | La posición Y superior del área de la firma en la página del documento en unidades de medida (píxeles, porcentajes o milímetros). Ver `MeasureType` `LocationMeasureType`. |
| [transparency](/signature/python-net/groupdocs.signature.options/stampsignoptions/transparency/) | La transparencia de la firma del sello. El valor varía de 0.0 a 1.0, con un valor predeterminado de 0. |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/stampsignoptions/vertical_alignment/) | La alineación vertical del sello en una página del documento. |
| [width](/signature/python-net/groupdocs.signature.options/stampsignoptions/width/) | El ancho del área de firma en la página del documento en valores de medida (píxeles, porcentajes o milímetros). La unidad de medida se define mediante `MeasureType` SizeMeasureType. |
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
from groupdocs.signature.options import StampSignOptions

with Signature("sample.docx") as signature:
    options = StampSignOptions()
    options.left = 380
    options.top = 520
    options.width = 160
    options.height = 160
    # configure opciones adicionales de sello según sea necesario
    signature.sign(options)
```

### Ver también
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
