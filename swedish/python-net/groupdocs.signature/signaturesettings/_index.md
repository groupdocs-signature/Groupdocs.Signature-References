---
title: "Klassen SignatureSettings"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Representerar inställningar för att anpassa Signature-beteende."
type: docs
url: /sv/python-net/groupdocs.signature/signaturesettings/
is_root: false
weight: 140
---


## SignatureSettings class

Representerar inställningar för att anpassa beteendet för [`Signature`](/signature/python-net/groupdocs.signature/signature/).

Typen SignatureSettings visar följande medlemmar:

### Konstruktörer
| Konstruktor | Beskrivning |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature/signaturesettings/__init__/) | Initierar en standardinstans av SignatureSettings med standardvärden. |
| [__init__](/signature/python-net/groupdocs.signature/signaturesettings/__init__/#logger) | Initierar en standardinstans av SignatureSettings med Logger-implementationen. |

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [default_culture](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/) | Standardkulturen som används under dokumentbehandling. Standardvärdet är "en-US". |
| [include_standard_metadata_signatures](/signature/python-net/groupdocs.signature/signaturesettings/include_standard_metadata_signatures/) | Flaggan som indikerar om standarddokumentmetadata-signaturer såsom Författare, Ägare, skapelsedatum och ändringsdatum inkluderas i metadata-listan. |
| [log_level](/signature/python-net/groupdocs.signature/signaturesettings/log_level/) | Loggnivåflaggorna som bestämmer vilka typer av meddelanden som skickas till [`SignatureSettings.Logger`](/signature/python-net/groupdocs.signature/signaturesettings/logger/). |
| [logger](/signature/python-net/groupdocs.signature/signaturesettings/logger/) | Logger-implementationen som används för loggning (Fel, Varningar, Spår). [`ILogger`](/signature/python-net/groupdocs.signature.logging/ilogger/). |
| [save_document_on_empty_delete](/signature/python-net/groupdocs.signature/signaturesettings/save_document_on_empty_delete/) | Flaggan som bestämmer om källdokumentet sparas om när Delete-metoden inte har några påverkade signaturer att ta bort. |
| [save_document_on_empty_update](/signature/python-net/groupdocs.signature/signaturesettings/save_document_on_empty_update/) | Flaggan som bestämmer om källdokumentet sparas om när `Update`-metoden inte har några signaturer att uppdatera. |
| [show_deleted_signatures_info](/signature/python-net/groupdocs.signature/signaturesettings/show_deleted_signatures_info/) | Flaggan som bestämmer om raderade signaturer inkluderas i dokumentinforesultatet. Varje [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) har en `Deleted`-flagga som indikerar om den har raderats. |

### Se även
* module [`groupdocs.signature`](/signature/python-net/groupdocs.signature/)
