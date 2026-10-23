---
title: "DigitalSearchOptions Klasse"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Stellt Suchoptionen für digitale Signaturen dar."
type: docs
url: /de/python-net/groupdocs.signature.options/digitalsearchoptions/
is_root: false
weight: 130
---


## DigitalSearchOptions class

Stellt Suchoptionen für digitale Signaturen dar.

Mehr erfahren

- Basic usage of search for Digital electronic signature by GroupDocs.Signature: How to eSearch Digital signatures in a document (https://docs.groupdocs.com/display/signaturenet/Search+for+Digital+e-signatures)
- Advanced usage of settings of search for Digital electronic signature with GroupDocs.Signature: Advanced usage of eSearch Digital signatures in a document and additional settings (https://docs.groupdocs.com/display/signaturenet/Advanced+search+for+Digital+signatures)

Der DigitalSearchOptions Typ stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsearchoptions/__init__/) | Initialisiert eine neue Instanz der DigitalSearchOptions Klasse mit Standardwerten. |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [comments](/signature/python-net/groupdocs.signature.options/digitalsearchoptions/comments/) | Die Kommentare der zu suchenden digitalen Signatur. |
| [issuer_name](/signature/python-net/groupdocs.signature.options/digitalsearchoptions/issuer_name/) | Der Distinguished Name des Zertifikatsausstellers, nach dem gesucht werden soll, wenn der Wert nicht leer ist. |
| [sign_date_time_from](/signature/python-net/groupdocs.signature.options/digitalsearchoptions/sign_date_time_from/) | Der Datums‑ und Zeitbereich der zu suchenden digitalen Signatur. Nullbare Werte werden ignoriert. |
| [sign_date_time_to](/signature/python-net/groupdocs.signature.options/digitalsearchoptions/sign_date_time_to/) | Das Ende des Datums‑ und Zeitbereichs der zu suchenden digitalen Signaturen. Ein Nullwert wird ignoriert. |
| [subject_name](/signature/python-net/groupdocs.signature.options/digitalsearchoptions/subject_name/) | Der Distinguished Subject Name des Zertifikats, nach dem gesucht werden soll, wenn ein nicht‑leerer Wert angegeben wird. |
| [all_pages](/signature/python-net/groupdocs.signature.options/searchoptions/all_pages/) | Das Flag, das angibt, ob auf jeder Dokumentseite gesucht werden soll. Standardmäßig ist dieser Wert True. (geerbt von [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/searchoptions/page_number/) | Die Dokumentseitennummer für die Suche (optional). (geerbt von [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/searchoptions/pages_setup/) | Die Optionen, um Seiten für die Signatursuche anzugeben. (geerbt von [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/searchoptions/shape_position/) | Das Flag, das angibt, ob die Position der Form im Dokumentlayout zurückgegeben werden soll. Nur für Word‑Dokumente verfügbar. (geerbt von [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [skip_external](/signature/python-net/groupdocs.signature.options/searchoptions/skip_external/) | Das Flag, um nur Signaturen zurückzugeben, die als `IsSignature` markiert sind. Standardmäßig ist der Wert `False`, was bedeutet, dass alle Signaturen, die den angegebenen Kriterien entsprechen, zurückgegeben werden. (geerbt von [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |

### Siehe auch
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
