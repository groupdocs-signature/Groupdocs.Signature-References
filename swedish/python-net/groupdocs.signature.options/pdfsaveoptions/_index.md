---
title: "PdfSaveOptions-klass"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Representerar sparalternativ för PDF-dokument."
type: docs
url: /sv/python-net/groupdocs.signature.options/pdfsaveoptions/
is_root: false
weight: 340
---


## PdfSaveOptions class

Representerar sparalternativ för PDF-dokument.

Typen PdfSaveOptions visar följande medlemmar:

### Konstruktörer
| Konstruktor | Beskrivning |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/__init__/) | Initierar en ny instans av PdfSaveOptions med standardvärden. |
| [__init__](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/__init__/#file_format) | Initierar en ny instans av PdfSaveOptions med det angivna utdatafilformatet. |
| [__init__](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/__init__/#overwrite_existing_file) | Initierar en ny instans av PdfSaveOptions med en överskrivningsflagga. |
| [__init__](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/__init__/#file_format-overwrite_existing_file) | Initierar en ny instans av PdfSaveOptions med det angivna utdatafilformatet och en överskrivningsflagga. |

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [file_format](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/file_format/) | Filformatet för det signerade dokumentet. |
| [permissions](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/permissions/) | PDF-dokumentets behörigheter såsom utskrift, ändring och dataextraktion. |
| [permissions_password](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/permissions_password/) | Behörighetslösenordet (huvudlösenordet) som krävs för att ändra behörighetsinställningar. |
| [add_missing_extenstion](/signature/python-net/groupdocs.signature.options/saveoptions/add_missing_extenstion/) | Flaggan som bestämmer om en filändelse ska läggas till automatiskt när den saknas i sökvägen för utdatafilen. Standardvärdet är False. (ärvd från [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [overwrite_existing_files](/signature/python-net/groupdocs.signature.options/saveoptions/overwrite_existing_files/) | Flaggan som indikerar om en befintlig fil ska skrivas över med den nya utdatafilen. (ärvd från [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [password](/signature/python-net/groupdocs.signature.options/saveoptions/password/) | Lösenordet som används för att skydda det sparade signerade dokumentet. Stöds inte för bilddokument. (ärvd från [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [use_original_password](/signature/python-net/groupdocs.signature.options/saveoptions/use_original_password/) | Flaggan som indikerar om lösenordet från [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/) ska användas när det signerade dokumentet sparas som skyddat. Standardvärdet är True. Stöds inte för bilddokument. (ärvd från [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |

### Exempel

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

### Se även
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
