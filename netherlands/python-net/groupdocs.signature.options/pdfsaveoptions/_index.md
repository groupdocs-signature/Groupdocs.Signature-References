---
title: "PdfSaveOptions klasse"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Vertegenwoordigt opslaanopties voor PDF-documenten."
type: docs
url: /nl/python-net/groupdocs.signature.options/pdfsaveoptions/
is_root: false
weight: 340
---


## PdfSaveOptions class

Vertegenwoordigt opslaanopties voor PDF-documenten.

Het PdfSaveOptions-type bevat de volgende leden:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/__init__/) | Initialiseert een nieuw exemplaar van PdfSaveOptions met standaardwaarden. |
| [__init__](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/__init__/#file_format) | Initialiseert een nieuw exemplaar van PdfSaveOptions met het opgegeven uitvoerbestandsformaat. |
| [__init__](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/__init__/#overwrite_existing_file) | Initialiseert een nieuw exemplaar van PdfSaveOptions met een overschrijvingsvlag. |
| [__init__](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/__init__/#file_format-overwrite_existing_file) | Initialiseert een nieuw exemplaar van PdfSaveOptions met het opgegeven uitvoerbestandsformaat en overschrijvingsvlag. |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [file_format](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/file_format/) | Het bestandsformaat van het ondertekende document. |
| [permissions](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/permissions/) | De PDF-documentrechten, zoals afdrukken, wijzigen en gegevensextractie. |
| [permissions_password](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/permissions_password/) | Het machtigingswachtwoord (het primaire wachtwoord) dat nodig is om machtigingsinstellingen te wijzigen. |
| [add_missing_extenstion](/signature/python-net/groupdocs.signature.options/saveoptions/add_missing_extenstion/) | De vlag die bepaalt of er automatisch een extensie wordt toegevoegd wanneer deze ontbreekt in het uitvoerbestandspad. Standaardwaarde is False. (geërfd van [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [overwrite_existing_files](/signature/python-net/groupdocs.signature.options/saveoptions/overwrite_existing_files/) | De vlag die aangeeft of een bestaand bestand moet worden overschreven met het nieuwe uitvoerbestand. (geërfd van [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [password](/signature/python-net/groupdocs.signature.options/saveoptions/password/) | Het wachtwoord dat wordt gebruikt om het opgeslagen ondertekende document te beveiligen. Niet ondersteund voor afbeeldingsdocumenten. (geërfd van [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [use_original_password](/signature/python-net/groupdocs.signature.options/saveoptions/use_original_password/) | De vlag die aangeeft of het wachtwoord van [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/) moet worden gebruikt bij het opslaan van het ondertekende document als beschermd. De standaardwaarde is True. Niet ondersteund voor afbeeldingsdocumenten. (geërfd van [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |

### Voorbeeld

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import LoadOptions, PdfSaveOptions, QrCodeSignOptions
from groupdocs.signature.domain import QrCodeTypes

load_options = LoadOptions()
load_options.password = "1234567890"

save_options = PdfSaveOptions()
save_options.password = "new-password"
save_options.permissions_password = "new-owner-password"
save_options.use_original_password = False

qr_options = QrCodeSignOptions("Approved by John Smith", QrCodeTypes.QR)

with Signature("protected.pdf", load_options) as signature:
    result = signature.sign("signed_new_password.pdf", qr_options, save_options)
    print(f"Signatures added: {len(result.succeeded)}")
```

### Zie ook
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
