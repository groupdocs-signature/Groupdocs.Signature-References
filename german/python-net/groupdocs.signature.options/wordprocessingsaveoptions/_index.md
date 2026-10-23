---
title: "WordProcessingSaveOptions Klasse"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Stellt Speicheroptionen für Textverarbeitungsdokumente dar."
type: docs
url: /de/python-net/groupdocs.signature.options/wordprocessingsaveoptions/
is_root: false
weight: 650
---


## WordProcessingSaveOptions class

Stellt Speicheroptionen für Textverarbeitungsdokumente dar.

Der WordProcessingSaveOptions Typ stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/wordprocessingsaveoptions/__init__/) | Initialisiert eine neue Instanz der WordProcessingSaveOptions Klasse mit Standardwerten. |
| [__init__](/signature/python-net/groupdocs.signature.options/wordprocessingsaveoptions/__init__/#file_format) | Initialisiert eine neue Instanz von WordProcessingSaveOptions mit dem angegebenen Ausgabeformat. |
| [__init__](/signature/python-net/groupdocs.signature.options/wordprocessingsaveoptions/__init__/#overwrite_existing_file) | Initialisiert eine neue Instanz von WordProcessingSaveOptions mit angegebenem Ausgabetyp und Überschreibungs‑Flag. |
| [__init__](/signature/python-net/groupdocs.signature.options/wordprocessingsaveoptions/__init__/#file_format-overwrite_existing_file) | Initialisiert eine neue Instanz von WordProcessingSaveOptions mit dem angegebenen Ausgabeformat und Überschreibungs‑Flag. |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [file_format](/signature/python-net/groupdocs.signature.options/wordprocessingsaveoptions/file_format/) | Das Dateiformat des signierten Dokuments. |
| [ooxml_compliance](/signature/python-net/groupdocs.signature.options/wordprocessingsaveoptions/ooxml_compliance/) | Das optionale OOXML‑Konformitätslevel für das signierte Dokument. |
| [add_missing_extenstion](/signature/python-net/groupdocs.signature.options/saveoptions/add_missing_extenstion/) | Das Flag bestimmt, ob automatisch eine Erweiterung hinzugefügt wird, wenn sie im Ausgabepfad fehlt. Standardwert ist False. (geerbt von [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [overwrite_existing_files](/signature/python-net/groupdocs.signature.options/saveoptions/overwrite_existing_files/) | Das Flag gibt an, ob eine vorhandene Datei mit der neuen Ausgabedatei überschrieben werden soll. (geerbt von [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [password](/signature/python-net/groupdocs.signature.options/saveoptions/password/) | Das zum Schutz des gespeicherten signierten Dokuments verwendete Passwort. Nicht unterstützt für Bilddokumente. (geerbt von [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [use_original_password](/signature/python-net/groupdocs.signature.options/saveoptions/use_original_password/) | Das Flag gibt an, ob das Passwort aus [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/) beim Speichern des signierten Dokuments als geschützt verwendet werden soll. Der Standardwert ist True. Nicht unterstützt für Bilddokumente. (geerbt von [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |

### Siehe auch
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
