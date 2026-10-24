---
title: "Klassen DigitalVerifyOptions"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Behåller alternativ för att verifiera ett dokuments digitala signatur."
type: docs
url: /sv/python-net/groupdocs.signature.options/digitalverifyoptions/
is_root: false
weight: 150
---


## DigitalVerifyOptions class

Behåller alternativ för att verifiera ett dokuments digitala signatur.

Läs mer

- Basic usage of verification for Digital electronic signature by GroupDocs.Signature: [How to eVerification Digital signatures in a document](https://docs.groupdocs.com/display/signaturenet/Verify+Digital+signatures+in+the+document)
- Advanced usage of settings of verification for Digital electronic signature with GroupDocs.Signature: Advanced usage of eVerification Digital signatures in a document and additional settings

Typen DigitalVerifyOptions exponerar följande medlemmar:

### Konstruktörer
| Konstruktor | Beskrivning |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/__init__/) | Initierar en DigitalVerifyOptions‑instans med standardvärden. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/__init__/#certificate_file_path) | Initierar en DigitalVerifyOptions‑instans med den angivna sökvägen till det digitala certifikatet. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/__init__/#certificate_stream) | Initierar en DigitalVerifyOptions‑instans med den angivna certifikatströmmen. |

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [certificate](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/certificate/) | X509Certificate2‑certifikatet som erhållits från certifikatets filsökväg eller ström. |
| [certificate_file_path](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/certificate_file_path/) | Filsökvägen till det digitala certifikatet. |
| [certificate_stream](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/certificate_stream/) | Strömmen för det digitala certifikatet. |
| [comments](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/comments/) | Kommentarerna för den digitala signaturen som ska valideras. |
| [contact](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/contact/) | Signaturens kontakt att validera. |
| [issuer_name](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/issuer_name/) | Utfärdarens namn på certifikatet som ska valideras. |
| [location](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/location/) | Signaturens plats att validera. |
| [password](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/password/) | Lösenordet för det digitala certifikatet om det krävs. |
| [reason](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/reason/) | Anledningen till den digitala signaturen som ska valideras. |
| [sign_date_time_from](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/sign_date_time_from/) | Starten på datum- och tidsintervallet för den digitala signaturen som ska valideras. Ett None‑värde kommer att ignoreras. |
| [sign_date_time_to](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/sign_date_time_to/) | Slutet på datum- och tidsintervallet för den digitala signaturen som ska valideras. Ett null‑värde kommer att ignoreras. |
| [subject_name](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/subject_name/) | Det särskiljande ämnesnamnet för certifikatet som ska valideras; verifieringen kontrollerar om signaturens ämnesnamn innehåller eller är lika med detta skiftlägeskänsliga värde. |
| [all_pages](/signature/python-net/groupdocs.signature.options/verifyoptions/all_pages/) | Flaggan som indikerar om varje dokumentsida ska verifieras. Som standard är värdet True. (ärvd från [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/verifyoptions/extensions/) | De extra tilläggen för verifiering av alternativa signaturalternativ. (ärvd från [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [is_valid](/signature/python-net/groupdocs.signature.options/verifyoptions/is_valid/) | Den giltiga egenskapsflaggan. (ärvd från [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/verifyoptions/page_number/) | Dokumentsidans nummer som ska verifieras; om det inte är angivet verifieras alla sidor i dokumentet för den första förekomsten (minsta värde är 1). (ärvd från [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/verifyoptions/pages_setup/) | Sidalternativen för att specificera vilka sidor som ska verifieras. (ärvd från [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/verifyoptions/shape_position/) | Formens position i dokumentlayouten som används för att verifiera signaturer i sidhuvuden/sidfötter. (ärvd från [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |

### Se även
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
