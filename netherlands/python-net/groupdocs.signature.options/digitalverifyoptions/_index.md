---
title: "DigitalVerifyOptions‑klasse"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Bevat opties om de digitale handtekening van een document te verifiëren."
type: docs
url: /nl/python-net/groupdocs.signature.options/digitalverifyoptions/
is_root: false
weight: 150
---


## DigitalVerifyOptions class

Bevat opties om de digitale handtekening van een document te verifiëren.

Meer informatie

- Basic usage of verification for Digital electronic signature by GroupDocs.Signature: [How to eVerification Digital signatures in a document](https://docs.groupdocs.com/display/signaturenet/Verify+Digital+signatures+in+the+document)
- Advanced usage of settings of verification for Digital electronic signature with GroupDocs.Signature: Advanced usage of eVerification Digital signatures in a document and additional settings

Het DigitalVerifyOptions‑type biedt de volgende leden:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/__init__/) | Initialiseert een DigitalVerifyOptions‑instantie met standaardwaarden. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/__init__/#certificate_file_path) | Initialiseert een DigitalVerifyOptions‑instantie met het opgegeven bestandspad van het digitale certificaat. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/__init__/#certificate_stream) | Initialiseert een DigitalVerifyOptions‑instantie met de opgegeven certificaat‑stream. |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [certificate](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/certificate/) | Het X509Certificate2‑certificaat verkregen van het certificaat‑bestandspad of de stream. |
| [certificate_file_path](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/certificate_file_path/) | Het bestandspad van het digitale certificaat. |
| [certificate_stream](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/certificate_stream/) | De stream van het digitale certificaat. |
| [comments](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/comments/) | De opmerkingen van de digitale handtekening die gevalideerd moet worden. |
| [contact](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/contact/) | Het handtekeningcontact om te valideren. |
| [issuer_name](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/issuer_name/) | De uitgeversnaam van het certificaat dat gevalideerd moet worden. |
| [location](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/location/) | De handtekeninglocatie om te valideren. |
| [password](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/password/) | Het wachtwoord van het digitale certificaat indien vereist. |
| [reason](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/reason/) | De reden van de digitale handtekening die gevalideerd moet worden. |
| [sign_date_time_from](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/sign_date_time_from/) | Het begin van het datum‑ en tijdsbereik van de digitale handtekening die gevalideerd moet worden. Een None‑waarde wordt genegeerd. |
| [sign_date_time_to](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/sign_date_time_to/) | Het einde van het datum‑ en tijdsbereik van de digitale handtekening die gevalideerd moet worden. Een null‑waarde wordt genegeerd. |
| [subject_name](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/subject_name/) | De subject‑distinguished‑naam van het certificaat dat gevalideerd moet worden; verificatie controleert of de subject‑naam van de handtekening deze hoofdlettergevoelige waarde bevat of gelijk is. |
| [all_pages](/signature/python-net/groupdocs.signature.options/verifyoptions/all_pages/) | De vlag die aangeeft of elke documentpagina moet worden geverifieerd. Standaard is de waarde True. (geërfd van [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/verifyoptions/extensions/) | De extra extensies voor verificatie van alternatieve handtekeningopties. (geërfd van [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [is_valid](/signature/python-net/groupdocs.signature.options/verifyoptions/is_valid/) | De geldige eigenschapsvlag. (geërfd van [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/verifyoptions/page_number/) | Het paginanummer van het document dat moet worden geverifieerd; indien niet ingesteld, worden alle pagina's van het document geverifieerd voor de eerste keer (minimumwaarde is 1). (geërfd van [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/verifyoptions/pages_setup/) | De pagina-opties om de te verifiëren pagina's op te geven. (geërfd van [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/verifyoptions/shape_position/) | De vormpositie in de documentlay-out die wordt gebruikt voor het verifiëren van handtekeningen in kopteksten/voetteksten. (geërfd van [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |

### Zie ook
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
