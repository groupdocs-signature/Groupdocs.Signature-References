---
title: "SignatureSettings klasse"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Stelt instellingen voor het aanpassen van het gedrag van Signature voor."
type: docs
url: /nl/python-net/groupdocs.signature/signaturesettings/
is_root: false
weight: 140
---


## SignatureSettings class

Stelt instellingen voor het aanpassen van het gedrag van [`Signature`](/signature/python-net/groupdocs.signature/signature/) voor.

Het type SignatureSettings exposeert de volgende leden:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature/signaturesettings/__init__/) | Initialiseert een standaard SignatureSettings‑instantie met standaardwaarden. |
| [__init__](/signature/python-net/groupdocs.signature/signaturesettings/__init__/#logger) | Initialiseert een standaard SignatureSettings‑instantie met de Logger‑implementatie. |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [default_culture](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/) | De standaardcultuur die wordt gebruikt tijdens documentverwerking. De standaardwaarde is "en-US". |
| [include_standard_metadata_signatures](/signature/python-net/groupdocs.signature/signaturesettings/include_standard_metadata_signatures/) | De vlag die aangeeft of standaard documentmetadata‑handtekeningen zoals Auteur, Eigenaar, aanmaakdatum en wijzigingsdatum zijn opgenomen in de metadata‑lijst. |
| [log_level](/signature/python-net/groupdocs.signature/signaturesettings/log_level/) | De logniveau‑vlaggen die bepalen welke soorten berichten worden doorgegeven aan [`SignatureSettings.Logger`](/signature/python-net/groupdocs.signature/signaturesettings/logger/). |
| [logger](/signature/python-net/groupdocs.signature/signaturesettings/logger/) | De logger‑implementatie die wordt gebruikt voor loggen (Errors, Warnings, Traces). [`ILogger`](/signature/python-net/groupdocs.signature.logging/ilogger/). |
| [save_document_on_empty_delete](/signature/python-net/groupdocs.signature/signaturesettings/save_document_on_empty_delete/) | De vlag die bepaalt of het brondocument opnieuw wordt opgeslagen wanneer de Delete‑methode geen getroffen handtekeningen heeft om te verwijderen. |
| [save_document_on_empty_update](/signature/python-net/groupdocs.signature/signaturesettings/save_document_on_empty_update/) | De vlag die bepaalt of het brondocument opnieuw wordt opgeslagen wanneer de `Update`‑methode geen handtekeningen heeft om bij te werken. |
| [show_deleted_signatures_info](/signature/python-net/groupdocs.signature/signaturesettings/show_deleted_signatures_info/) | De vlag die bepaalt of verwijderde handtekeningen worden opgenomen in het document‑infresultaat. Elke [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) heeft een `Deleted`‑vlag om aan te geven of deze is verwijderd. |

### Zie ook
* module [`groupdocs.signature`](/signature/python-net/groupdocs.signature/)
