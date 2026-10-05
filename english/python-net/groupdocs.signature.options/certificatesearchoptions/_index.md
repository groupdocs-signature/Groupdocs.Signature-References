---
title: CertificateSearchOptions class
second_title: GroupDocs.Signature for Python via .NET API References
description: "Represents search options for Certificate metadata signatures."
type: docs
url: /python-net/groupdocs.signature.options/certificatesearchoptions/
is_root: false
weight: 60
---


## CertificateSearchOptions class

Represents search options for Certificate metadata signatures.

Learn more

- Advanced usage of settings of search for Metadata electronic signature with GroupDocs.Signature: Advanced search within Digital Certificate X509 documents (https://docs.groupdocs.com/display/signaturenet/advanced+search+certificate+documents)

The CertificateSearchOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/certificatesearchoptions/__init__/) | Initializes a new instance of the TextSearchOptions class with default values. |
| [__init__](/signature/python-net/groupdocs.signature.options/certificatesearchoptions/__init__/#text) | Initializes a new instance of the TextSearchOptions class with text value. |

### Properties
| Property | Description |
| :- | :- |
| [match_type](/signature/python-net/groupdocs.signature.options/certificatesearchoptions/match_type/) | The text match type used for searching. |
| [text](/signature/python-net/groupdocs.signature.options/certificatesearchoptions/text/) | The certificate property text to match on searching. |
| [all_pages](/signature/python-net/groupdocs.signature.options/searchoptions/all_pages/) | The flag indicating whether to search on each document page. By default this value is True. (inherited from [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/searchoptions/page_number/) | The document page number for searching (optional). (inherited from [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/searchoptions/pages_setup/) | The options to specify pages for signature searching. (inherited from [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/searchoptions/shape_position/) | The flag indicating whether to return the shape position in the document layout. Available only for Word documents. (inherited from [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [skip_external](/signature/python-net/groupdocs.signature.options/searchoptions/skip_external/) | The flag to return only signatures marked as `IsSignature`. By default the value is `False`, which indicates that all signatures matching the specified criteria are returned. (inherited from [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |

### See Also
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
