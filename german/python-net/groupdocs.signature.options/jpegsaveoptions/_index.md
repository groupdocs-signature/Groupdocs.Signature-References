---
title: "JpegSaveOptions Klasse"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Stellt JPEG-Speicheroptionen für Bilddokumente dar."
type: docs
url: /de/python-net/groupdocs.signature.options/jpegsaveoptions/
is_root: false
weight: 290
---


## JpegSaveOptions class

Stellt JPEG-Speicheroptionen für Bilddokumente dar.

Der JpegSaveOptions Typ stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/jpegsaveoptions/__init__/) | Initialisiert JpegSaveOptions mit Standardwerten. |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [bits_per_channel](/signature/python-net/groupdocs.signature.options/jpegsaveoptions/bits_per_channel/) | Die Anzahl der Bits pro Kanal für ein verlustfreies JPEG‑Bild. Unterstützte Werte liegen zwischen 2 und 8 Bits pro Kanal. |
| [color_type](/signature/python-net/groupdocs.signature.options/jpegsaveoptions/color_type/) | Der Farbtyp für JPEG‑Bilder. |
| [comment](/signature/python-net/groupdocs.signature.options/jpegsaveoptions/comment/) | Der JPEG‑Dateikommentar. |
| [compression_type](/signature/python-net/groupdocs.signature.options/jpegsaveoptions/compression_type/) | Der Kompressionstyp. |
| [quality](/signature/python-net/groupdocs.signature.options/jpegsaveoptions/quality/) | Die Bildqualität. |
| [sample_rounding_mode](/signature/python-net/groupdocs.signature.options/jpegsaveoptions/sample_rounding_mode/) | Der Stichproben‑Rundungsmodus, der verwendet wird, um einen 8‑Bit‑Wert an einen n‑Bit‑Wert von `JpegOptions.BitsPerChannel` anzupassen. |
| [add_missing_extenstion](/signature/python-net/groupdocs.signature.options/saveoptions/add_missing_extenstion/) | Das Flag bestimmt, ob automatisch eine Erweiterung hinzugefügt wird, wenn sie im Ausgabepfad fehlt. Standardwert ist False. (geerbt von [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [file_format](/signature/python-net/groupdocs.signature.options/imagesaveoptions/file_format/) | Das Dateiformat des signierten Dokuments. (geerbt von [`ImageSaveOptions`](/signature/python-net/groupdocs.signature.options/imagesaveoptions/)) |
| [overwrite_existing_files](/signature/python-net/groupdocs.signature.options/saveoptions/overwrite_existing_files/) | Das Flag gibt an, ob eine vorhandene Datei mit der neuen Ausgabedatei überschrieben werden soll. (geerbt von [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [password](/signature/python-net/groupdocs.signature.options/saveoptions/password/) | Das zum Schutz des gespeicherten signierten Dokuments verwendete Passwort. Nicht unterstützt für Bilddokumente. (geerbt von [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [use_original_password](/signature/python-net/groupdocs.signature.options/saveoptions/use_original_password/) | Das Flag gibt an, ob das Passwort aus [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/) beim Speichern des signierten Dokuments als geschützt verwendet werden soll. Der Standardwert ist True. Nicht unterstützt für Bilddokumente. (geerbt von [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |

### Siehe auch
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
