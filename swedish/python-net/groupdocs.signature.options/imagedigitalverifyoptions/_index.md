---
title: "ImageDigitalVerifyOptions-klass"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Behåller alternativ för att verifiera digitala signaturer i rasterbilder."
type: docs
url: /sv/python-net/groupdocs.signature.options/imagedigitalverifyoptions/
is_root: false
weight: 220
---


## ImageDigitalVerifyOptions class

Behåller alternativ för att verifiera digitala signaturer i rasterbilder.

ImageDigitalVerifyOptions-typen visar följande medlemmar:

### Konstruktörer
| Konstruktor | Beskrivning |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/imagedigitalverifyoptions/__init__/) | Initierar en ny instans av ImageDigitalVerifyOptions-klassen för att verifiera digitala (steganografiska) signaturer i rasterbilder. |

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [detected_probability](/signature/python-net/groupdocs.signature.options/imagedigitalverifyoptions/detected_probability/) | Sannolikheten som returneras av AnalyzePercentageDigitalSignature (0-100). |
| [detection_threshold_percent](/signature/python-net/groupdocs.signature.options/imagedigitalverifyoptions/detection_threshold_percent/) | Detekteringströskelprocenten för partiell extraktion (0-100). Standardvärdet är 75. |
| [password](/signature/python-net/groupdocs.signature.options/imagedigitalverifyoptions/password/) | Lösenordet som användes för att bädda in signaturen. |
| [use_full_data_extraction](/signature/python-net/groupdocs.signature.options/imagedigitalverifyoptions/use_full_data_extraction/) | Egenskapen bestämmer om fullständig dataextraktion (AnalyzePercentageDigitalSignature) utförs för maximal noggrannhet. |
| [all_pages](/signature/python-net/groupdocs.signature.options/verifyoptions/all_pages/) | Flaggan som indikerar om varje dokumentsida ska verifieras. Som standard är värdet True. (ärvd från [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/verifyoptions/extensions/) | De extra tilläggen för verifiering av alternativa signaturalternativ. (ärvd från [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [is_valid](/signature/python-net/groupdocs.signature.options/verifyoptions/is_valid/) | Den giltiga egenskapsflaggan. (ärvd från [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/verifyoptions/page_number/) | Dokumentsidans nummer som ska verifieras; om det inte är angivet verifieras alla sidor i dokumentet för den första förekomsten (minsta värde är 1). (ärvd från [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/verifyoptions/pages_setup/) | Sidalternativen för att specificera vilka sidor som ska verifieras. (ärvd från [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/verifyoptions/shape_position/) | Formens position i dokumentlayouten som används för att verifiera signaturer i sidhuvuden/sidfötter. (ärvd från [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |

### Se även
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
