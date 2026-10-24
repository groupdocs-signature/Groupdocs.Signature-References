---
title: "DigitalSearchOptions klasse"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Vertegenwoordigt zoekopties voor digitale handtekeningen."
type: docs
url: /nl/python-net/groupdocs.signature.options/digitalsearchoptions/
is_root: false
weight: 130
---


## DigitalSearchOptions class

Vertegenwoordigt zoekopties voor digitale handtekeningen.

Meer informatie

- Basic usage of search for Digital electronic signature by GroupDocs.Signature: How to eSearch Digital signatures in a document (https://docs.groupdocs.com/display/signaturenet/Search+for+Digital+e-signatures)
- Advanced usage of settings of search for Digital electronic signature with GroupDocs.Signature: Advanced usage of eSearch Digital signatures in a document and additional settings (https://docs.groupdocs.com/display/signaturenet/Advanced+search+for+Digital+signatures)

Het DigitalSearchOptions-type bevat de volgende leden:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsearchoptions/__init__/) | Initialiseert een nieuw exemplaar van de DigitalSearchOptions‑klasse met standaardwaarden. |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [comments](/signature/python-net/groupdocs.signature.options/digitalsearchoptions/comments/) | De opmerkingen van de digitale handtekening om te zoeken. |
| [issuer_name](/signature/python-net/groupdocs.signature.options/digitalsearchoptions/issuer_name/) | De onderscheidende naam van de certificaatuitgever om naar te zoeken wanneer de waarde niet leeg is. |
| [sign_date_time_from](/signature/python-net/groupdocs.signature.options/digitalsearchoptions/sign_date_time_from/) | Het datum‑ en tijdsbereik van de digitale handtekening om te zoeken. Een nullable‑waarde wordt genegeerd. |
| [sign_date_time_to](/signature/python-net/groupdocs.signature.options/digitalsearchoptions/sign_date_time_to/) | Het einde van het datum‑ en tijdsbereik van digitale handtekeningen om te zoeken. Een null‑waarde wordt genegeerd. |
| [subject_name](/signature/python-net/groupdocs.signature.options/digitalsearchoptions/subject_name/) | De onderscheidende subjectnaam van het certificaat om naar te zoeken wanneer een niet‑lege waarde is opgegeven. |
| [all_pages](/signature/python-net/groupdocs.signature.options/searchoptions/all_pages/) | De vlag die aangeeft of er op elke documentpagina moet worden gezocht. Standaard is deze waarde True. (geërfd van [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/searchoptions/page_number/) | Het paginanummer van het document voor zoeken (optioneel). (geërfd van [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/searchoptions/pages_setup/) | De opties om pagina's op te geven voor handtekeningzoeken. (geërfd van [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/searchoptions/shape_position/) | De vlag die aangeeft of de vormpositie in de documentlay-out moet worden geretourneerd. Alleen beschikbaar voor Word‑documenten. (geërfd van [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [skip_external](/signature/python-net/groupdocs.signature.options/searchoptions/skip_external/) | De vlag om alleen handtekeningen die gemarkeerd zijn als `IsSignature` te retourneren. Standaard is de waarde `False`, wat aangeeft dat alle handtekeningen die aan de opgegeven criteria voldoen, worden geretourneerd. (geërfd van [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |

### Zie ook
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
