---
title: "ImageDigitalVerifyOptions klasse"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Bevat opties om digitale handtekeningen in rasterafbeeldingen te verifiëren."
type: docs
url: /nl/python-net/groupdocs.signature.options/imagedigitalverifyoptions/
is_root: false
weight: 220
---


## ImageDigitalVerifyOptions class

Bevat opties om digitale handtekeningen in rasterafbeeldingen te verifiëren.

Het type ImageDigitalVerifyOptions bevat de volgende leden:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/imagedigitalverifyoptions/__init__/) | Initialiseert een nieuw exemplaar van de ImageDigitalVerifyOptions klasse voor het verifiëren van digitale (steganografie) handtekeningen in rasterafbeeldingen. |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [detected_probability](/signature/python-net/groupdocs.signature.options/imagedigitalverifyoptions/detected_probability/) | De waarschijnlijkheid geretourneerd door AnalyzePercentageDigitalSignature (0-100). |
| [detection_threshold_percent](/signature/python-net/groupdocs.signature.options/imagedigitalverifyoptions/detection_threshold_percent/) | Het detectiedrempelpercentage voor gedeeltelijke extractie (0-100). Standaard is 75. |
| [password](/signature/python-net/groupdocs.signature.options/imagedigitalverifyoptions/password/) | Het wachtwoord dat werd gebruikt om de handtekening in te sluiten. |
| [use_full_data_extraction](/signature/python-net/groupdocs.signature.options/imagedigitalverifyoptions/use_full_data_extraction/) | De eigenschap bepaalt of volledige data-extractie (AnalyzePercentageDigitalSignature) wordt uitgevoerd voor maximale nauwkeurigheid. |
| [all_pages](/signature/python-net/groupdocs.signature.options/verifyoptions/all_pages/) | De vlag die aangeeft of elke documentpagina moet worden geverifieerd. Standaard is de waarde True. (geërfd van [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/verifyoptions/extensions/) | De extra extensies voor verificatie van alternatieve handtekeningopties. (geërfd van [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [is_valid](/signature/python-net/groupdocs.signature.options/verifyoptions/is_valid/) | De geldige eigenschapsvlag. (geërfd van [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/verifyoptions/page_number/) | Het paginanummer van het document dat moet worden geverifieerd; indien niet ingesteld, worden alle pagina's van het document geverifieerd voor de eerste keer (minimumwaarde is 1). (geërfd van [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/verifyoptions/pages_setup/) | De pagina-opties om de te verifiëren pagina's op te geven. (geërfd van [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/verifyoptions/shape_position/) | De vormpositie in de documentlay-out die wordt gebruikt voor het verifiëren van handtekeningen in kopteksten/voetteksten. (geërfd van [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |

### Zie ook
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
