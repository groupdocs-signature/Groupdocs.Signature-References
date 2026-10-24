---
title: "CertificateVerifyOptions klasse"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Bevat opties om certificaatdocumenten te verifiëren."
type: docs
url: /nl/python-net/groupdocs.signature.options/certificateverifyoptions/
is_root: false
weight: 70
---


## CertificateVerifyOptions class

Bevat opties om certificaatdocumenten te verifiëren.

Meer informatie

- Basic usage of certificate documents by GroupDocs.Signature: Preview Digital Certificates properties (https://docs.groupdocs.com/signature/net/preview-certificate-properties/)

Het type CertificateVerifyOptions exposeert de volgende leden:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/__init__/) | Initialiseert een nieuw exemplaar van TextVerifyOptions met standaardwaarden. |
| [__init__](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/__init__/#subject) | Initialiseert een nieuw CertificateVerifyOptions‑object met het te verifiëren onderwerp. |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [expired](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/expired/) | De eigenschap geeft aan of het certificaat is verlopen op basis van het validatieresultaat. |
| [issuer](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/issuer/) | De certificaatuitgever om te verifiëren. |
| [match_type](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/match_type/) | Het type tekstovereenkomst dat wordt gebruikt voor verificatie. |
| [perform_chain_validation](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/perform_chain_validation/) | Het verificatieproces moet X.509‑ketenvalidatie bieden met behulp van het basisvalidatiebeleid. |
| [serial_number](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/serial_number/) | Het serienummer van het certificaat om te verifiëren. |
| [subject](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/subject/) | Het certificaatonderwerp om te verifiëren. |
| [thumbprint](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/thumbprint/) | De vingerafdruk van het certificaat om te verifiëren. |
| [all_pages](/signature/python-net/groupdocs.signature.options/verifyoptions/all_pages/) | De vlag die aangeeft of elke documentpagina moet worden geverifieerd. Standaard is de waarde True. (geërfd van [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/verifyoptions/extensions/) | De extra extensies voor verificatie van alternatieve handtekeningopties. (geërfd van [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [is_valid](/signature/python-net/groupdocs.signature.options/verifyoptions/is_valid/) | De geldige eigenschapsvlag. (geërfd van [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/verifyoptions/page_number/) | Het paginanummer van het document dat moet worden geverifieerd; indien niet ingesteld, worden alle pagina's van het document geverifieerd voor de eerste keer (minimumwaarde is 1). (geërfd van [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/verifyoptions/pages_setup/) | De pagina-opties om de te verifiëren pagina's op te geven. (geërfd van [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/verifyoptions/shape_position/) | De vormpositie in de documentlay-out die wordt gebruikt voor het verifiëren van handtekeningen in kopteksten/voetteksten. (geërfd van [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |

### Zie ook
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
