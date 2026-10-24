---
title: "Clase Mailmark2D"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Codifica y decodifica el texto incrustado en el Royal Mail 2D Mailmark."
type: docs
url: /es/python-net/groupdocs.signature.domain.extensions/mailmark2d/
is_root: false
weight: 220
---


## Mailmark2D class

Codifica y decodifica el texto incrustado en el Royal Mail 2D Mailmark.

El tipo Mailmark2D expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/__init__/) | Inicializa los datos combinados de Royal Mail Mailmark con valores predeterminados de datos primarios y secundarios. |

### Métodos
| Método | Descripción |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/clone/) | Devuelve una copia de este objeto. |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [class_](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/class_/) | La clase del elemento. |
| [customer_content](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/customer_content/) | El espacio opcional para uso del cliente. |
| [customer_content_encode_mode](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/customer_content_encode_mode/) | El modo de codificación del código de barras DataMatrix. Valor predeterminado: `DataMatrixEncodeMode.c40`. |
| [data_matrix_type](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/data_matrix_type/) | El tipo Mailmark 2D define el tamaño del código de barras Data Matrix. |
| [destination_post_code_and_dps](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/destination_post_code_and_dps/) | La propiedad contiene el código postal de la dirección de entrega con DPS, que para direcciones interiores consta de un área (1‑2 caracteres), distrito (1‑2 caracteres), sector (1 carácter), unidad (2 caracteres) y DPS (2 caracteres), debe seguir un formato PAF® válido y tiene una longitud máxima de 9 caracteres. |
| [information_type_id](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/information_type_id/) | El identificador de la carga útil del código de barras Royal Mail Mailmark para cada tipo de producto. |
| [item_id](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/item_id/) | El identificador único del artículo dentro del Supply Chain ID, requerido en cada código de barras Mailmark para una identificación única durante al menos 90 días (valor máximo: 99999999). |
| [return_to_sender_post_code](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/return_to_sender_post_code/) | El código postal de devolución al remitente sin DPS. |
| [rts_flag](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/rts_flag/) | La bandera que indica qué nivel de servicio de devolución al remitente se solicita. La longitud máxima es 1. |
| [supply_chain_id](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/supply_chain_id/) | El grupo único de clientes involucrados en el envío. |
| [upu_country_id](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/upu_country_id/) | El ID de país UPU (longitud máxima: 4 caracteres). |
| [version_id](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/version_id/) | El identificador de versión del código de barras relevante para cada ID de tipo de información. |

### Ver también
* module [`groupdocs.signature.domain.extensions`](/signature/python-net/groupdocs.signature.domain.extensions/)
