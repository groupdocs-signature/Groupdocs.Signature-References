---
title: "ExportImageSaveOptions Klasse"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Stellt Speicheroptionen für den Export von Dokumenten als Bild dar."
type: docs
url: /de/python-net/groupdocs.signature.options/exportimagesaveoptions/
is_root: false
weight: 160
---


## ExportImageSaveOptions class

Stellt Speicheroptionen für den Export von Dokumenten als Bild dar.

Der Typ ExportImageSaveOptions stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/__init__/) | Initialisiert eine neue Instanz der Klasse ExportAsImageSaveOptions mit Standardwerten. |
| [__init__](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/__init__/#file_format) | Initialisiert eine neue Instanz von ExportAsImageSaveOptions mit dem angegebenen Dateiformat. |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [border](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/border/) | Die Bildecken‑Einstellungen. Standardmäßig ist dieser Wert nicht gesetzt. |
| [export_all_pages](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/export_all_pages/) | Das Flag zum Exportieren jeder Seite. |
| [page_columns](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/page_columns/) | Die Anzahl der Spalten für exportierte Bilder. Verwenden Sie diese Eigenschaft, wenn Sie Bilder in einer Reihe anordnen möchten. |
| [page_number](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/page_number/) | Die Dokumentseitenzahl für den Export (Mindestwert ist 1). |
| [pages_setup](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/pages_setup/) | Die Optionen, um die zu signierenden Seiten anzugeben. |
| [tiff_multipage](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/tiff_multipage/) | Die Dokumentseiten werden in einem TIFF‑Bild auf verschiedenen Frames platziert. |
| [add_missing_extenstion](/signature/python-net/groupdocs.signature.options/saveoptions/add_missing_extenstion/) | Das Flag bestimmt, ob automatisch eine Erweiterung hinzugefügt wird, wenn sie im Ausgabepfad fehlt. Standardwert ist False. (geerbt von [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [file_format](/signature/python-net/groupdocs.signature.options/imagesaveoptions/file_format/) | Das Dateiformat des signierten Dokuments. (geerbt von [`ImageSaveOptions`](/signature/python-net/groupdocs.signature.options/imagesaveoptions/)) |
| [overwrite_existing_files](/signature/python-net/groupdocs.signature.options/saveoptions/overwrite_existing_files/) | Das Flag gibt an, ob eine vorhandene Datei mit der neuen Ausgabedatei überschrieben werden soll. (geerbt von [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [password](/signature/python-net/groupdocs.signature.options/saveoptions/password/) | Das zum Schutz des gespeicherten signierten Dokuments verwendete Passwort. Nicht unterstützt für Bilddokumente. (geerbt von [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [use_original_password](/signature/python-net/groupdocs.signature.options/saveoptions/use_original_password/) | Das Flag gibt an, ob das Passwort aus [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/) beim Speichern des signierten Dokuments als geschützt verwendet werden soll. Der Standardwert ist True. Nicht unterstützt für Bilddokumente. (geerbt von [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |

### Siehe auch
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
