---
title: "Clase ImageDigitalVerifyOptions"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Mantiene opciones para verificar firmas digitales en imágenes rasterizadas."
type: docs
url: /es/python-net/groupdocs.signature.options/imagedigitalverifyoptions/
is_root: false
weight: 220
---


## ImageDigitalVerifyOptions class

Mantiene opciones para verificar firmas digitales en imágenes rasterizadas.

El tipo ImageDigitalVerifyOptions expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/imagedigitalverifyoptions/__init__/) | Inicializa una nueva instancia de la clase ImageDigitalVerifyOptions para verificar firmas digitales (esteganografía) en imágenes raster. |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [detected_probability](/signature/python-net/groupdocs.signature.options/imagedigitalverifyoptions/detected_probability/) | La probabilidad devuelta por AnalyzePercentageDigitalSignature (0-100). |
| [detection_threshold_percent](/signature/python-net/groupdocs.signature.options/imagedigitalverifyoptions/detection_threshold_percent/) | El porcentaje de umbral de detección para extracción parcial (0-100). El valor predeterminado es 75. |
| [password](/signature/python-net/groupdocs.signature.options/imagedigitalverifyoptions/password/) | La contraseña que se utilizó para incrustar la firma. |
| [use_full_data_extraction](/signature/python-net/groupdocs.signature.options/imagedigitalverifyoptions/use_full_data_extraction/) | La propiedad determina si se realiza la extracción completa de datos (AnalyzePercentageDigitalSignature) para máxima precisión. |
| [all_pages](/signature/python-net/groupdocs.signature.options/verifyoptions/all_pages/) | La bandera que indica si cada página del documento debe ser verificada. Por defecto el valor es True. (heredado de [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/verifyoptions/extensions/) | Las extensiones adicionales para la verificación de opciones de firma alternativas. (heredado de [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [is_valid](/signature/python-net/groupdocs.signature.options/verifyoptions/is_valid/) | La bandera de propiedad válida. (heredado de [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/verifyoptions/page_number/) | El número de página del documento a verificar; si no se establece, se verifican todas las páginas del documento para la primera aparición (el valor mínimo es 1). (heredado de [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/verifyoptions/pages_setup/) | Las opciones de página para especificar las páginas a verificar. (heredado de [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/verifyoptions/shape_position/) | La posición de la forma en el diseño del documento utilizada para verificar firmas en encabezados/pies de página. (heredado de [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |

### Ver también
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
