---
title: "Klassen CertificateVerifyOptions"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Behåller alternativ för att verifiera certifikatdokument."
type: docs
url: /sv/python-net/groupdocs.signature.options/certificateverifyoptions/
is_root: false
weight: 70
---


## CertificateVerifyOptions class

Behåller alternativ för att verifiera certifikatdokument.

Läs mer

- Basic usage of certificate documents by GroupDocs.Signature: Preview Digital Certificates properties (https://docs.groupdocs.com/signature/net/preview-certificate-properties/)

Typen CertificateVerifyOptions exponerar följande medlemmar:

### Konstruktörer
| Konstruktor | Beskrivning |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/__init__/) | Initierar en ny instans av TextVerifyOptions med standardvärden. |
| [__init__](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/__init__/#subject) | Initierar en ny CertificateVerifyOptions-instans med ämnet att verifiera. |

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [expired](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/expired/) | Egenskapen indikerar om certifikatet har gått ut baserat på valideringsresultatet. |
| [issuer](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/issuer/) | Certifikatutfärdaren att verifiera. |
| [match_type](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/match_type/) | Textmatchningstypen som används för verifiering. |
| [perform_chain_validation](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/perform_chain_validation/) | Verifieringsprocessen bör tillhandahålla X.509-kedjevalidering med den grundläggande valideringspolicyn. |
| [serial_number](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/serial_number/) | Certifikatets serienummer att verifiera. |
| [subject](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/subject/) | Certifikatets ämne att verifiera. |
| [thumbprint](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/thumbprint/) | Certifikatets fingeravtryck att verifiera. |
| [all_pages](/signature/python-net/groupdocs.signature.options/verifyoptions/all_pages/) | Flaggan som indikerar om varje dokumentsida ska verifieras. Som standard är värdet True. (ärvd från [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/verifyoptions/extensions/) | De extra tilläggen för verifiering av alternativa signaturalternativ. (ärvd från [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [is_valid](/signature/python-net/groupdocs.signature.options/verifyoptions/is_valid/) | Den giltiga egenskapsflaggan. (ärvd från [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/verifyoptions/page_number/) | Dokumentsidans nummer som ska verifieras; om det inte är angivet verifieras alla sidor i dokumentet för den första förekomsten (minsta värde är 1). (ärvd från [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/verifyoptions/pages_setup/) | Sidalternativen för att specificera vilka sidor som ska verifieras. (ärvd från [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/verifyoptions/shape_position/) | Formens position i dokumentlayouten som används för att verifiera signaturer i sidhuvuden/sidfötter. (ärvd från [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |

### Se även
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
