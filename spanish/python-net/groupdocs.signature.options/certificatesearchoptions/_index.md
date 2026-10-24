---
title: "Clase CertificateSearchOptions"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Representa las opciones de búsqueda para firmas de metadatos de certificado."
type: docs
url: /es/python-net/groupdocs.signature.options/certificatesearchoptions/
is_root: false
weight: 60
---


## CertificateSearchOptions class

Representa las opciones de búsqueda para firmas de metadatos de certificado.

Aprende más

- Advanced usage of settings of search for Metadata electronic signature with GroupDocs.Signature: Advanced search within Digital Certificate X509 documents (https://docs.groupdocs.com/display/signaturenet/advanced+search+certificate+documents)

El tipo CertificateSearchOptions expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/certificatesearchoptions/__init__/) | Inicializa una nueva instancia de la clase TextSearchOptions con valores predeterminados. |
| [__init__](/signature/python-net/groupdocs.signature.options/certificatesearchoptions/__init__/#text) | Inicializa una nueva instancia de la clase TextSearchOptions con un valor de texto. |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [match_type](/signature/python-net/groupdocs.signature.options/certificatesearchoptions/match_type/) | El tipo de coincidencia de texto usado para la búsqueda. |
| [text](/signature/python-net/groupdocs.signature.options/certificatesearchoptions/text/) | El texto de la propiedad certificate para coincidir en la búsqueda. |
| [all_pages](/signature/python-net/groupdocs.signature.options/searchoptions/all_pages/) | La bandera que indica si buscar en cada página del documento. Por defecto este valor es True. (heredado de [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/searchoptions/page_number/) | El número de página del documento para buscar (opcional). (heredado de [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/searchoptions/pages_setup/) | Las opciones para especificar páginas para la búsqueda de firmas. (heredado de [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/searchoptions/shape_position/) | La bandera que indica si devolver la posición de la forma en el diseño del documento. Disponible solo para documentos Word. (heredado de [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [skip_external](/signature/python-net/groupdocs.signature.options/searchoptions/skip_external/) | La bandera para devolver solo firmas marcadas como `IsSignature`. Por defecto el valor es `False`, lo que indica que se devuelven todas las firmas que coinciden con el criterio especificado. (heredado de [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |

### Ver también
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
