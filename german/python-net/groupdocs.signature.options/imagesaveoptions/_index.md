---
title: "ImageSaveOptions‑Klasse"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Stellt Speicheroptionen für Bilddokumente dar."
type: docs
url: /de/python-net/groupdocs.signature.options/imagesaveoptions/
is_root: false
weight: 230
---


## ImageSaveOptions class

Stellt Speicheroptionen für Bilddokumente dar.

Der Typ ImageSaveOptions stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/imagesaveoptions/__init__/) | Initialisiert eine neue Instanz der ImagesSaveOptions‑Klasse mit Standardwerten. |
| [__init__](/signature/python-net/groupdocs.signature.options/imagesaveoptions/__init__/#overwrite_existing_file) | Initialisiert eine neue Instanz der ImagesSaveOptions‑Klasse mit Überschreibungs‑Flag. |
| [__init__](/signature/python-net/groupdocs.signature.options/imagesaveoptions/__init__/#file_format-overwrite_existing_file) | Initialisiert eine neue Instanz von ImagesSaveOptions mit dem angegebenen Ausgabeformat und Überschreibungs‑Flag. |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [file_format](/signature/python-net/groupdocs.signature.options/imagesaveoptions/file_format/) | Das Dateiformat des signierten Dokuments. |
| [add_missing_extenstion](/signature/python-net/groupdocs.signature.options/saveoptions/add_missing_extenstion/) | Das Flag bestimmt, ob automatisch eine Erweiterung hinzugefügt wird, wenn sie im Ausgabepfad fehlt. Standardwert ist False. (geerbt von [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [overwrite_existing_files](/signature/python-net/groupdocs.signature.options/saveoptions/overwrite_existing_files/) | Das Flag gibt an, ob eine vorhandene Datei mit der neuen Ausgabedatei überschrieben werden soll. (geerbt von [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [password](/signature/python-net/groupdocs.signature.options/saveoptions/password/) | Das zum Schutz des gespeicherten signierten Dokuments verwendete Passwort. Nicht unterstützt für Bilddokumente. (geerbt von [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [use_original_password](/signature/python-net/groupdocs.signature.options/saveoptions/use_original_password/) | Das Flag gibt an, ob das Passwort aus [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/) beim Speichern des signierten Dokuments als geschützt verwendet werden soll. Der Standardwert ist True. Nicht unterstützt für Bilddokumente. (geerbt von [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |

### Siehe auch
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
