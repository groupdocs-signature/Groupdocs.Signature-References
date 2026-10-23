---
title: "SignatureSettings-Klasse"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Repräsentiert Einstellungen zur Anpassung des Signature-Verhaltens."
type: docs
url: /de/python-net/groupdocs.signature/signaturesettings/
is_root: false
weight: 140
---


## SignatureSettings class

Stellt Einstellungen zur Anpassung des Verhaltens von [`Signature`](/signature/python-net/groupdocs.signature/signature/) dar.

Der Typ SignatureSettings stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature/signaturesettings/__init__/) | Initialisiert eine Standardinstanz von SignatureSettings mit Standardwerten. |
| [__init__](/signature/python-net/groupdocs.signature/signaturesettings/__init__/#logger) | Initialisiert eine Standardinstanz von SignatureSettings mit der Logger-Implementierung. |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [default_culture](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/) | Die standardmäßige Kultur, die während der Dokumentenverarbeitung verwendet wird. Der Standardwert ist "en-US". |
| [include_standard_metadata_signatures](/signature/python-net/groupdocs.signature/signaturesettings/include_standard_metadata_signatures/) | Das Flag, das angibt, ob standardmäßige Dokumentmetadaten‑Signaturen wie Autor, Eigentümer, Erstellungsdatum und Änderungsdatum in der Metadatenliste enthalten sind. |
| [log_level](/signature/python-net/groupdocs.signature/signaturesettings/log_level/) | Die Log‑Level‑Flags, die bestimmen, welche Arten von Nachrichten an [`SignatureSettings.Logger`](/signature/python-net/groupdocs.signature/signaturesettings/logger/) weitergeleitet werden. |
| [logger](/signature/python-net/groupdocs.signature/signaturesettings/logger/) | Die Logger‑Implementierung, die für das Protokollieren (Fehler, Warnungen, Traces) verwendet wird. [`ILogger`](/signature/python-net/groupdocs.signature.logging/ilogger/). |
| [save_document_on_empty_delete](/signature/python-net/groupdocs.signature/signaturesettings/save_document_on_empty_delete/) | Das Flag, das bestimmt, ob das Quell‑Dokument erneut gespeichert wird, wenn die Delete‑Methode keine betroffenen Signaturen zum Entfernen hat. |
| [save_document_on_empty_update](/signature/python-net/groupdocs.signature/signaturesettings/save_document_on_empty_update/) | Das Flag, das bestimmt, ob das Quell‑Dokument erneut gespeichert wird, wenn die `Update`‑Methode keine Signaturen zum Aktualisieren hat. |
| [show_deleted_signatures_info](/signature/python-net/groupdocs.signature/signaturesettings/show_deleted_signatures_info/) | Das Flag, das bestimmt, ob gelöschte Signaturen im Dokument‑Info‑Ergebnis enthalten sind. Jede [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) hat ein `Deleted`‑Flag, das anzeigt, ob sie gelöscht wurde. |

### Siehe auch
* module [`groupdocs.signature`](/signature/python-net/groupdocs.signature/)
